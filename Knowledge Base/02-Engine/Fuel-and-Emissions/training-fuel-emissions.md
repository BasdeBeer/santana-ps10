# Santana PS10 EIII - Engine Fuel and Emission Control System Training Manual

**Engine:** Iveco 8140.43P (2.8 TD, Euro III)
**Source:** Dealer Training Manual - Engine Fuel and Emission Control System (Pages 2-20)

---

## 1. Generalites - System Overview

### Safety Warning

Due to the high pressure reached by the fuel (1350 bar), it is dangerous to handle the high pressure pipe outlets when the engine is running or there is pressure in the hydraulic accumulator (Rail).

---

## 1.1 Main Characteristics

The fuel injection system features the following advanced characteristics:

- **High Injection Pressure (1350 bar)** - Availability for superior atomization
- **Pressure Modulation** - Possibility of modulating pressure between 150 bar and the maximum 1350 bar, independently of the rotation speed and the engine load
- **High Regimes Capability** - Acting capacity up to 6000 rpm
- **Injection Pressure Control** - Before and during the injection
- **Fuel Consumption Reduction** - Optimized combustion
- **Emissions Reduction** - Lower pollutant output
- **Anti-Chattering** - Smoother combustion sound
- **Fumes Control** - When accelerating
- **Maximum Regime Limit Control** - Engine speed limiter
- **Thermostat Control** - Cold start heating
- **Air-Conditioning Control** - Load compensation
- **Auxiliary Fuel Pump Control** - Primary stage pumping

### Electronic Control Features

- **Cylinder Balance** - Minimum rocker control
- **Advance Main Injection** - Pilot injection before main combustion
- **Closed Cycle Pressure Injection Control** - Precision fuel metering
- **Overfeeding Pressure Control** - Boost pressure regulation
- **Pre-Injection Capability** - Pilot injection for reduced noise and emissions

---

## 1.2 Main Functions

The main functions of the system are essentially the following:

- Fuel temperature control
- Engine coolant temperature control
- Quantity of injected fuel control
- Minimum regime control
- Fuel when pedal is released (cut-off) control
- Cylinder balance at minimum (rocker) control
- Anti-chattering
- Fumes when accelerating control
- Maximum regime limit control
- Thermostat control
- Air-conditioning (if fitted) control
- Auxiliary fuel pump control
- Cylinder position control
- Advance main injection and pilot control
- Closed cycle of pressure injection control
- Overfeeding pressure control

The systems allows a pre-injection (pilot injection before PMS) with the advantage of reducing by-products of pressure in the combustion chamber, reducing the sound level of combustion, typical of direct injection engines.

---

## 2. Fuel System

### 2.1 General Description

The fuel system for vehicles with common rail engines is made up of the following elements:

**Major Components:**

- **Fuel Tank** - Primary fuel storage with safety features
- **Profiler** - Positioned between the tank and the electric feed pump to filter large particles
- **Electric Feed Pump** - Moves the fuel from the tank to the high pressure fuel pump
- **Fuel Filter/Fuel Heater/Obstructed Fuel Sensor/Fuel Temperature Sensor/Fuel Heater Control/Water in Fuel Sensor** - Comprehensive fuel treatment and monitoring unit
- **High Pressure Fuel Pump** - Capable of supplying fuel to the electroinjectors at a maximum pressure of 1350 bar
- **Hydraulic Accumulator (Rail)** - Incorporates a pressure sensor
- **Four Fuel Electro-Injectors** - Direct cylinder injection components
- **Electro-Valve** - Controls the rate of fuel to the thermostarter in the pre/post heating of air admitted when the coolant temperature, air admitted or fuel is below 0 °C
- **Thermostarter Spark Plug** - Attached at the intake manifold which carries out pre/post heating when the ignition is on and the coolant temperature, air admitted or fuel is below 0 °C

---

## 2.2 Fuel System Operation

### Fuel Pressure Regulation

- **Piston Pump** - Supplies the fuel at a regular pressure equivalent to that of the injection (up to 1350 bar)
- **Two-Way Electro-Valve** - Takes from the pump supply, the appropriate amount of fuel to regulate the desired pressure value
- **Pressurized Fuel Accumulator (Collector/Rail)** - Contains the pressure oscillations (ripple)
- **Electro-Injectors** - Fed by the rail and their working is determined by the stimulation of a rapid electromagnetic operator (integrated in the body of each electroinjector) opening an aperture which causes a pressure difference. This difference allows the opening of the injector end producing the spray

