# Cruise Control Forum Research - Iveco Daily III / MS 6.3 EDC

> **Source:** Iveco Forums threads t5519 (all 16 pages, 140+ posts, 2011-2024), t8912 (7 posts), t8593 (wiring diagram thread), t5551, t9116, t10967, t7529. MHH AUTO forum. Digital Kaos forum. All web-sourced information.

## Key Threads Analyzed

### 1. Fitting Cruise Control (t5519) - THE main thread, 16 pages
- 140+ posts spanning 2011 to 2024
- Multiple confirmed successful retrofits on 1999-2006 Iveco Daily III
- Consensus: plug-and-play on 3rd gen, no ECU coding required

### 2. CC Wiring Diagram (t8593)
- Critical finding: cable 8154 (OFF) uses a **normally-closed** switch
- Forum quote: "between 1 of the bigger wires (red?) and one of the smaller (green?), it was a normally closed signal for the 'off' signal"
- Cruise control power +15 is on pin 9 of the Steering Column Control connector, wire number 8879

### 3. Cruise Control Wiring (t8912)
- Retired electronics engineer (45 years experience) seeking to build custom switch panel
- Confirmed EDC16 linked to MS 6.3 (both Bosch systems)
- Component codes: 85150 ("4 channel methane control unit"), 54032 ("8 function steering column switch unit"), 25858 (relay for EDC connection)

### 4. Cruise Control Retrofit - No Connector (t10967)
- 2004 35S12 HPI, EDC16 ELT1.7
- User initially couldn't find the hidden connector
- Resolution: "finally I DID find the connector. Black, 4 green wires, 2 red, tucked away really well."

## Confirmed Successful Retrofits (from forum)

| Year | Model | Engine | Result | Notes |
|------|-------|--------|--------|-------|
| 1999 | Daily 40.C 13 | 2.8 JTD | Success | Plug and play |
| 2000 | 35S11 | 2.8 | Success | Multiple users |
| 2000 | 35S13V | 2.8L TD | Success | |
| 2001 | 50C13 | 2.8 | Success | |
| 2003 | 35C11 | 2.8 CR | Success | "30 minutes, plug and play" |
| 2003 | 35S12 | 2.8 | Success | |
| 2004 | 35S12 | 2.8 HPI | Success | Found hidden connector |
| 2005 | 35S12 | 2.8 | Success | Original poster |
| 2005 | 50C15BUS | 2.8 | Success | |
| 2005 | Daily | 2.8 | Success | |
| 2006 | Daily (late) | 2.8 | Success | 07 manufacturing date |
| 2007 | 65C18 | 3.0 | Success | |

**Failed/Required coding:**
| Year | Model | Result | Notes |
|------|-------|--------|-------|
| 2007 | 35S12 (4th gen) | Failed | 3rd gen stalk caused wiper malfunction |
| 2015 | 35S11 | Failed | Required ECU coding (~GBP 300) |

## Signal Type: Pin 32 is NOT Momentary

**Critical finding from thread t8593 and Iveco Aufbauherstellerschulung:**
- Cable 8154 (pin 32, OFF) uses normally-closed logic
- 12V present = system armed. 12V removed = system off.
- Maximum current draw: 10mA per pin
- The Iveco Daily stalk achieves this with a latching ON/OFF ring

**Pins 33, 1, 25 (SET+, SET-, RES) are momentary:**
- Active-high: 12V pulse = function active
- Spring-return stalk positions (on the Daily stalk)

## Stalk Part Numbers (for reference, won't fit PS10 column)

| Part Number | Manufacturer | Gen | Notes |
|-------------|-------------|-----|-------|
| 42535373 | VALEO | 3rd gen | Most common, ~EUR 60. Discontinued Aug 2019 |
| 42552536 | ITALAMEC | 3rd gen | Alternative, different wire arrangement |
| 42558821 | - | 3rd gen | Switch lever code |
| 28351697 | - | 4th gen+ | Requires ECU coding, not compatible with 3rd gen |
| 42568500 | - | Post-2006 | Replacement for 42558821 |

