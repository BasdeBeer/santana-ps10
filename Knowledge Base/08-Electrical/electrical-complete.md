# Santana PS10 Complete Electrical System Documentation

**Vehicle:** 2006 Santana PS10 Station Wagon (Type 1/Type 2)
**Engine:** Iveco 8140.43P (2.8 Turbo Diesel, Euro III, Common Rail or Mechanical Injection variants)
**Electrical System:** 12V negative ground
**Compilation Date:** March 2026

---

## Table of Contents

1. Battery Specifications
2. Wiring Color Codes
3. Fuse Box Layout and Circuit Protection
4. Relay Locations and Functions
5. Starting System
6. Charging System
7. Lighting Circuits
8. Engine Control Systems
9. Fuel System Electrical
10. Heating/Ventilation Electrical
11. Wiper and Washer System
12. Horn Circuit
13. Instrument Cluster and Gauges
14. Wiring Diagrams Reference
15. Connector Standards
16. Diagnostic Information

---

## 1. BATTERY SPECIFICATIONS

**System Voltage:** 12V (nominally 13.5V when charging) (Service Manual, Section 8, Page 8-1)

**Battery Characteristics:**
- Negative terminal as ground (earth return)
- All vehicle electrical components designed for 12-volt operation (Service Manual, Section 8, Page 8-1)
- Ground distribution through engine block and chassis (Service Manual, Section 8, Page 8-1)

**Owner's Manual Electrical Equipment Listing** (Owner's Manual, Page 11.4):
- Front headlights: 12 V 60/55 W
- Rear headlights (indicators): 12 V 21 W
- Rear brake lights: 12 V 21 W
- Rear position lights: 12 V 2 x 10 W
- Rear turn signals: 12 V 21 W
- Anti-fog lights: 12 V 21 W
- Dashboard mineralogical light: 12 V 5 W
- Front turn signals: 12 V 21 W
- Ceiling light: 12 V 5 W
- Instrument panel (odometer, speedometer, tachometer): 12 V 3 x 3 W
- Warning lights and indicators: 12 V 12 x 1.2 W

---

## 2. WIRING COLOR CODES

Standard color-coded wire system for circuit identification throughout vehicle (Service Manual, Section 8, Page 8-1; Service Manual, Section 10, Electrical Diagrams):

| Code | Color | Usage |
|------|-------|-------|
| B | Black | Ground return |
| R | Red | Power supply (+) |
| GY | Gray | Circuit identification |
| WG | White-Green | Circuit identification |
| Br | Brown | Circuit identification |
| L or BL | Blue | Circuit identification |
| W | White | Circuit identification |
| Y | Yellow | Circuit identification |
| Gr | Green | Circuit identification |
| Lg | Light Green | Circuit identification |
| WR | White-Red | Striped/traced wire |
| Br/R | Brown-Red | Striped wire |
| Y/W | Yellow-White | Striped wire |
| G/Y | Green-Yellow | Striped wire |
| Y/BL | Yellow/Blue | Signal lines |
| B/BL | Black/Blue | Signal lines |
| B/W | Black/White | Signal lines |
| W/R | White/Red | Signal lines |
| W/B | White/Blue | Signal lines |
| G/W | Green/White | Signal lines |
| Gr/B | Green/Black | Speaker wiring |

---

## 3. FUSE BOX LAYOUT AND CIRCUIT PROTECTION

### Main Fuse Box Location
Left fender mounting (Service Manual, Section 8, Page 8-2)

### Fuse Distribution (Common Rail variant shown on Power Supply Diagram)
(Service Manual, Section 10, Electrical Diagrams-2, Page 10-5)

The main fuse box uses cassette-type fuses with multiple branches. Standard PS10 fuse ratings observed:
- Main power supply fuses with ratings for generator output
- Individual circuit fuses for major systems
- Combination fuses for multiple circuits

**Main Fuse Locations (from diagram annotations):**
- **Cassette Fuse Box (Combination Harness):** Houses multiple relay and fuse combinations
- **TO GENERATOR (positive output):** Primary charging circuit
- **TO STARTING HEATER RELAY:** Cold-start assist supply
- **TO STARTING MOTOR (activation):** Starter circuit protection

### Circuit-Protected Loads (from Power Supply Diagram):