### Electronic Control Unit (ECU) Functions

The electronic control unit, in which the control and power units for the electroinjector piloting are integrated, is prepared for the control of the entire injection system. Some sensors, connected to the control board, can determine the state of the engine and the injection system at every moment as well as the demand for power by the driver.

**Key Control Functions:**
- Piston pump control through a regulating valve
- Fuel pressure maintenance
- Injector timing and duration control
- Load and rpm based adjustments
- Temperature compensation

### System Safety Features

**Pressure Relief:**
- Hydraulic accumulator (Rail) includes integral pressure relief
- System pressure limited to safe operating levels
- Excess pressure automatically diverted

---

## 2.3 High Pressure Electronic Injection System Functional Diagram

**System Components and Their Relationships:**

1. **Engine Speed Sensor** (RPM monitoring)
2. **Battery** (Power supply)
3. **Thermostarter Spark Plug** (Cold start heating)
4. **Electronic Control Unit** (Main controller)
5. **Crankshaft Speed Sensor** (Timing reference)
6. **Electro-Injectors** (Fuel delivery)
7. **Hydraulic Accumulator (Rail)** (Pressure storage)
8. **Fuel Pressure Sensor** (Pressure monitoring)
9. **Electro-Magnetic Fan** (Thermal management)
10. **Hydraulic Accumulator (Rail) Fuel Pressure Sensor** (Redundant pressure sensing)
11. **Air-Conditioning Compressor** (if fitted)
12. **High Pressure Pump** (Primary pressurization)
13. **3rd Piston Deactivator Valve** (Cylinder deactivation)
14. **Fuel Pressure Regulator** (Pressure control valve)
15. **Fuel Filter** (Fuel treatment)
16. **Fuel Heater** (Thermal management)
17. **Fuel Temperature Sensor** (Temperature monitoring)
18. **Electric Feed Pump** (Low pressure supply)
19. **Fuel Prefilter** (Tank-mounted filter)
20. **Fuel Tank** (Fuel storage)
21. **Electronic Control Unit** (Redundant shown)
22. **Multiple Connector** (5-way connector)
23. **Hydraulic Accumulator (Rail) Fuel Pressure Limiter** (Overpressure protection)
24. **Clutch Pedal Sensor** (Load input)
25. **Brake Pedal Sensor** (Load input)
26. **Brake Pedal Sensor** (Load input)
27. **Thermostarter Warning Light** (Cold start indicator)
28. **Speedometer** (Vehicle speed)
29. **Rev Counter** (RPM gauge)
30. **Admission Collector Air Pressure and Temperature Sensor** (Intake monitoring)

---

## 2.4 Electric Feed Pump

### 2.4.1 Generalites

- **Type**: Rotary pump with integrated by-pass, fitted in the aspiration line on the rear left side of the read body
- **Motor Type**: Fuel electro-pump is roller volumetric, with brush motor and stimulation by permanent magnets
- **Operation**: The rotor wheel pulled by the engine creates volumes which move from the aspiration opening to the delivery opening
- **Roller Function**: Volumes are delimited by the rollers which become attached to the exterior ring during engine rotation
- **Valve System**: The pump has two valves:
  - First: a no-return valve to avoid the emptying of fuel from the system (with the pump stopped)
  - Second: a pressure valve which communicates the delivery with aspiration when pressures superior to 5 bar occur

### 2.4.2 Characteristics

| Specification | Value |
|---|---|
| Delivery Pressure | 2.5 bar |
| Flow | > 155 l/h |
| Supply Voltage | 13.5 V x 5A |
| Reel Resistance at 20 °C | 28.5 Ohm |

---

## 2.5 Fuel Filter

### Generalites

The main fuel filter is formed by:
- **Bracket [1]** - Filter housing structure
- **Filter Element [3]** - Main filtration media between bracket and fuel heater [2]
- **Fuel Heater [2]** - Integrated heating element
- **Clogged Filter Sensor [5]** - Blockage detection
- **Fuel Temperature Sensor** - Temperature monitoring
- **Fuel Heater Control [6]** - Heating control circuit
- **Water-in-Fuel Sensor [4]** - Water contamination detection

### Characteristics

- **Filter Grade**: 5 micras
- **Internal Working Pressure**: 0.6 bar

---

## 2.5.1 Fuel Temperature Sensor