**VIN is required when ordering** - three different variants exist for Daily models. Wrong one won't work.

## Connector Details (Daily, for reference)

- 6-pin black connector hidden under steering column
- 4 green wires (cables 8154, 8155, 8156, 8157) = cruise functions
- 2 red wires (cable 8150) = 12V ignition power (joined before returning to loom)
- Location: "on the opposite side of the steering column above the light stalks, fixed near the base of the stalk, top side"
- Approximately 50% of 3rd gen Dailys have this connector pre-installed even without cruise option

## PS10 vs Daily Differences

- On the Daily: cruise wiring harness (from stalk connector to EDC) is often pre-installed
- On the PS10: **no pre-wiring exists.** EDC connector pins are empty, no harness to steering column
- The PS10 steering column is different from the Daily; the Daily stalk won't fit directly
- The PS10 Owner's Manual has no cruise control section (confirmed by reading pages 15-30, section 2 "Control and Instrument Panel")
- Both share the same Bosch MS 6.3 EDC with identical Housing B pinout

## Engine Compatibility

- **8140.43B / 8140.43P** (common rail, electronic injection, EDC): **Cruise supported**
- **8140.43C** (conventional diesel, mechanical injection): **Cruise NOT supported**
- The PS10 uses the 8140.43P (Euro III EDC) = supported variant

## Operating Behavior (from forum experience)

### Minimum speed
- 30 km/h minimum (owner's manual spec). Some users report 40 km/h.
- Cannot engage in neutral or at idle
- Requires 2nd gear or higher with clutch near bite point

### Resume quirks
- RES works after brake/clutch cancel
- RES does NOT work after using the OFF switch (stored speed erased)
- Speed adjustments via SET+/SET- permanently update the stored speed (no temporary override)

### Manual transmission issues
- Clutch cancel causes momentary engine rev-up (normal on manual)
- Downshifting while in cruise disengages it; resume doesn't perfectly restore speed after gear change
- Forum user proposed rewiring clutch switch to create "pause" function vs permanent OFF, but no one implemented it

### Dashboard
- No dashboard indicator light for cruise active (confirmed)
- No warning lights when cruise engaged or disengaged

### Fuel economy
- One user reported improvement from 6 to 8.7 km/L on continental highway driving with cruise

### Known issues
- Gauge freeze after engine shutdown (rev counter, temp, fuel stuck at last reading). One user reported this; linked to instrument cluster earth wiring, not directly caused by cruise.
- Oxidized fuse contacts can prevent cruise from getting power

## Aftermarket Alternatives

### Peugeot/Citroen stalk (EUR 15-16)
- Aftermarket cruise stalks from AliExpress/eBay
- Requires manual wiring to match Iveco cable codes
- Successfully used by multiple forum members
- Wiring map (from forum user):
  - Orange/White = RES (8155)
  - Orange = SET+ (8167/8157)
  - Green/White = Brake pedal
  - Blue = SET- (8156)
  - Blue/White = GND
  - Green = OFF (8154)

### Aftermarket cruise kits
- NCS Systems "Precision Cruise" for Iveco Daily (standalone kit, bypasses EDC)
- Not applicable to PS10 as it targets cable-throttle vehicles, and the 8140.43P uses electronic throttle via EDC

## Unanswered Questions

1. **Exact 12V threshold at EDC pin.** Likely just battery/ignition voltage (~12-14V), but no spec found.
2. **Does the PS10 variant of the MS 6.3 have cruise enabled?** Strong evidence says yes (pedal switches pre-wired, Housing B labels pins, same ECU family as Daily). Can only be confirmed by testing.
3. **Pin 32 logic polarity.** Forum evidence strongly suggests 12V = armed, 0V = off (normally-closed). Not verified against official Bosch documentation. Testing with a toggle switch will confirm.
