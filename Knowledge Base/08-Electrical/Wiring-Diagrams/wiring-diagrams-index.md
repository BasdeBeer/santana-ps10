# Santana PS10 Electrical Wiring Diagrams Index

**Source:** Service Manual PS10, Section 10: Electrical Diagrams (Pages 10-5 through 10-19)

---

## Overview

Complete electrical wiring diagrams for the Santana PS10 are contained in the Service Manual pages 10-5 through 10-19. Diagrams cover both Common Rail and Mechanical Injection engine variants with detailed connector pinouts, wire color codes, relay configurations, and component specifications.

---

## Diagram Categories and Page References

### 1. Power Supply Diagram (Common Rail) - Page 10-5

**ELECTRICAL DIAGRAMS-2: POWER SUPPLY DIAGRAM**

Comprehensive main power distribution schematic showing:

**Main Fuse Box Configuration:**
- Combination fuses for main power supply
- Individual branch fuses for major systems
- Relay assemblies for power switching
- Main switch integration

**Power Distribution Components:**
- Battery connection
- TO GENERATOR (positive output)
- TO STARTING HEATER RELAY
- TO STARTING MOTOR (activation)
- CASSETTE FUSE arrangements
- TO STARTING HEATER relay (Blue relay)

**Primary Circuits Controlled:**
1. TO REAR FOG RELAY
2. FROM COMBINATION SWITCH
3. TO LICENCE PLATE LIGHT
4. TO POSITION LIGHT (FRONT)
5. TO POSITION LIGHT (AFT)
6. TO IGNITION COL
7. TO REAR TURN
8. TO UPPER GASHER
9. TO REAR DEFOGGER
10. TO HEATED MIRROR
11. TO CIGARETTE LIGHTER
12. TO DOOR LIGHT
13. TO STOP LIGHT
14. TO HAZARD SWITCH (HORN AND DIP RELAY)
15. TO BRUSH LIGHT
16. CASSETTE FUSE (with relay)
17. TO FUEL HEATER RELAY
18. TO TRAINDOOR's VEN
19. TO FUEL PUMP RELAY
20. TO HEADLIGHT RELAY
21. TO ECU POWER SUPPLY (x2 feeds)

---

### 2. Engine Control System Electronic Fuel Injection (Connector A) - Page 10-6

**ELECTRICAL DIAGRAMS-3: ENGINE CONTROL SYSTEM ELECTRONIC FUEL INJECTION (CONNECTOR A)**

Complete engine control unit wiring showing all sensor inputs and actuator outputs:

**Engine Side Connector Pin Layout (Connector A):**
Multiple pins providing connections for:
- Engine speed signals
- Temperature sensors (coolant, intake air, fuel)
- Pressure sensors (fuel pressure, rail pressure)
- Sensor grounds
- Relay and switch inputs
- Injector command outputs
- Fuel pump control
- Thermostarter valve control
- Fan motor control
- Diagnostic signals

**Relay Assemblies Shown:**
- Engine speed relay
- Fuel pump relay
- Starting motor relay
- Fuel heater relay
- Air conditioning compressor relay

**Output Components:**
- Fuel injector circuits (4 individual injectors)
- Electric fuel pump motor
- Thermostarter heater valve
- Electromagnetic fan motor
- Air conditioning compressor clutch
- Third piston deactivator valve

**Key Circuit Functions:**
- Direct injection solenoid control
- Electronic fuel pump priming
- Temperature-dependent cold-start assist
- Emissions control optimization
- Load-based fuel adjustment

---

### 3. Engine Control System Electronic Fuel Injection (Connector B) - Page 10-7

**ELECTRICAL DIAGRAMS-4: ENGINE CONTROL SYSTEM ELECTRONIC FUEL INJECTION (CONNECTOR B)**

Detailed continuation of engine control wiring showing:

**Sensor and Input Specifications:**
- Crankshaft speed sensor connection
- Camshaft position sensor
- Air mass flow meter
- Oxygen sensor (lambda sensor)
- Boost pressure sensor
- Gear position sensor
- Vehicle speed sensor