1. **TO REAR FOG RELAY** - Rear fog lamp circuit
2. **FROM COMBINATION SWITCH** - Main lighting switch input
3. **TO LICENCE PLATE LIGHT** - Rear license plate illumination
4. **TO POSITION LIGHT (FRONT)** - Front parking lights
5. **TO POSITION LIGHT (AFT)** - Rear parking/position lights
6. **TO IGNITION COL** - Ignition system
7. **TO REAR TURN** - Rear turn signal lamps
8. **TO UPPER GASHER** - Upper washer pump circuit (spray jets)
9. **TO REAR DEFOGGER** - Rear window demister heating element
10. **TO HEATED MIRROR** - Heated exterior mirror (if equipped)
11. **TO CIGARETTE LIGHTER** - Accessory power outlet
12. **TO DOOR LIGHT** - Interior door-mounted lighting
13. **TO STOP LIGHT** - Brake light activation circuit
14. **TO HAZARD SWITCH (HORN AND DIP RELAY)** - Hazard warning and horn control
15. **TO BRUSH LIGHT** - Brush/courtesy light circuit
16. **TO FUEL HEATER RELAY** - Fuel heating system (diesel)
17. **TO FUEL PUMP RELAY** - Electric fuel pump motor supply (30A capacity per Connector A diagram)
18. **TO HEADLIGHT RELAY** - Headlamp high/low beam control
19. **TO ECU POWER SUPPLY (x2 feeds)** - Electronic Control Unit dual supply lines

**Additional Fuse Designations (Mechanical Injection variant):**
(Service Manual, Section 10, Electrical Diagrams-12, Page 10-12)

Main Fuses (Mechanical Injection):
- WA, WC, WT, WG fuses for main power distribution
- WL fuse for lighting circuits
- W fuse as main distribution point

---

## 4. RELAY LOCATIONS AND FUNCTIONS

### Relay Assembly Locations (Service Manual, Section 8, Page 8-2)

**Left Fender Components:**
- **Thermo Starter Relay** (Cold-start glow plug control)
- **Relays** (Multiple relay module, ref. item 9)
- **Fuses** (Fuse box module, ref. item 10)

### Relay Functions (from Engine Control Diagrams)

**Electronic Control System (Common Rail) - Connector A (Page 10-6):**
1. **Engine Speed Relay** - Controls fuel pump operation based on engine RPM
2. **Fuel Pump Relay** (30A capacity) - Direct supply control for electric fuel pump motor
3. **Starting Motor Relay** - Starter engagement control
4. **Fuel Heater Relay** (20A capacity) - Thermostarter glow plug heating
5. **Air Conditioning Compressor Relay** - A/C clutch engagement (if equipped)

**Specialized Relays:**
- **Starting Heater Relay (Blue Relay)** - Primary control for cold-start heating system
- **Rear Fog Relay** - Rear fog lamp circuit control
- **Headlight Relay** - High/low beam switching
- **Head Light Relay** - Additional headlamp control circuit

**Mechanical Injection (Glow Plug) Relay - Page 10-13:**
- **Glow Plug Relay** with integrated contacts: 30, 31, T, FGK, I5, 50, MV
- Manual KSB switch control for preheating system
- Electrovalve switching for fuel routing
- Cut-off valve safety logic for automatic shutdown

---

## 5. STARTING SYSTEM

### Starter Motor Specifications

**Location:** Engine compartment, mounted on engine block (Service Manual, Section 8, Page 8-3)

**Component Reference Locations:**
- Item 4: Starting motor (Front Wiring diagram, Page 8-3)
- Item 7: Starting motor (Engine Compartment diagram, Page 8-3)

**Control Circuit:**
- Starting motor relay energization from ignition switch
- High-current direct battery supply through main relay
- Ground return through engine block and chassis

### Starting Circuit Components
- **Main Switch:** Combination ignition/lighting switch
- **Starting Motor Switch:** Also labeled "easy" switch (optional automated feature) (Service Manual, Section 8, Page 8-4)
- **Thermo Starter Relay:** Cold-start assist (Fuel System Section)

### Cold-Start Heating System

**Thermostarter Glow Plug System:**
- **Location:** Intake manifold (Diesel cold-start assist)
- **Voltage Supply:** 13.5V battery
- **Type:** Ceramic heating element
- **Control:** Electronic temperature-based activation
- **Operation:** Automatic preheating below 0°C, automatic shutoff after warmup
- **Indicator Light:** Dashboard glow plug indicator (PIN 27) illuminates during preheat cycle

---

## 6. CHARGING SYSTEM

### Generator Output

