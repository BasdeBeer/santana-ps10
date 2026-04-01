# EDC Housing B - Full Pinout (Control Unit to Cab-Bonnet Cable)

> **Source:** User-supplied image of the official EDC Housing B connector diagram. Verified against Iveco forum pinout discussions.

## Connector Layout

The Housing B connector has 43 pins arranged in 3 rows plus a partial fourth. Looking at the connector face:

```
Row 1: [12] [11] [10] [9] [8]  [7]  [6]  [5]  [4]  [3]  [2]  [1]
Row 2: [24] [23] [22] [21] [20] [19] [18] [17] [16] [15] [14] [13]
Row 3: [43] [42] [41] [40] [39] [38] [37] [36] [35] [34] [33] [32]
                                          [31] [30] [29] [28] [27] [26] [25]
```

*(Refer to original image for exact physical layout)*

## Full Pin Table

| Pin | Description | Cable | Code |
|-----|-------------|-------|------|
| **1** | **Au Cruise Control (SET-)** | **8156** | **54032** |
| 2 | To load sensor on accelerator for EDC | 5157 | 85152 |
| 3 | Spare | — | — |
| 4 | To instrument panel module A1 rpm indicator repeater | 5155 | 58918 |
| 5 | Spare | — | — |
| 6 | Compressor engaged signal to EDC | 8162 | 25340 |
| 7 | To diagnostic socket | 2299 | 72027 |
| 8 | To alarm control unit | Verde | 85130 |
| 9 | EDC control unit supply | 8150 | 75000 F23 |
| 10 | EDC control unit supply | 8150 | 75000 F23 |
| 11 | Control to relay for connection with fuel tank for thermal starter (not for F1A) | 0000 | 25223 |
| 12 | To earth signal (battery negative) | 0000 | m7 |
| 13 | To load sensor on accelerator for EDC | 5156 | 85152 |
| 14 | Instrument panel module A20 rpm indicator repeater mass | 0000 | 58918 |
| 15 | Spare | — | — |
| 16 | To instrument panel module A17 rpm signal | 5614 | 58918 |
| 17 | Spare | — | — |
| 18 | Spare | — | — |
| 19 | To diagnostic socket | 1199 | 72027 |
| 20 | To key-operated fuse 2 | 8051 | 75000 F2 |
| 21 | To instrument panel module AI A30 engine preheat warning leds | 0000 | 58918 |
| 22 | EDC control unit supply | 8150 | 75000 F23 |
| 23 | To instrument panel module AI EDC A29 defect warning leds | 5156 | 53041 |
| 24 | To earth signal (battery negative) | 0000 | m7 |
| **25** | **Au Cruise Control (RES)** | **8155** | **54032** |
| 26 | Supply with stop lights on | 8153 | 25006 |
| 27 | To load sensor on accelerator for EDC | 0150 | 85152 |
| 28 | To diagnostic socket | 9932 | 72027 |
| 29 | To load sensor on accelerator for EDC | 0159 | 85152 |
| 30 | Spare | — | — |
| 31 | Supply when brake pedal is pressed | 8158 | 53565 |
| **32** | **Au Cruise Control (OFF)** | **8154** | **54032** |
| **33** | **Au Cruise Control (SET/+)** | **8157** | **54032** |
| 34 | Spare | — | — |
| 35 | To load sensor on accelerator for EDC | 5158 | 85152 |
| 36 | Spare | — | — |
| 37 | F1A preheat centre control | 1310 | 25231 |
| 38 | To clutch pressed signal relay for EDC | 0160 | 42374 |
| 39 | To alarm control unit | Bianco | 85136 |
| 40 | Control to relay for EDC engagement | 8150 | 25858 |
| 41 | EDC control unit supply | 8150 | 75000 F23 |
| 42 | Heater starter insertion remote control switch control/F1A preheat centre control | 0000/1311 | 25231 |
| 43 | To earth signal (battery negative) | 0000 | m7 |

## Cruise Control Pins Summary

| Pin | Function | Cable | Signal Type | Switch Type | Status on 24-BX-HS |
|-----|----------|-------|-------------|-------------|---------------------|
| 32 | System ARM/OFF | 8154 | **Continuous 12V** = armed, 0V = off | Latching toggle | **Empty, needs crimp pin** |
| 33 | SET+ (engage / accelerate) | 8157 | Momentary 12V pulse | Momentary button | **Empty, needs crimp pin** |
| 1 | SET- (decelerate) | 8156 | Momentary 12V pulse | Momentary button | **Empty, needs crimp pin** |
| 25 | RES (resume last speed) | 8155 | Momentary 12V pulse | Momentary button | **Empty, needs crimp pin** |

**Note:** Pin 32 uses normally-closed logic. On the Iveco Daily stalk, a latching ring maintains continuous 12V to this pin when cruise is armed. When the ring is turned to OFF (or the toggle switch is flipped off), 12V is removed and the system disables, erasing the stored speed. See [how-switches-work.md](how-switches-work.md) for details.

## Safety Disengagement Pins (already wired)

| Pin | Function | Cable | Status |
|-----|----------|-------|--------|
| 26 | Stop lights on signal | 8153 | Wired |
| 31 | Brake pedal pressed supply | 8158 | Wired |
| 38 | Clutch pressed signal relay | 0160 | Wired |

Pin 26 (stop light signal) and pin 31 (brake switch) together provide redundant brake detection. The EDC sees both and will cancel cruise on either signal.