**Display and Diagnostic Interface:**
- Engine check light signal
- Malfunction indicator integration
- Fault code generation pathways
- OBD-II diagnostic interface

**Control System Integration:**
- Transmission shift control coordination (if equipped)
- ABS system interface
- Power steering pressure signal
- Air conditioning demand signal

---

### 4. Starting Heater Valve Diagram - Page 10-8

**ELECTRICAL DIAGRAMS-5: STARTING HEATER VALVE DIAGRAM**

Fuel heater system control showing:

**Vehicle Engine Connector (Connector E) Pin Layout:**
Multiple connections for thermostarter circuit

**Main Components:**
1. Thermostarter spark plug (glow element)
2. Thermostarter electro-valve
3. Thermostarter relay
4. Starting heater relay
5. Glow lamp indicator control
6. Temperature sensor integration
7. Fuel heater solenoid

**System Operation:**
- Cold-start detection logic (fuel, coolant, and air intake temperature monitoring)
- Automatic heater element preheating (below 0°C)
- Driver feedback via indicator light
- Automatic shut-off after warm-up
- Electrical safety interlock

**Specifications:**
- Supply voltage: 13.5V battery
- Glow plug type: Ceramic heating element
- Location: Intake manifold
- Heating duration: Temperature-dependent automatic control

---

### 5. Glow Plug Starter Relay Diagram (Mechanical Injection) - Page 10-13

**ELECTRICAL DIAGRAMS-13: GLOW PLUG RELAY DIAGRAM**

Cold-start assist system for mechanical injection variant:

**Relay Configuration:**
- Multiple relay contacts (30, 31, T, FGK, I5, 50, MV)
- KSB switch for manual control
- Electrovalve switching
- Cut-off valve safety logic

**Components:**
1. Glow plug heating element
2. Preheating system sensor
3. KSB switch control
4. Electrovalve for fuel routing
5. Cut-off valve (safety shutdown)

**Circuit Protection:**
- KSB resistor for current limiting
- Preheating system sensor feedback
- Electrovalve actuation safety
- Automatic deactivation logic

---

### 6. Fuel Filter Sensors Diagram - Page 10-9

**ELECTRICAL DIAGRAMS-7: FUEL FILTER SENSORS DIAGRAM**

Fuel system monitoring with integrated sensor arrays:

**Engine Side Connector Layout (Connector E-T):**
Multiple sensor inputs for fuel monitoring

**Sensor Types:**
1. Fuel filter pressure sensors (differential pressure detection)
2. Water-in-fuel sensor
3. Fuel temperature compensation sensor
4. Fuel condition monitoring

**System Functions:**
- Clogged filter warning detection
- Water contamination alerts
- Temperature-compensated density correction
- Injection volume adjustment

**Safety Interlocks:**
- Fuel pressure override circuits
- Sensor redundancy for reliability
- Automatic shutdown on critical conditions

---

### 7. Double Stop Switch Diagram - Page 10-8

**ELECTRICAL DIAGRAMS-8: DOUBLE STOP SWITCH DIAGRAM**

Brake system electrical integration showing:

**Main Components:**
- Vehicle side switch circuit
- Brake pedal sensor
- Stop light relay activation
- Hazard warning integration

**Circuit Functions:**
- Stop light activation on braking
- Brake signal to transmission (if equipped)
- Engine management braking signal
- Traction control integration (if equipped)

---

### 8. Fuel Pump Diagram - Page 10-9

**ELECTRICAL DIAGRAMS-9: FUEL PUMP DIAGRAM**

Electric fuel pump circuit control showing:

**Pump Motor Specifications:**
- Motor type: Roller-type electric motor
- Supply voltage: 13.5V
- Current draw: 5A
- Resistance: 28.5 Ohm @ 20°C

**Circuit Components:**
- Engine side connector pinout
- Fuel pump relay
- Pump motor wiring
- Terruptor ground return
- Safety cutoff logic

**System Operation:**
1. ECU energizes fuel pump relay on key ON
2. Low-pressure pump motor starts
3. Fuel flows through filter assembly
4. High-pressure fuel pump takes suction
5. Relief valve regulates pressure
6. Fuel returns to tank via regulator