**Location:** Integrated in the fuel filter [1]

**Temperature Control Function:**
When the fuel temperature is excessive (external atmospheric temperature, engine at full load and tank on reserve), the correct lubrication of the high pressure pump cannot be guaranteed.

When fuel temperature is over 75 °C:
- Control unit orders pressure regulator to reduce pressure level (not injection time)
- If the temperature goes above 90 °C, power is reduced to 60%

**Sensor Characteristics:**
- Type: NTC (Negative Temperature Coefficient) sensor
- Resistance values by temperature:

| Temperature | Resistance |
|---|---|
| -40 °C | 43.30 kOhm |
| -20 °C | 15.46 kOhm |
| 0 °C | 5.89 kOhm |
| 20 °C | 2.50 kOhm |
| 40 °C | 1.17 kOhm |
| 60 °C | 0.59 kOhm |
| 80 °C | 0.32 kOhm |
| 100 °C | 0.19 kOhm |
| 120 °C | 0.11 kOhm |

**Sensor Function:**
The control unit, using the values received, determines fuel the density and volume. Correcting the delivery and limiting the engine performance.

---

## 2.5.2 Fuel Heater in Filter

**Function**: Heating fuel to ensure proper viscosity and lubrication of high pressure pump components

**Control**: Thermostarter electro-valve regulates fuel flow and heating based on:
- Coolant temperature
- Air intake temperature
- Fuel temperature
- Threshold: Below 0 °C activation

---

## Common Rail Electronic Injection System Components

### 1.3 System Components with Diagram

**Engine Control System Integration:**

**Sensor Inputs:**
1. Engine Speed Sensor - RPM and position
2. Crankshaft Speed Sensor - Timing reference
3. Camshaft Speed Sensor - Valve timing
4. Coolant Temperature Sensor - Thermal state
5. Air Intake Temperature Sensor - Combustion control
6. Fuel Temperature Sensor - Fuel condition
7. Pressure Sensors - Fuel rail and boost pressure
8. Position Sensors - Accelerator and brake pedals
9. Clutch Pedal Sensor - Load state
10. Speedometer - Vehicle speed

**Actuator Outputs:**
- Fuel Injectors (4x) - Precision fuel spray control
- Fuel Pump - Low pressure supply
- Pressure Regulator - Rail pressure maintenance
- Thermostarter - Glow plug for cold start
- Electromagnetic Fan - Thermal management
- Various Control Valves - System optimization

**Safety Monitoring:**
- Fuel Pressure Limiter - Overpressure protection
- Filter Blockage Detection - Service indicator
- Water in Fuel Detection - Contamination alarm
- Fault Code Generation - Diagnostic capability

---

## 3. Fuel Injection Specifications

### High Pressure Pump Characteristics

| Specification | Value |
|---|---|
| Maximum Injection Pressure | 1350 bar |
| Minimum Safe Pressure | 150 bar |
| Operating Pressure Range | 150-1350 bar |
| Pressure Control | Electronic, independent of RPM and load |

### Fuel Injector Specifications

| Specification | Value |
|---|---|
| Type | Electro-magnetic solenoid |
| Quantity | 4 (one per cylinder) |
| Actuation | Rapid electromagnetic operator |
| Response Time | < 1 millisecond |
| Spray Pattern | Multi-hole precision spray |
| Fuel Atomization | Ultra-fine mist for complete combustion |

### Hydraulic Accumulator (Rail) Specifications

| Specification | Value |
|---|---|
| Function | Pressure ripple absorption and storage |
| Integral Components | Pressure sensor and relief valve |
| Material | Steel, high-pressure rated |
| Pressure Capacity | Up to 1400 bar |

---

## 4. System Troubleshooting

### Common Fuel System Issues

| Symptom | Possible Cause | Diagnostic Action |
|---|---|---|
| Hard Start (Cold) | Thermostarter malfunction, fuel heater issue | Test glow plug, check fuel temperature sensor |
| Rough Idle | Fuel pressure low, injector fault, sensor issue | Check rail pressure, perform injector test |
| Black Smoke | Over-fueling, injection timing error | Check fuel temperature, verify ECU parameters |
| White Smoke | Incomplete combustion, cold engine operation | Allow warm-up period, check thermostarter |
| Loss of Power | Low fuel pressure, clogged filter, pump failure | Check fuel filter, measure rail pressure |
| High Fuel Consumption | Pressure regulator fault, injector leak | Verify regulator operation, test injector spray |
| Check Engine Light | Sensor malfunction, pressure out of range | Scan for fault codes, test affected sensor |
| Excessive Noise | Fuel pressure too high, injector rattle | Check pressure limiter, verify regulator |

