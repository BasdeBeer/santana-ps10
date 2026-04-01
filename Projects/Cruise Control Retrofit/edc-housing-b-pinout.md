# EDC Housing B - Full 43-Pin Reference

Source: Pinout diagram from official Iveco documentation (user-supplied image).

## Connector Layout (looking at the connector face)

```
Row 1: [12][11][10][ 9][ 8][ 7][ 6][ 5][ 4][ 3][ 2][ 1]
Row 2: [24][23][22][21][20][19][18][17][16][15][14][13]
Row 3: [43][42][41][40][39][38][37][36][35][34][33][32]
                                  [31][30][29][28][27][26][25]
```

## All Pins

| Pin | Description | Cable | Code |
|-----|-------------|-------|------|
| **1** | **⭐ Cruise Control SET-** | **8156** | **54032** |
| 2 | Load sensor on accelerator for EDC | 5157 | 85152 |
| 3 | Spare | — | — |
| 4 | Instrument panel module A1 rpm indicator repeater | 5155 | 58918 |
| 5 | Spare | — | — |
| 6 | Compressor engaged signal to EDC | 8162 | 25340 |
| 7 | Diagnostic socket | 2299 | 72027 |
| 8 | Alarm control unit | Verde | 85130 |
| 9 | EDC control unit supply | 8150 | 75000 F23 |
| 10 | EDC control unit supply | 8150 | 75000 F23 |
| 11 | Relay for fuel tank thermal starter (not F1A) | 0000 | 25223 |
| 12 | Earth (battery negative) | 0000 | m7 |
| 13 | Load sensor on accelerator for EDC | 5156 | 85152 |
| 14 | Instrument panel A20 rpm indicator repeater mass | 0000 | 58918 |
| 15 | Spare | — | — |
| 16 | Instrument panel module A17 rpm signal | 5614 | 58918 |
| 17 | Spare | — | — |
| 18 | Spare | — | — |
| 19 | Diagnostic socket | 1199 | 72027 |
| 20 | Key-operated fuse 2 | 8051 | 75000 F2 |
| 21 | Instrument panel AI A30 preheat warning leds | 0000 | 58918 |
| 22 | EDC control unit supply | 8150 | 75000 F23 |
| 23 | Instrument panel AI EDC A29 defect warning leds | 5156 | 53041 |
| 24 | Earth (battery negative) | 0000 | m7 |
| **25** | **⭐ Cruise Control RESUME** | **8155** | **54032** |
| 26 | Supply with stop lights on | 8153 | 25006 |
| 27 | Load sensor on accelerator for EDC | 0150 | 85152 |
| 28 | Diagnostic socket | 9932 | 72027 |
| 29 | Load sensor on accelerator for EDC | 0159 | 85152 |
| 30 | Spare | — | — |
| 31 | **Supply when brake pedal pressed** | 8158 | 53565 |
| **32** | **⭐ Cruise Control OFF** | **8154** | **54032** |
| **33** | **⭐ Cruise Control SET+** | **8157** | **54032** |
| 34 | Spare | — | — |
| 35 | Load sensor on accelerator for EDC | 5158 | 85152 |
| 36 | Spare | — | — |
| 37 | F1A preheat centre control | 1310 | 25231 |
| 38 | **Clutch pressed signal relay for EDC** | 0160 | 42374 |
| 39 | Alarm control unit | Bianco | 85136 |
| 40 | Relay for EDC engagement | 8150 | 25858 |
| 41 | EDC control unit supply | 8150 | 75000 F23 |
| 42 | Heater starter / F1A preheat centre control | 0000/1311 | 25231 |
| 43 | Earth (battery negative) | 0000 | m7 |

## Pins You Need to Add

| Pin | Function | What to connect |
|-----|----------|----------------|
| 33 | SET+ (engage cruise / increase speed) | Momentary button → 12V ign |
| 1 | SET- (decrease speed) | Momentary button → 12V ign |
| 25 | RES (resume last speed) | Momentary button → 12V ign |
| 32 | OFF (cancel cruise) | Momentary button → 12V ign |

## Pins Already Working (safety disengagement)

| Pin | Function | Status |
|-----|----------|--------|
| 26 | Stop light signal | Wired |
| 31 | Brake pedal pressed | Wired |
| 38 | Clutch pedal pressed | Wired |