**Fault Detection:**
- Blink Code 27: Electric feed pump failure
- Relay operation verification
- Motor power and ground testing
- Pressure testing procedures

---

### 9. Diagnosis Diagram - Page 10-10

**ELECTRICAL DIAGRAMS-10: DIAGNOSIS DIAGRAM**

Diagnostic connector and test point layout:

**Connector Configuration:**
- Diagnostic access points
- Test signal routing
- Meter connection points
- Circuit validation procedures

**Test Functions:**
- Sensor signal verification
- Relay function testing
- Power supply validation
- Ground circuit confirmation
- Component isolation testing

---

### 10. AC Diagram - Page 10-11

**ELECTRICAL DIAGRAMS-11: AC DIAGRAM**

Air conditioning system electrical control:

**Main Components:**
1. AC compressor clutch solenoid
2. AC pressure sensor
3. Compressor control relay
4. Thermal switch
5. ECU climate control interface

**System Control:**
- Compressor demand from ECU
- Pressure relief activation
- Thermal protection cutoff
- Engine load management

---

### 11. Cooling System Diagram - Page 10-16

**ELECTRICAL DIAGRAMS-16: COOLING SYSTEM**

Radiator fan and thermal management:

**Main Components:**
1. Coolant temperature switch (thermal sensor)
2. Fan motor relay
3. Electric cooling fan motor
4. Temperature override circuit

**System Operation:**
- Automatic fan activation at temperature threshold
- Manual override capability
- Thermal protection logic
- Engine load compensation

**Specifications:**
- Temperature switch activation: Programmable threshold
- Fan motor voltage: 13.5V
- Relay protection: Thermal cutoff available

---

### 12. Headlamp Leveling System Diagram - Page 10-17

**ELECTRICAL DIAGRAMS-17: HEADLAMP LEVELING SYSTEM DIAGRAM**

Automatic headlight height adjustment:

**Components:**
1. Left headlamp leveling actuator
2. Right headlamp leveling actuator
3. Actuator control module
4. Headlamp leveling switch
5. Load sensor for vehicle attitude
6. Indicator feedback circuits

**Circuit Functions:**
- Vehicle load detection
- Headlight angle adjustment
- Driver manual override
- Beam angle calibration

**Wire Colors in Diagram:**
- Y/BL: Yellow/Blue (signal lines)
- R: Red (power supply)
- B: Black (ground returns)

---

### 13. Reverse Lamp Diagram - Page 10-18

**ELECTRICAL DIAGRAMS-18: REVERSE LAMP DIAGRAM**

Reverse gear indication and lighting:

**Components:**
1. Reverse gear sensor/switch
2. Control relay
3. Reverse lamp left
4. Reverse lamp right

**Circuit Features:**
- Automatic activation when reverse selected
- Relay isolation for lamp control
- Ground return through lamp fixtures
- Safe operation in reverse gear

---

### 14. Radio and Rear Window Defogger - Page 10-19

**ELECTRICAL DIAGRAMS-19: RADIO & REAR WINDOW DEFOGGER**

Audio system and rear glass heating integration:

**Radio System:**
- Power supply from main harness
- Speaker configuration (front LH, front RH, rear LH, rear RH)
- Audio amplifier connections
- Ground distribution

**Speaker Configuration:**
- Front left speaker (Lg/B, Lg, Gr/B, Gr)
- Front right speaker (B/BL, W, W/R, BL)
- Rear left speaker
- Rear right speaker

**Rear Defogger System:**
1. Defogger switch control
2. Thermal switch (temperature protection)
3. Defogger grid LH
4. Defogger grid RH
5. Defogger relay

**Defogger Operation:**
- Manual ON/OFF switch activation
- Automatic shutoff timer
- Thermal protection (prevents overheating)
- Ground return through defogger grids

---

## Wire Color Code Reference

