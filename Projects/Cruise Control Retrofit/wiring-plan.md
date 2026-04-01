# Wiring Plan - Cruise Control Retrofit

## How It Works

Each cruise function is a simple switch. Press a button, 12V goes to an EDC pin. The ECU does the rest.

```
                          ┌─── [SET+]  ───► EDC Pin 33 (cable 8157) - engage / increase speed
                          │
 12V IGN ─── 5A fuse ───┤─── [SET-]  ───► EDC Pin 1  (cable 8156) - decrease speed
                          │
                          ├─── [RES]   ───► EDC Pin 25 (cable 8155) - resume last speed
                          │
                          └─── [OFF]   ───► EDC Pin 32 (cable 8154) - cancel cruise
```

All buttons are **momentary, normally open**. Press = 12V signal. Release = no signal.

Brake pedal and clutch pedal already cancel cruise automatically (pins 31 and 38 are wired from factory).

---

## Minimum Viable: Just SET+

If you only want "hold current speed", wire just one button:

```
 12V IGN ─── 5A fuse ─── [SET+ button] ─── wire ─── EDC Pin 33
```

That's it. Press the button at your desired speed, release the accelerator, engine holds speed. Tap brake or clutch to cancel.

---

## Step by Step

### 1. Disconnect battery
You're working on the ECU connector. Disconnect the negative terminal.

### 2. Prepare crimp pins (engine bay work)

For each wire:
1. Cut ~1.5m of 0.75mm² wire (enough to reach from ECU through firewall to cabin)
2. Strip 5-6mm off one end
3. Tin the stripped wire with solder
4. Place wire in the open barrel of the BDK 2.8mm socket contact (P/N 1928498056)
5. Solder from below, let solder wick into the barrel
6. Fold the insulation barrel tabs over the wire jacket for strain relief
7. Heat shrink over the joint up to the pin shoulder

Label each wire:
- **Pin 33** = SET+ (most important)
- **Pin 1** = SET-
- **Pin 25** = RES
- **Pin 32** = OFF

### 3. Insert pins into EDC Housing B

1. Release Housing B from the ECU (it may have a locking lever or clip)
2. Looking at the connector face, locate the empty pin positions using the layout:

```
Row 1: [12][11][10][ 9][ 8][ 7][ 6][ 5][ 4][ 3][ 2][ 1] ← PIN 1 (SET-) here
Row 2: [24][23][22][21][20][19][18][17][16][15][14][13]
Row 3: [43][42][41][40][39][38][37][36][35][34][33][32] ← PIN 32 (OFF) + PIN 33 (SET+)
       ...                              [31][30][29][28][27][26][25] ← PIN 25 (RES)
```

3. Insert each pin straight into its cavity. Push until it clicks (the internal latch grabs)
4. Gently tug each wire to confirm it's locked
5. Reconnect Housing B to the ECU

### 4. Route wires to cabin

1. Bundle the wires with cable ties
2. Follow existing wiring loom where possible
3. Pass through the firewall. Options:
   - Existing rubber grommet with spare capacity
   - Near the accelerator cable pass-through
   - Near the clutch cable / hydraulic line pass-through
4. Seal the grommet after passing wires through (silicone or similar)

### 5. Wire the cabin side

1. Find your 12V ignition source:
   - **Option A:** The unconnected plug in the steering column (12V + 12V-ign you found)
   - **Option B:** Tap from the fuse box (fuse F11 or fuse 24)
   - Must be live only when ignition is ON
2. Connect through the **5A inline fuse**
3. Wire fused 12V to one terminal of each button (common feed)
4. Wire the other terminal of each button to its respective EDC wire:
   - SET+ button → wire going to pin 33
   - SET- button → wire going to pin 1
   - RES button → wire going to pin 25
   - OFF button → wire going to pin 32
5. Solder all connections, heat shrink everything

### 6. Mount buttons

Your call where to put them. Ideas:
- Blank switch slot on dashboard (if available)
- Small panel mounted near steering column
- Centre console near gear lever

### 7. Reconnect battery and test

**Electrical check (ignition on, engine off):**
- Multimeter: verify 12V at button common rail
- Press each button, measure 12V at the corresponding wire at the EDC end
- Check dashboard for any new warning lights

**Road test:**
1. Drive to a quiet road, reach ~50 km/h
2. Press SET+
3. Release accelerator
4. Engine should hold speed
5. Tap brake to cancel
6. Try RES to resume
7. Try SET+ / SET- to adjust speed in small increments

---

## If It Doesn't Work

| Symptom | Check |
|---------|-------|
| Nothing happens when pressing SET+ | Measure 12V at EDC pin 33 while pressing. If 12V present but no cruise: ECU may need cruise enabled via diagnostics |
| Cruise engages then immediately cancels | Brake or clutch switch may be stuck/faulty. Measure pins 31 and 38 with pedals released |
| Warning light on dashboard | Read EDC blink codes (diagnosis button) |
| Works but won't hold speed accurately | Normal for first test. EDC needs vehicle speed signal (already has it from injection system) |

## Safety Notes

- This is low-current signaling only (milliamps). No risk of damaging the ECU.
- The 5A fuse protects against short circuits in your wiring.
- Cruise will always disengage on brake or clutch press (factory safety, independent of your buttons).
- Test on a quiet road first. Get a feel for how it engages/disengages before using in traffic.
