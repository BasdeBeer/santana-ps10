# Cruise Control Retrofit - Santana PS10 / Bosch MS 6.3 EDC

> **Source:** Iveco forum threads (t5519 all 16 pages, t8912, t8593, t9116, t10967), EDC Housing B pinout diagram (user-supplied image), PS10 Service Manual section 6C, Iveco Aufbauherstellerschulung (bodybuilder training document), MHH AUTO forum. PS10 manuals do not document cruise control, but the EDC and pedal switches support it.

## Confidence: HIGH

- Service Manual (section 6C, p.47): "Actuators with a continuous ON/OFF signal for: Cruise control (if fitted)"
- Housing B pinout labels pins 1, 25, 32, 33 as "Au Cruise Control"
- Brake (pins 26, 31) and clutch (pin 38) switches already wired
- 140+ forum posts: every 1999-2006 Daily III with electronic injection worked plug-and-play, no ECU coding
- PS10 engine is 8140.43P (electronic common rail, Euro III) = supported variant. The 8140.43C (conventional diesel) is NOT supported.

## Pin 32: The Key Detail

Pin 32 (cable 8154) is NOT a momentary cancel button. It uses **normally-closed logic with continuous 12V:**

- **12V on pin 32 = system armed** (listening for SET+/SET-/RES commands)
- **0V on pin 32 = system off** (cruise disabled, stored speed erased)

Source: forum thread t8593 and Iveco Aufbauherstellerschulung. The Iveco Daily stalk uses a latching ON/OFF ring for this.

## Recommended Wiring: Simple (3 buttons, no toggle)

Wire pin 32 **permanently to fused 12V ignition**. The system is always armed when the key is on, dead when the key is off. No toggle switch needed. Brake and clutch cancel cruise safely.

```
                                    ┌── permanent wire ─────────── Pin 32 (always armed)
                                    │
Fuse box ► 5A fuse ► 12V IGN ──────┼── Momentary [SET+] ───────── Pin 33
                                    │
                                    ├── Momentary [SET-] ───────── Pin 1
                                    │
                                    └── Momentary [RES]  ───────── Pin 25
```

**Alternative:** Add a latching toggle switch on pin 32 if you want a master kill switch. Most Daily owners with the stalk say they never use the OFF ring.

## Pin Functions

| Pin | Cable | Function | Signal | Switch |
|-----|-------|----------|--------|--------|
| 32 | 8154 | ARM system | Continuous 12V | Wire direct (or latching toggle) |
| 33 | 8157 | SET+ (engage / speed up) | Momentary 12V | Momentary button |
| 1 | 8156 | SET- (speed down) | Momentary 12V | Momentary button |
| 25 | 8155 | RES (resume) | Momentary 12V | Momentary button |

## How to Use It

1. Drive above 30 km/h, in gear, clutch released
2. Press **SET+** once. EDC locks current speed. Foot off gas.
3. Tap **SET+** to increase, **SET-** to decrease (each tap ~1 km/h, hold for continuous)
4. **Brake or clutch** cancels cruise but preserves stored speed
5. Press **RES** to resume stored speed after brake/clutch cancel
6. Speed adjustments via SET+/SET- permanently update the stored speed

**No dashboard indicator** when cruise is active (confirmed by forum).

## Engagement Requirements

- Speed above 30 km/h (some report 40)
- In gear, clutch fully released
- Speedometer and tachometer working (EDC needs both signals)
- Both brake switches functional (not stuck)
- Clutch switch functional (system needs it to "wake up")

## Related Documents

- [retrofit-plan.md](retrofit-plan.md) - Step-by-step build plan with shopping list
- [edc-housing-b-pinout.md](edc-housing-b-pinout.md) - Full 43-pin Housing B table
- [connector-specs.md](connector-specs.md) - Bosch BDK 2.8mm crimp pin details and NL/EU suppliers
- [forum-research.md](forum-research.md) - Compiled findings from 16 pages of Iveco forum threads
- [fallback-options.md](fallback-options.md) - Troubleshooting and ECU enable options