---

## 5. Fuel System Safety and Service

### High Pressure Safety

**Critical Safety Points:**
1. Never work on high-pressure fuel system while engine is running
2. Pressure remains even after engine shutdown
3. Always depressurize system before service
4. Use only fuel-rated containers and equipment
5. Never assume system is "safe" to work on

### Fuel Quality Requirements

- **Type**: Diesel fuel meeting EN590 or equivalent standard
- **Viscosity**: Properly winterized for ambient temperature
- **Contamination**: Must be free of water and particulates
- **Cetane Number**: Minimum 45 (recommended 50+)

### Filter Service

| Service Item | Interval |
|---|---|
| Fuel Filter Element Inspection | Every fuel change |
| Fuel Filter Element Replacement | When blockage sensor indicates or per maintenance |
| Water Removal (if detected) | Immediate |
| System Flush (if heavily contaminated) | As needed |

### Emission Control Strategy

**Iveco Common Rail System Euro III Emissions Compliance:**

1. **Pre-Injection (Pilot Injection)** - Reduces combustion pressure rise
2. **Flexible Timing** - Optimizes combustion process
3. **Precise Fuel Metering** - Eliminates excess fuel
4. **Exhaust Gas Recirculation (EGR)** - Reduces NOx emissions
5. **Particulate Control** - Fine fuel atomization reduces solid particulates
6. **Temperature Monitoring** - Ensures optimal combustion conditions

---

## 6. Specialized Tools and Equipment

### Fuel System Service Tools (Partial List from Manual)

| Tool Reference | Function |
|---|---|
| 790965 | Auxiliary organs group pulley and engine flywheel positioner |
| 790966 | Dial gauge holder tool for overheating injection pump |
| 790967 | Dial gauge 0-5 mm |
| 790968 | Front oil seal installer |
| 790969 | Handler for tappet |
| 790970 | Spanner for rotating camshaft (cylinder head removed) |
| 790971 | Springs pusher to substitute valve set regulating plates |
| 790972 | Tool for removal, installation and applying tightening torque at oil filter |
| 790973 | Auxiliary organs group repairing support |
| 790974 | Tool set to check resistance to rotation of drive axle oil pump |
| 790975 | Engine handling device for removal and installation |
| 790976 | Locking tool for engine flywheel to apply tightening torques |
| 790977 | Special spanner (13 mm) for removal and installation of injection pump lower nut |
| 790978 | Connecting rods assignments tester |
| 790989 | Engine coupling to work bench bridles |
| 790990 | Engine repairing bench |
| 790991 | Injection pump gub remover |
| 790992 | Injection pump hub positioner (mechanical injection engine) |
| 791037 | Injection pump hub positioner (common rail engine) |
| 790993 | Fuel injection pipes remover |

---

## 7. Cold Start and Thermostarter System

### Thermostarter Function

**Components:**
- Thermostarter spark plug at intake manifold
- Electro-valve controlling fuel flow to heater
- Electronic control of heating duration

**Cold Start Operation (Fuel or Air < 0 °C):**
1. Driver turns ignition key ON
2. ECU detects low fuel/air/coolant temperature
3. Electro-valve opens to route fuel through heater
4. Thermostarter plug energizes and heats incoming charge
5. Heating continues for calibrated duration
6. Fuel is pre-heated and air charge is warmed
7. Engine start improves, white smoke reduces

**Characteristics:**
- Heating activates only when necessary
- Duration varies with temperature
- Automatic cutoff prevents waste
- Indicator light warns of glow plug operation

---

## 8. Emission Control and Euro III Compliance

The Iveco 8140.43P Euro III engine meets stringent European emission standards through:

1. **Advanced Fuel Injection** - Precise combustion control
2. **Electronic Monitoring** - Real-time emissions optimization
3. **Temperature Management** - Optimal combustion window
4. **Pressure Control** - Efficient fuel utilization
5. **Pilot Injection** - Noise and emissions reduction
6. **EGR Systems** - NOx reduction strategy

This training manual provides the foundation for proper diagnosis, maintenance, and service of the Santana PS10 fuel and emissions control systems.

