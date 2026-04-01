# Fallback Options - If Cruise Control Doesn't Engage

> **Source:** Iveco forums (t5519, t8912), MHH AUTO forum, web research on Bosch MS 6.3 ECU programming, ECU tuning service listings. This is web-sourced information.

## Before Assuming the ECU Needs Work

The forum documents these common causes of failure that have nothing to do with ECU programming:

### 1. No ignition power on cable 8150
There may be an unpopulated relay under the dash (behind the instruments) that feeds 12V to the cruise connector. If the relay slot is empty, cruise buttons get no power even though they're wired correctly. Check fuse F11 and fuse 24.

### 2. Faulty brake switch
If a brake switch is stuck closed or wired backwards, the EDC thinks the brake is permanently pressed and will refuse to engage cruise. Two brake switches exist (pins 26 and 31). Unplug each one at a time and test. Check continuity: unplugged, pins 1-2 should show continuity; pins 2-3 should not. When pressed, pins 2-3 should activate.

### 3. Faulty clutch switch
The forum specifically mentions the system needs the clutch switch to "wake up." If the clutch switch (pin 38) is dead or disconnected, cruise may not engage. Check the brown wires on the clutch pedal switch.

### 4. Bad earth/ground on instrument cluster
If your speedometer or tachometer is erratic, the EDC isn't getting a clean speed/RPM signal. Fix the ground first. The instrument cluster earth is a known weak point.

### 5. Wrong pin position in Housing B
Double-check that each crimp pin went into the correct cavity. Wrong cavity = no signal. Use a flashlight and the pin layout diagram.

### 6. Speed below threshold
Cruise only engages above ~30 km/h. Test at 50+ km/h on a straight road.

## The Diagnostic Situation

### Your PS10's connector
The PS10 uses a **38-pin round Iveco diagnostic connector** (not standard OBD-II). It's located above the clutch pedal. The MS 6.3 speaks **ISO 9141 K-Line protocol** (KWP2000), not CAN.

### Why your adapter doesn't work
Standard OBD-II scan tools likely can't communicate because:
- The adapter may not map the K-Line pin correctly from the 38-pin round to the 16-pin OBD-II socket
- Your scan tool may not support the Iveco-specific dialect of KWP2000
- Some tools report "short circuit to ground (0.00V)" on MS 6.3, requiring direct chip access instead

### Tools that actually work with MS 6.3
| Tool | Type | Cost | Notes |
|------|------|------|-------|
| Iveco EASY / Eltrac | Genuine dealer tool | ~EUR 2,300+ | Full access, but one user saw cruise "always off" with no option to change |
| Iveco EASY clone | Chinese clone | ~EUR 50-100 | May work via K-Line, no guarantee for cruise parameters |
| KT200 | Bench programmer | ~EUR 200-400 | Reads/writes MS 6.3 via boot mode (direct PCB connection) |
| KTag | Bench programmer | ~EUR 200-400 | Supports MS 6.3 bench programming |
| FGTech Galletto 4 | Bench programmer | ~EUR 150-300 | Can tune MS 6.3 via BDM (Background Debug Mode) |

## Path 1: Send ECU to a Specialist (most practical, ~EUR 150-300)

Ship the ECU to a company that does MS 6.3 programming. Ask them to enable cruise control.

**Known MS 6.3 service providers:**
- **ECU Connection (UK)** - ecuconnection.co.uk - Does MS 6.3 programming including custom requests
- **Ziptuning** - ziptuning.com - Tunes MS 6.3 (maps for injection, boost, torque, speed limiter)
- **TuningBot** - tuningbot.com - MS 6.3 immo off and tuning

None explicitly advertise "cruise enable," but if it's a firmware flag, they have the tools to find and flip it. Contact them directly and describe what you need.

**Process:** Remove ECU from vehicle, ship it, they read the 24C16 EEPROM, modify cruise parameter, ship it back. Turnaround typically 3-7 days.

## Path 2: DIY Bench Programming (high difficulty, ~EUR 200-400 for tools)

### What's inside the ECU
- The MS 6.3 stores configuration on a **24C16 EEPROM** (serial memory chip)
- The EEPROM is **soldered to the PCB** (not socketed, cannot be simply pulled out)
- It stores maps, configuration, and immobilizer data

### How to read/write it
1. Remove ECU from vehicle
2. Open the housing
3. Connect to the PCB boot pins using a KT200 or KTag programmer
4. Read the full EEPROM dump
5. Open in **WinOLS** or **ECM Titanium** to find the cruise control enable/disable parameter
6. Modify and write back

### The catch
No public documentation exists for the exact cruise control parameter location in the MS 6.3 firmware. You'd need to compare dumps from a cruise-enabled ECU vs yours, or ask the tuning community (MHH AUTO forum has extensive MS 6.3 threads, though focused on immobilizer and speed limiter rather than cruise).

## Path 3: Swap for a Cruise-Enabled ECU (~EUR 100-200)

If another Iveco Daily III with the same 8140.43 engine had factory cruise, its ECU already has cruise enabled in firmware.

**Complication:** The 24C16 EEPROM also stores immobilizer data. You'd need to clone your immo data onto the donor ECU, which requires bench programming tools or a specialist.

## Path 4: Iveco EASY Clone (~EUR 50-100)

Try a cheap clone of the Iveco EASY diagnostic software. It communicates over K-Line via the 38-pin connector. Your existing adapter might work with this software. One forum user saw cruise parameters in EASY, though options were limited. Worth trying before more expensive options.

## What the Evidence Suggests

The strong forum consensus is that **most 2006-era MS 6.3 ECUs have cruise enabled by default.** Every electronically-injected 1999-2006 Daily III in the 16-page forum thread worked plug-and-play. The Service Manual listing cruise as a supported actuator with dedicated pins is further evidence.

The most likely outcome: you wire the switches, and it works. If it doesn't, check the basics (power, brake switches, grounds) before assuming ECU work is needed.
