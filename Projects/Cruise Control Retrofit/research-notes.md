# Research Notes - Cruise Control Retrofit

## Background

The Santana PS10 was never sold with cruise control. However, the Bosch MS 6.3 EDC (shared with the Iveco Daily III) supports it. On Daily models, the stalk just sends 12V to EDC pins and it works. The PS10 has the same ECU but the cruise wiring was never installed.

Evidence cruise is supported on this PS10:
- EDC Housing B pinout explicitly labels pins 1, 25, 32, 33 as "Au Cruise Control"
- Brake pedal switch (pin 31) and clutch pedal switch (pin 38) are factory-wired
- These switches serve dual purpose: engine management AND cruise safety disengagement
- Multiple Daily III owners with the same ECU confirm plug-and-play

## Iveco Forum Findings

### Thread: Cruise control wiring (t8912)
https://ivecoforums.com/cruise-control-wiring-t8912.html
- Housing B pinout discussion confirming cruise pin assignments

### Thread: Fitting cruise control (t5519)
https://ivecoforums.com/fitting-cruise-control-t5519-s90.html
- Multiple successful installs on 2007-2010 Daily III
- Stalk P/N: 42558821 (~£50-63), alt: 42535373
- 6-pin black connector under steering column (on Daily)
- Two red input wires (cable 7155): 12V ignition power
- Four green output wires (cables 8154-8157): one per cruise function
- 10-20 minute install on Daily (stalk swap, harness pre-installed)
- "The pedal switches are designed to pass the CC in standby status, if one of these switches is faulty then CC will not operate."

### Thread: Fitting cruise control (t7529)
https://ivecoforums.com/fitting-cruise-control-t7529-s10.html
https://ivecoforums.com/fitting-cruise-control-t7529-s30.html
- 2006 models send cruise signals directly to EDC (no body computer)
- Post-2009 models may route through body computer (not relevant for PS10)
- Fuses F11 and 24 supply power
- Known issue: one user had gauges stick after install, resolved by cycling ignition

### Blog: Autostelle - MS 6.3 wiring diagram
https://autostelle.car.blog/2022/01/22/iveco-delay-bosch-ms-6-3-wiring-diagram-ecu/
- Full ECU wiring diagram (image-based)
- Confirms MS 6.3 pinout matches

## Signal Details

- Active-high: 12V at the pin = function active
- Momentary switches (not latched)
- Low current (ECU input impedance is high, milliamp range)
- No pull-down resistors, relays, or logic circuits needed
- Minimum engagement speed: ~30-40 km/h (reported, not confirmed for PS10)

## ECU Software

- MS 6.3 comes with cruise **enabled by default** on most 2006-2010 Daily III variants
- No reprogramming reported as necessary on any Daily III forum install
- Cannot 100% confirm for the PS10 variant until tested
- If not enabled: would need diagnostic software to activate (Iveco dealer or aftermarket tool)

## Open Questions

1. Does the PS10 MS 6.3 variant have cruise enabled? (Very likely yes, but test will confirm)
2. The unconnected plug in the steering column (12V + 12V-ign) - could be useful as power source, but is NOT the cruise connector
3. Minimum engagement speed on this specific ECU calibration?