| Code | Color |
|---|---|
| B | Black (Ground) |
| R | Red (Power) |
| W | White |
| Y | Yellow |
| Br | Brown |
| Gr | Green |
| L or BL | Blue |
| GY | Gray |
| WG | White-Green |
| Lg | Light Green |
| WR | White-Red |
| Br/R | Brown-Red (striped) |
| Y/W | Yellow-White (striped) |
| G/Y | Green-Yellow (striped) |

---

## Connector Standards

### ECU Connectors (Common Rail)
- **Connector A:** Engine control inputs/outputs
- **Connector B:** Sensor and actuator continuation
- **Connector E:** Heater and fuel system control

### Vehicle Side Connector
- Multiple-pin design with standard DIN 43650 type specifications
- Sealed plastic housing for environmental protection
- Redundant ground paths for safety

---

## Component Specifications by System

### Starting and Charging System
- Battery voltage: 13.5V nominal
- Starter motor: High-current draw (see wiring gauge specifications)
- Generator output: Regulated 13.5V ±0.5V
- Main fuse ratings: 80A, 100A (see power supply diagram)

### Engine Control (Common Rail)
- ECU supply voltage: 13.5V
- Sensor supply: 5V regulated
- Fuel pump relay: 30A capacity
- Fuel heater relay: 20A capacity
- Injector driving: Integrated ECU drivers

### Engine Control (Mechanical Injection)
- Simpler relay configuration
- Glow plug relay: Manual and thermal control
- Lower electronic component count
- Mechanical fuel pump governor

### Lighting System
- Headlamps: High beam and low beam relays
- Rear lights: Multi-circuit relay switching
- License plate light: Individual circuit
- Interior lights: Parallel relay configuration

---

## Diagnostic Information

### Fault Code Reference
Refer to Section 8 and Wiring Diagram pages for fault code meanings:
- Code 23: Fuel temperature sensor fault
- Code 27: Electric fuel pump malfunction
- Code 28: Fuel heater malfunction
- Additional codes defined in diagnostic connector documentation

### Testing Procedures
1. Visual inspection of all connectors and wiring
2. Voltage testing at key points (see diagram page references)
3. Resistance testing of sensors and actuators
4. Relay function verification
5. Diagnostic scanner connection (see diagnostic diagram page 10-10)

---

## Reference Summary

| System | Page | Key Components |
|---|---|---|
| Power Supply (Common Rail) | 10-5 | Main fuses, relays, battery distribution |
| Engine Control (Connector A) | 10-6 | Sensors, injectors, fuel pump, thermostarter |
| Engine Control (Connector B) | 10-7 | Additional sensors, diagnostic interface |
| Fuel Heater Valve | 10-8 | Thermostarter system, cold-start assist |
| Fuel Filter Sensors | 10-9 | Pressure sensors, water detection |
| Diagnosis | 10-10 | Test points, diagnostic connector |
| AC System | 10-11 | Compressor clutch, pressure control |
| Cooling System | 10-16 | Fan motor, thermal switch |
| Headlamp Leveling | 10-17 | Automatic height adjustment |
| Reverse Lamps | 10-18 | Reverse gear switching |
| Radio & Defogger | 10-19 | Audio system, rear glass heating |
| Glow Plug Relay (Mechanical) | 10-13 | Cold-start glow system |

---

## Notes

- All diagram page numbers reference Service Manual PS10, Section 10
- Wire gauges: See individual diagram specifications
- Current ratings: See fuse and relay specifications on power supply diagram (page 10-5)
- Connector pinouts: See detailed diagram enlargements on each page
- Color combinations with stripes (e.g., Y/W) represent traced or striped wires
- Ground points marked with symbol ⏚ throughout diagrams
- Power supply points marked with +13.5V or +B throughout diagrams

---

## Additional Documentation

For complete electrical service procedures, see:
- Section 8: Body Electrical System (pages 8-1 through 8-4)
- Section 10: Technical Data and Electrical Diagrams (pages 10-1 through 10-19)
- Complete service manual index for component-specific procedures

*This wiring diagram index serves as a quick reference guide. Always refer to the specific diagram pages for detailed connector pinouts, wire gauges, and current specifications.*