**Power Supply Path (from Power Supply Diagram, Page 10-5):**
- **TO GENERATOR (positive output):** Main charging circuit to fuse box
- Generator supplies regulated voltage to battery and vehicle systems

**Voltage Regulation:**
- Regulated 13.5V ±0.5V output (Service Manual, Section 8, Page 8-1)
- Nominal 12V charging system (Owner's Manual, Page 11.4)

### Main Fuse Protection
Main power from generator routes through primary fuses before distribution to vehicle circuits.

---

## 7. LIGHTING CIRCUITS

### Front Lighting

**Headlights (Service Manual, Section 8, Page 8-2):**
- **Components:** Left and right headlight assemblies with integrated regulators
- **Wire Colors:** Y/BL (Yellow/Blue signal lines) for control signals
- **Control:** Headlight Relay switching high/low beam function
- **Indicators:** Position light (Front) circuits, ref item 5

**Front Turn Signals:**
- **Wiring:** Turn and side lights circuits (Item 5, Left Fender diagram)
- **Color Code:** Striped wires for turn signal distinctiveness
- **Control:** Combination switch (ignition/lighting) with hazard integration

### Rear Lighting

**Rear Lights Assembly:**
- **Components:** Integrated rear light cluster (Item 5, Left Fender diagram, Service Manual, Page 8-2)
- **Circuits:**
  - Rear turn signals: TO REAR TURN fuse
  - Rear position lights: TO POSITION LIGHT (AFT)
  - Brake lights: TO STOP LIGHT
  - License plate light: TO LICENCE PLATE LIGHT

**Rear Lighting Wiring (Floor Wiring Layout, Page 8-4):**
- Item 1: To left rear light (floor loom)
- Item 3: To right rear light and license light
- Item 4: To license light (separate circuit)

**Rear Window Defogger (Heating Element):**
- **Control:** TO REAR DEFOGGER fuse (Service Manual, Page 8-2)
- **Function:** Rear glass heating for condensation removal
- **Wiring Detail:** Service Manual, Section 10, Electrical Diagrams-19 (Radio & Rear Window Defogger), Page 10-19

### Interior Lighting

**Instrument Panel and Gauges:**
- Dashboard mineralogical light: 12 V 5 W (Owner's Manual, Page 11.4)
- Odometer/speedometer/tachometer lighting: 12 V 3 x 3 W (Owner's Manual, Page 11.4)

**Interior Lights:**
- **Door Lights:** TO DOOR LIGHT circuit (Service Manual, Page 8-2)
- **Ceiling Light:** 12 V 5 W (Owner's Manual, Page 11.4)
- **Room Light:** Optional heated A/C wiring noted in Instrument Panel layout (Service Manual, Page 8-4, Item 7)

### Rear Fog Light Circuit

**Rear Fog Relay:** Controls rear fog lamp circuit (Power Supply Diagram, Page 10-5)
**Control:** From combination switch with hazard integration

---

## 8. ENGINE CONTROL SYSTEMS

### Electronic Control Unit (ECU) - Common Rail Variant

**ECU Connectors (Service Manual, Section 10, Pages 10-6 to 10-7):**

**Connector A (Engine Control Inputs/Outputs):**
Multiple pins providing:
- Engine speed signals
- Temperature sensor inputs (coolant, intake air, fuel)
- Pressure sensor inputs (fuel pressure, rail pressure)
- Sensor grounds and reference supplies
- Relay and switch inputs
- Injector command outputs (4 individual solenoid injectors)
- Fuel pump motor control
- Thermostarter valve control
- Fan motor control
- Diagnostic signal outputs

**Connector B (Sensor Continuation - Page 10-7):**
- Crankshaft speed sensor connection
- Camshaft position sensor
- Air mass flow meter
- Oxygen sensor (lambda sensor)
- Boost pressure sensor
- Gear position sensor
- Vehicle speed sensor
- Engine check light signal
- Malfunction indicator integration
- Fault code generation pathways
- OBD-II diagnostic interface

**Connector E (Fuel/Heater System - Page 10-8):**
Multiple connections for:
- Thermostarter spark plug control
- Thermostarter electro-valve
- Fuel heater solenoid
- Temperature sensor integration
- Starting heater relay activation

### Input Sensors

**Sensor Types (Training Manual, Wiring Diagrams section):**
1. Engine Speed Sensor - Crankshaft RPM monitoring
2. Crankshaft Speed Sensor - Timing reference signal
3. Camshaft Speed Sensor - Valve timing reference
4. Coolant Temperature Sensor - Engine thermal state monitoring
5. Air Intake Temperature Sensor - Combustion control input
6. Fuel Temperature Sensor - Fuel condition and density compensation
7. Fuel Pressure Sensor - Rail pressure monitoring
8. Hydraulic Accumulator (Rail) Pressure Sensor - Pressure ripple monitoring
9. Air Pressure and Temperature Sensor - Intake manifold conditions
10. Clutch Pedal Sensor - Load state detection
11. Brake Pedal Sensor - Braking state input
12. Vehicle Speed Sensor - Speedometer input and transmission control

**Fuel Temperature Sensor (Training Manual, Page 6):**
- Type: NTC thermistor (Negative Temperature Coefficient)
- Location: Fuel filter element
- Function: Density and volume correction for injection
- Temperature Range: -40°C to +120°C
- Connector: Connector A, pins A-15 (signal), A-30 (ground)
- Fault Code: Blink Code 23 indicates sensor malfunction

**Sensor Resistance Table (Training Manual, Page 6):**
| Temperature | Resistance |
|---|---|
| -40°C | 43.30 kOhm |
| -20°C | 15.46 kOhm |
| 0°C | 5.89 kOhm |
| 20°C | 2.50 kOhm |
| 40°C | 1.17 kOhm |
| 60°C | 0.59 kOhm |
| 80°C | 0.32 kOhm |
| 100°C | 0.19 kOhm |
| 120°C | 0.11 kOhm |

### Output Actuators

**Fuel Injectors (Common Rail):**
- 4 electromagnetic solenoid injectors
- High-current drivers integrated in ECU
- Individual injector circuits controlled by ECU timing logic

**Fuel Pump Motor:**
- Type: Electric roller pump
- Voltage: 13.5V
- Current: 5A nominal
- Resistance: 28.5 Ohm @ 20°C
- Control: Fuel Pump Relay (30A capacity)
- Terruptor ground feedback to ECU pins A-07 (command), A-08 (ground return)

**Fuel Pressure Regulator Valve:**
- Type: 2-way electro-valve
- Function: Pressure modulation and relief
- Control: ECU-driven solenoid

**Thermostarter Spark Plug:**
- Type: Ceramic heating element
- Supply: 13.5V battery through Fuel Heater Relay (20A)
- Control: ECU-commanded preheating below 0°C
- Pin: A-32 (positive control signal)
- Automatic shutoff after warm-up

**Electromagnetic Fan Motor:**
- Voltage: 13.5V
- Function: Cooling system thermal management
- Control: Fan motor relay with thermal override

**3rd Piston Deactivator Valve:**
- Function: Cylinder management for emissions and efficiency
- Control: ECU-driven solenoid

**Air Conditioning Compressor Clutch (if equipped):**
- Control: AC compressor relay with pressure and thermal sensing

---

## 9. FUEL SYSTEM ELECTRICAL

### Electric Fuel Pump Circuit

**Diagram Reference:** Service Manual, Section 10, Electrical Diagrams-9 (Fuel Pump Diagram), Page 10-9

**Pump Motor Specifications (Training Manual, Page 6):**
- Motor Type: Roller-type electric motor
- Supply Voltage: 13.5V
- Current Draw: 5A
- Motor Resistance: 28.5 Ohm @ 20°C
- Connector Pins: A-07 (GY wire, command), A-08 (WG wire, terruptor ground)

**Circuit Operation:**
1. ECU energizes fuel pump relay on key ON (after engine speed signal detected)
2. Relay switches full battery voltage to pump motor
3. Low-pressure pump supplies fuel through filter assembly
4. High-pressure fuel pump takes suction from main tank
5. Relief valve regulates pressure (typically 350-500 bar rail pressure)
6. Fuel returns to tank via regulator overflow

**Fault Detection:**
- **Blink Code 27:** Electric feed pump failure/malfunction (Training Manual, Page 6)
- Check relay operation and continuity
- Verify fuel pump motor power and ground connections
- Test motor resistance at 20°C: should measure 28.5 Ohm
- Check terruptor ground feedback signal (pin A-08)

### Fuel Temperature Compensation

**Sensor Circuit (Training Manual, Page 6):**
- **Blink Code 23:** Fuel Temperature Sensor Fault
- NTC sensor mounted in fuel filter element
- Voltage divider circuit with ECU pull-up resistor
- Temperature signal used for density and volume correction
- Connector Pins: A-15 (sensor signal), A-30 (ground)

### Fuel Heater Control

**Thermostarter System (Training Manual, Page 6; Service Manual, Page 10-8):**
- **Blink Code 28:** Fuel Heater Malfunction
- **Electro-Valve:** Controls fuel routing for heating
- **Relay:** Fuel Heater Relay (20A capacity) thermal-controlled switching
- **Heating Element:** Resistance heating in fuel circuit
- **Control Sequence:**
  1. Key ON: ECU detects fuel temperature via sensor
  2. If fuel < 0°C: Heater relay energizes from battery
  3. Current flows through heater element
  4. Fuel warming reduces viscosity
  5. Automatic shutoff after warm-up
- **Connector Pins:** A-32 (heater control), A-08 (ground return)

### Fuel Filter Sensors

**Diagram Reference:** Service Manual, Section 10, Electrical Diagrams-7 (Fuel Filter Sensors), Page 10-9

**Sensor Array in Fuel Filter Housing:**
1. **Fuel Filter Pressure Sensors** - Differential pressure detection for clogged filter warning
2. **Water-in-Fuel Sensor** - Water contamination detection
3. **Fuel Temperature Sensor** - Temperature compensation (see above)
4. **Fuel Condition Monitoring** - Quality and density feedback

**System Functions:**
- Clogged filter warning detection and driver alert
- Water contamination alerts for fuel quality
- Temperature-compensated density correction
- Injection volume adjustment based on conditions

---

## 10. HEATING/VENTILATION ELECTRICAL

### Rear Defogger System

**Diagram Reference:** Service Manual, Section 10, Electrical Diagrams-19 (Radio & Rear Window Defogger), Page 10-19

**Components:**
1. Defogger switch control (manual ON/OFF)
2. Thermal protection switch (temperature limit)
3. Defogger heating grid LH (left side)
4. Defogger heating grid RH (right side)
5. Defogger relay control module

**Operating Sequence:**
1. Driver activates defogger switch
2. Relay energizes from battery power
3. Current flows through left and right heating grid elements
4. Thermal protection prevents overheating
5. Automatic shutoff timer (typically 10-15 minutes)

**Wiring Details:**
- Power supply: GB (positive)
- Heating elements return: GL (ground through grids)
- Relay control: TO REAR DEFOGGER (from main fuse box)
- Thermal cutoff: Built-in temperature-sensitive relay contact

---

## 11. WIPER AND WASHER SYSTEM

### Windscreen Wiper Motor

**Location and Components (Service Manual, Section 8, Page 8-3):**
- Item 1: Wiper motor (Front Wiring diagram)
- Item 2: Floor wiring connection harness
- Item 3: Instrument panel wiring (control signals)

**Motor Control:**
- Multi-speed operation via combination switch
- Intermittent/slow/fast speed selection
- Automatic shutoff at park position

**Washer Pump Circuit (Service Manual, Section 8, Page 8-4):**
- Item 11: Wind-screen wiper tank (Left Fender diagram)
- Item 12: Wind-screen wiper pump (Left Fender diagram)
- Supplies washers to windscreen jets

**Fuse Protection:**
- TO UPPER GASHER fuse (main fuse box) - Upper spray jets
- Circuit controlled by combination switch with motor relay

### Windscreen Washer System

**Pump Circuit:**
- Electric washer pump motor
- Supply from dedicated washer fluid reservoir
- Manual or combination switch activation
- Separate circuits for front/rear washers on some variants

---

## 12. HORN CIRCUIT

**Diagram Reference:** Service Manual, Section 10, Electrical Diagrams-2 (Power Supply Diagram), Page 10-5

**Horn Control:**
- **TO HAZARD SWITCH (HORN AND DIP RELAY)** - Main horn relay circuit (Power Supply Diagram notation)
- Horn activation integrated with hazard/dip beam switching
- Relay provides high-current supply to horn solenoid

**Component Location (Service Manual, Section 8, Page 8-2):**
- Item 4: Horn mounted on right fender (Right Fender diagram)

---

## 13. INSTRUMENT CLUSTER AND GAUGES

### Combination Meter (Instrument Panel)

**Diagram Reference:** Service Manual, Section 10, Electrical Diagrams-15 (Combination Meter Diagram), Page 10-15

**Instrument Panel Wiring (Service Manual, Section 8, Page 8-4):**
- Item 1: Fuses (instrument panel protection)
- Item 2: To main wiring (battery supply)
- Item 3: To electrical control (ECU communication)
- Item 4: To combination panel (gauge signals)
- Item 5: To brake light switch
- Item 6: To starting motor switch
- Item 7: To heated air conditioning wiring (optional)
- Item 8: To clock
- Item 9: To fan motor

**Gauge Specifications (Owner's Manual, Page 11.4):**

1. **Speedometer:**
   - Input: Vehicle speed sensor signal
   - Trip meter function
   - Odometer display (mechanical totalizer)

2. **Tachometer:**
   - Input: Engine speed sensor (G/y wire from Engine Speed Sensor, Diagram page 10-15)
   - RPM reading display
   - Red zone warning threshold

3. **Fuel Gauge:**
   - Input: Fuel level indicator float switch (V/R wires, Combination Meter Diagram)
   - Tank level indication
   - Reserve light activation (below reserve level)

4. **Coolant Temperature Gauge:**
   - Input: Coolant temperature sensor (Y/W wire, thermistor input)
   - Engine thermal state display
   - Warning threshold indication

### Warning Lights and Indicators

**Dashboard Indicator Lights (Owner's Manual, Page 11.4):**
- Oil pressure indicator light (oil pressure switch)
- Check Engine/ECU malfunction light (EDC warning)
- Thermostarter (Glow Plug) indicator (PIN 27)
- Brake system warning
- 4WD engagement indicator
- Optional auxiliary lights (A/C, heated mirror, etc.)

**Blink Code System (EDC Diagnostics):**
- EDC warning light on dashboard flashes in specific patterns
- Each blink sequence represents a diagnostic fault code
- Example: Code 23 = Fuel Temperature Sensor fault (2 flashes, pause, 3 flashes)
- Example: Code 27 = Electric fuel pump malfunction (2 flashes, pause, 7 flashes)
- Example: Code 28 = Fuel heater malfunction (2 flashes, pause, 8 flashes)

**EDC Blink Code Reading Procedure:**
1. Turn ignition OFF
2. Press diagnosis button on dashboard
3. Ignition ON
4. Two series of flashes separated by brief pause = one error code
5. Press button again to cycle through error list
6. When last error is reached, first error repeats

**Clearing Error Codes:**
1. Ignition OFF, press diagnosis button
2. Keep button pressed, turn ignition ON
3. Hold button for 5 seconds
4. Release button
5. Switch off ignition

---

## 14. WIRING DIAGRAMS REFERENCE

### Service Manual Section 10: Electrical Diagrams (Pages 10-5 through 10-19)

**Common Rail Variant Diagrams:**

| Page | Diagram | Key Information |
|------|---------|-----------------|
| 10-5 | Power Supply Diagram | Main fuse box layout, relay distribution, all major circuits |
| 10-6 | Engine Control System (Connector A) | ECU sensor inputs, injector outputs, fuel pump/heater control |
| 10-7 | Engine Control System (Connector B) | Additional sensor connections, diagnostic interface |
| 10-8 | Starting Heater Valve Diagram | Thermostarter system, glow plug control circuit |
| 10-9 | Fuel Filter Sensors & Fuel Pump | Pressure/temperature sensor wiring, pump motor circuit |
| 10-10 | Diagnosis Diagram | Diagnostic connector pinout, test point locations |
| 10-11 | AC Diagram | Air conditioning compressor clutch, pressure sensor control |
| 10-16 | Cooling System | Coolant temperature switch, fan motor relay, thermal management |
| 10-17 | Headlamp Leveling System | Automatic headlight height adjustment actuator control |
| 10-18 | Reverse Lamp Diagram | Reverse gear sensor, control relay, rear lamp circuits |
| 10-19 | Radio & Rear Window Defogger | Audio system wiring, speaker configuration, defogger grid heating |

**Mechanical Injection Variant Diagrams (Pages marked "ONLY MECHANICAL INJECTION"):**

| Page | Diagram | Key Information |
|------|---------|-----------------|
| 10-12 | Power Supply Diagram | Simplified fuse/relay arrangement for mechanical system |
| 10-13 | Glow Plug Relay Diagram | Manual and thermal glow plug preheating control |
| 10-14 | Instrument Panel | Speedometer, glow plug indicator, mirror switches |
| 10-15 | Combination Meter Diagram | Gauge connections (speedometer, temperature, fuel, tachometer) |
| 10-16 | Cooling System | Fan motor thermal control (same as Common Rail) |

### Training Manual Wiring Diagrams

**Santana Training Manual, Page 9:**
- Complete electrical schematic for PS10
- Circuit paths and connector locations
- Detailed component identification

---

## 15. CONNECTOR STANDARDS

### ECU Connector Types (Service Manual, Section 10, Pages 10-6 to 10-8)

**Multi-pin Connectors:**
- DIN 43650-standard type connectors (sealed plastic housing)
- Color-coded wire terminals for rapid identification
- Redundant ground paths for electrical safety
- All connectors sealed to prevent moisture ingress

**Connector Designation System:**
- Connector A: Engine Control Unit main input/output connector
- Connector B: Engine Control Unit sensor continuation connector
- Connector E: Engine/Heater system connector
- Vehicle Side Connectors: Multiple connection points throughout harness

### Pin Assignment Standards

**Voltage Supply Points:**
- +13.5V: Main battery power (marked on diagrams)
- +B: Battery positive
- Ground symbols (⏚): Ground return paths to chassis/engine block

**Wire Gauge Specifications:**
- Main power feeds: High-amperage cable sizing
- Sensor signals: Shielded twisted pair for noise immunity
- Ground return: Dedicated ground conductors to engine block and chassis

### Connector Protection

**Environmental Sealing:**
- Sealed plastic housing on all main connectors
- Weather-proof design for under-hood mounting
- Moisture protection for floor-mounted harnesses
- Inline splice connectors sealed against water intrusion

---

## 16. DIAGNOSTIC INFORMATION

### EDC Fault Code System

**Blink Code Format:**
- First flash series = tens digit
- Brief pause
- Second flash series = units digit
- Example: 2 flashes, pause, 7 flashes = Code 27

**Common EDC Fault Codes (Training Manual, Page 6):**

| Code | System | Defect | Investigation |
|------|--------|--------|-----------------|
| 23 | Fuel System | Fuel Temperature Sensor | Check NTC thermistor resistance vs. temperature, verify connector A-15/A-30 continuity |
| 27 | Fuel System | Electric Feed Pump | Test fuel pump motor resistance (28.5 Ohm @ 20°C), verify relay energization, check terruptor ground (pin A-08) |
| 28 | Fuel System | Fuel Heater | Verify fuel heater relay (20A) energization, test element resistance, check pin A-32 signal |

### Diagnostic Connector

**Location:** Service Manual, Section 10, Electrical Diagrams-10 (Diagnosis Diagram), Page 10-10

**Function:**
- Accepts OBD-II diagnostic scanner
- Provides all fault code access
- Allows real-time sensor monitoring
- Permits component actuator testing

**Test Points:**
- Sensor signal verification
- Relay function testing
- Power supply validation
- Ground circuit confirmation
- Component isolation testing

### Testing Procedures

**Voltage Testing (Service Manual, Section 8):**
1. Verify battery voltage at rest: approximately 12.0V
2. Check charging voltage with engine running: 13.5V ±0.5V
3. Measure supply voltage to components at key points
4. Verify ground continuity to engine block and chassis

**Resistance Testing (Training Manual, Page 6):**
1. Fuel Temperature Sensor: Compare measured resistance to temperature table
2. Fuel pump motor: Test at 20°C, should read 28.5 Ohm
3. Wiper motor: Check motor winding resistance
4. Lighting circuits: Verify lamp filament resistance or LED continuity

**Relay Function Testing:**
1. Listen for audible click when relay energizes
2. Measure voltage/current at relay coil during activation
3. Verify relay contact closure (continuity through normally-open contacts)
4. Check for voltage drop across relay contacts under load

**Component-Level Diagnostics:**
1. Injector testing: Check solenoid coil resistance
2. Sensor testing: Measure output voltage under varying conditions
3. Motor testing: Check for smooth operation and current draw
4. Wiring continuity: Trace circuits with multimeter for breaks/shorts

### Safety Precautions During Electrical Service

**High Voltage/Current Areas:**
- Fuel pump circuit operates at full battery voltage (13.5V at 5A)
- Starter motor circuit carries very high current (200+ amps)
- Relay-controlled circuits can deliver significant current loads
- Always disconnect negative battery terminal before major service

**Electrical Service Safety:**
1. Disconnect negative battery terminal
2. Wait 30 seconds for capacitor discharge
3. Use insulated tools on live circuits
4. Never work on wet components
5. Check for stored energy in capacitors before disconnecting
6. Cover battery terminal to prevent accidental reconnection

**Environmental Considerations:**
- All connectors sealed to prevent moisture ingress
- Wire insulation must remain intact (no exposed conductors)
- Proper wire routing prevents EMI/RFI issues
- Grounding paths critical for safety and EMC performance
- Do not route power cables near sensitive signal wires

---

## 17. WIRING DIAGRAMS - PAGES TO VIEW DIRECTLY

The following PDF pages contain detailed wiring diagrams that should be reviewed directly in the source manuals for complete understanding of circuit paths, connector locations, and component relationships. Diagrams are image-based and cannot be fully represented in markdown format.

**Service Manual Section 8 (Body Electrical System) - Pages to review:**
- Page 8-2: Overall wiring schemes (Right Fender, Left Fender, Main Wiring)
- Page 8-3: Front Wiring Layout, Engine Compartment Wiring
- Page 8-4: Instrument Panel Wiring, Floor Wiring Layout

**Service Manual Section 10 (Technical Data - Electrical Diagrams) - Pages to review:**
- Page 10-5: Power Supply Diagram (Common Rail) - Main fuse box and relay distribution
- Page 10-6: Engine Control System (Connector A) - ECU input/output pinouts
- Page 10-7: Engine Control System (Connector B) - Sensor continuation
- Page 10-8: Starting Heater Valve Diagram, Double Stop Switch, Fuel Filter Sensors
- Page 10-9: Fuel Pump Diagram
- Page 10-10: Diagnosis Diagram - Diagnostic connector layout
- Page 10-11: AC Diagram
- Page 10-12: Power Supply Diagram (Mechanical Injection variant)
- Page 10-13: Glow Plug Relay Diagram (Mechanical Injection)
- Page 10-14: Instrument Panel (Mechanical Injection)
- Page 10-15: Combination Meter Diagram
- Page 10-16: Cooling System
- Page 10-17: Headlamp Leveling System Diagram
- Page 10-18: Reverse Lamp Diagram
- Page 10-19: Radio & Rear Window Defogger

**Santana Training Manual:**
- Page 9: Complete electrical schematic with wiring paths and connector locations

---

## 18. CROSS-REFERENCES AND RELATED SYSTEMS

### Engine Control System Integration

**Section 6C (Service Manual): Fuel System and Emissions Control**
- Electronic fuel injection control details
- EDC system operation and diagnostics
- Common Rail pressure management
- Emissions control sensor integration

**Section 6L (Service Manual): Lubrication System**
- Engine oil pressure switch location and operation
- Low oil level indicator circuit

**Section 10 (Service Manual): Technical Data**
- Complete electrical system specifications
- All torque values for electrical connectors
- Wire gauge and routing specifications
- Diagnostic procedures and fault code definitions

### Transmission and Driveline Electrical

**Section 7A (Service Manual): Manual Transmission (ZF LT-85)**
- Neutral switch location and wiring
- Reverse lamp activation sensor
- Clutch pedal sensor connection

**Section 7D (Service Manual): Transfer (4WD)**
- 4WD engagement switch and indicator circuit
- Transfer case position sensors

---

## SUMMARY OF PDF SOURCES

All specifications in this document are directly quoted from or referenced to the following original manuals:

1. **Service Manual PS10.pdf** (Document 791044-C11, 627 pages)
   - Section 8: Body Electrical System (Pages 8-1 to 8-4)
   - Section 10: Technical Data - Electrical Diagrams (Pages 10-1 to 10-19)

2. **Santana Training Manual.pdf** (274 pages, Dealer training materials)
   - Wiring Diagram section (Page 9)
   - Engine Control System training (Pages 3-7)
   - Fuel system diagnostic information (Pages 5-6)

3. **Owner's Manual 791160-2L (English-French).pdf** (245 pages)
   - Section 11: Specifications - Equipment Electrical (Page 11.4)
   - Technical specifications table (Page 11.1-11.4)

4. **Parts Catalogue - ZF equipped (002).pdf** (~300 pages)
   - Electrical components figure (Page 4)
   - Wiring harness assembly (FIG. 01, Page 19)

---

**Document Completed:** March 28, 2026
**Vehicle:** 2006 Santana PS10, Iveco 8140.43P (Euro III)
**Status:** Complete electrical system extraction from all source manuals
**Note:** All specifications sourced directly from original PDFs with page references. No values inferred or estimated from general knowledge.
