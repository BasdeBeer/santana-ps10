# Cruise Control Retrofit - Build Plan

## Approach

Wire pin 32 permanently to 12V ignition (system always armed when key is on). Three momentary buttons for SET+, SET-, RES mounted in cabin. Wires route through firewall to crimp pins in EDC Housing B.

Optional: add a latching toggle on pin 32 instead of permanent wire, if you want a master kill switch.

---

## Shopping List

| Item | Qty | Part Number | Est. Cost |
|------|-----|-------------|-----------|
| Bosch BDK 2.8mm socket contacts | 4 | 1928498056 | ~EUR 2-4 |
| Automotive wire 0.75mm2 | ~5m | - | ~EUR 5 |
| Momentary push buttons (NO) | 3 | - | ~EUR 5-15 |
| Inline fuse holder + 5A fuse | 1 | - | ~EUR 3 |
| Heat shrink tubing | assorted | - | - |
| Firewall grommet (if needed) | 1 | - | ~EUR 2 |
| *Optional:* latching toggle (SPST, 12V) | 1 | - | ~EUR 3-5 |

**Total: EUR 15-30.** See [connector-specs.md](connector-specs.md) for crimp pin suppliers.

---

## How Each Switch Works

### Pin 32 - ARM (permanent wire or toggle)

The EDC needs continuous 12V on this pin to listen for cruise commands. No 12V = system completely deaf.

**Simplest approach:** Wire it straight from fused 12V ignition. System arms automatically with the key. Brake and clutch still cancel safely. No switch needed.

**With toggle:** Flip ON = armed. Flip OFF = cruise killed AND stored speed erased. Forum users with the Daily stalk say they never use the OFF ring.

### Pin 33 - SET+ (momentary button)

Press once to engage cruise at current speed. Tap while cruising to increase speed (~1 km/h per tap). Hold to accelerate continuously.

### Pin 1 - SET- (momentary button)

Tap while cruising to decrease speed (~1 km/h per tap). Hold to decelerate continuously.

### Pin 25 - RES (momentary button)

After brake/clutch cancel, press to resume the last stored speed. Does NOT work if pin 32 was de-energized (stored speed is erased when system disarms).

### Brake / Clutch (already wired)

Cancel cruise but preserve stored speed. Preferred cancel method for daily use. Clutch cancel may cause brief engine rev-up (normal on manual).

---

## Build Steps

### Phase 1: ECU Side (Engine Bay)

1. **Prep crimp pins.** For each of the 4 pins: cut ~1.5m of 0.75mm2 wire, strip 5-6mm, solder to the BDK 2.8mm socket contact's open barrel, heat shrink the joint. Label each wire.
2. **Disconnect battery.**
3. **Release Housing B** from the ECU.
4. **Insert pins** into correct positions (see [edc-housing-b-pinout.md](edc-housing-b-pinout.md)):
   - Pin 1 (SET-): top row, far right
   - Pin 25 (RES): second row area
   - Pin 32 (ARM): bottom rows
   - Pin 33 (SET+): bottom rows
5. **Tug each wire** to confirm the pin clicked and locked.
6. **Reconnect Housing B.**
7. **Route wires** along existing loom, through firewall to cabin.

### Phase 2: Cabin Side

```
                                    ┌── permanent wire ──────── Pin 32
                                    │
Fuse box ► 5A fuse ► 12V IGN ──────┼── [SET+] momentary ───── Pin 33
                                    │
                                    ├── [SET-] momentary ───── Pin 1
                                    │
                                    └── [RES]  momentary ───── Pin 25
```

1. Find 12V ignition-positive source (fuse F11, fuse 24, or any source live only with key ON).
2. Wire through inline 5A fuse.
3. **Pin 32 wire:** connect directly to fused 12V (or through toggle switch).
4. **Button wires:** connect fused 12V to one terminal of each button, other terminal to its EDC pin wire.
5. **Mount buttons.** Suggested: `[SET-] [SET+] [RES]` in a row near steering column or centre console.

### Phase 3: Test

**Electrical check (engine off, key ON):**
- 12V at common rail after fuse
- 12V at pin 32 wire (continuous)
- 12V at pin 33/1/25 wires only when respective button pressed
- No new EDC warning lights

**Road test:**
1. Drive to 50+ km/h, in gear, clutch released
2. Press SET+ once, release accelerator
3. Car should hold speed
4. Test: brake cancel, then RES to resume
5. Test: SET+/SET- to adjust speed
6. Test: clutch cancel (shift gear), then RES

**If nothing happens:** See [fallback-options.md](fallback-options.md). Check pin positions, brake/clutch switches, instrument cluster ground, fuses.

---

## Notes

- Low-current signals only (~10mA max per pin). No relays needed.
- 5A fuse is for short-circuit protection only.
- Iveco Daily stalk (42535373 / 42558821) won't fit PS10 steering column.
- Alternative: Peugeot/Citroen aftermarket cruise stalk (~EUR 15, AliExpress) with manual wiring. Multiple forum users have done this.
