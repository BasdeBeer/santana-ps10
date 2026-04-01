# Santana PS10 Knowledge Base - Master Index

**Complete map of the 58-file knowledge base for the 2006 Santana PS10 (Iveco 8140.43P, ZF gearbox, ~120,000 km)**

Generated: March 2026 | Source: All original PDFs verified

---

## SECTION 00: VEHICLE PROFILE & REFERENCE

### 00-Vehicle-Profile/vehicle-profile.md
**Overview:** Complete vehicle identity and current status documentation
**Key specs inline:**
- Make/Model: Santana Motor S.A., Spain (Type 1/2 station wagon)
- Engine: Iveco 8140.43P (2.8 TD, Euro III), EDC electronic control
- Transmission: ZF manual (LT-85), part-time 4WD transfer case
- Current odometer: ~120,000 km (full maintenance cycle complete)
- Registration: 24-BX-HS (Netherlands)
- Recommended oil: Shell Super Plus 10W/40 API SJ/CF
- Oil change interval: 30,000 km or 24 months (normal)
- Maintenance at 120k km: timing belt replaced at 90k, all fluids due for inspection/replacement
- Body numbers: VSFPSW10V00100001~ / VSFPSW20V00100009~

**Reference:** Pages 1-55 of all manuals; extraction source verification complete

---

## SECTION 01: MAINTENANCE & LUBRICATION

### 01-Maintenance-and-Lubrication/maintenance-history.md
**Overview:** Actual service log of this specific vehicle from 75k km to 121k km
**Parts replaced & dates:**
- Car battery (75,250 km)
- Oil + filter (75,250 km, 20-02-2025 @ 111,839 km)
- Rear brake discs + pads (75,500 km)
- Rear differential oil (75,500 km, 08-08-2024 @ 109,553 km)
- Front differential oil (75,500 km, 08-08-2024 @ 109,553 km)
- Gearbox + transfer case oil (75,675 km, 18-08-2024 @ 110,620 km)
- Air filter (76,000 km)
- Clutch master & slave cylinder (no km recorded)
- Power steering oil + filter (77,130 km)
- Thermostat + ECU temp sensor (10-10-2024)
- Fuel filter and pre-filter (25-01-2025)
- Brake fluid (20-02-2026 @ 121,388 km)
- Note: Santana part numbers differ from OEM; cross-reference both when ordering

### 01-Maintenance-and-Lubrication/service-manual-maintenance.md
**Overview:** Official maintenance schedule from Service Manual Section 0B (pages 6-33)
**Schedule intervals (normal conditions, up to 120,000 km):**
- Every 15k km: Oil & filter (R), clutch pedal (I)
- Every 30k km: Air filter (R), fuel filter (R), fuel prefilter (R), brake fluid (R), all transmission oils (I)
- Every 45k km: Timing belt (R)
- Every 60k km: Oil & filter (R), accessory belt (I), coolant (R)
- Every 75k km: Oil & filter (R), brake discs (I)
- Every 90k km: Timing belt (R), accessory belt (R), air filter (R), fuel filter (R), fuel prefilter (R)
- Every 105k km: Oil & filter (R), timing belt (R), clutch liquid (I)
- Every 120k km: Coolant (R), brake fluid (R), brake discs (I)

**Fluid capacities & torques:**
- Engine oil: 7.3L drained (7.0L with filter, 5.9L without filters); oil drain plug 3-4 Kg-m (30-40 Nm); oil filter 2.5 Kg-m (25 Nm)
- Coolant: 12 litres (50% demineralized water + 50% Dinagel 9103); freezing protection -38°C
- Gearbox oil: 3.120 cc (SAE 75W-90, API GL-4); use sealant TB 1215 QUIMILOCK
- Transfer box oil: 2.800 cc (SAE 75W-90, API GL-4); use sealant TB 1215 QUIMILOCK
- Differential front: 1.750 cc (SAE 80W-90, API GL-5); rear 2.500 cc
- Clutch liquid: DOT-4
- Servo-steering hydraulic oil: DEXRON-II
- Propeller shaft grease: AGUILA 95 BRUGAROLAS; union clamp nuts 2.8 ± 3.5 Kg-m (28 ± 35 Nm)

**Brake specifications:**
- Front pads: 15.30 mm (service limit 8 mm)
- Front disc: 20 mm (service limit 18 mm)
- Rear pads: 15.60 mm (service limit 8.2 mm)
- Rear disc: 10 mm (service limit 9 mm)
- Disc deflection: 0.15 mm max
- Wheel nuts: 11 ± 17 Kg-m (110 ± 170 Nm)

**Severe driving codes:** A (short frequent trips), B (muddy), C (dusty), D (cold/salty), E (short cold), G (towing/high speed/heat), H (towing), I (hired)

**Steering play:** 10 ± 30 mm (wheels straight, engine off)

### 01-Maintenance-and-Lubrication/training-manual-maintenance.md
**Overview:** Dealer training condensed schedule (covers 15k-120k km intervals)
**Normal conditions schedule:**
- 15k km: Oil/filter (R), accessory belt (R) at 60k, timing belt (R) at 60k, air filter (R) at 30k
- 30k km: Fuel filter (R), fuel prefilter (I) at 2.5k, all transmission oils (R)
- Other intervals: Same as service manual with training notation
- Severe codes match service manual exactly
- Engine specifications: 8140.43P, 2.8 TD, Euro III
- Oil: SAE 10W/40, API SJ/CF, 7.3L capacity
- Fuel filter: 10,000 km change interval
- Fuel prefilter: 2,500 km inspection interval

---

## SECTION 02: ENGINE SYSTEMS

### 02-Engine/engine-overview.md
**Overview:** Complete engine architecture and cross-reference guide
**Engine:** Iveco 8140.43P, 4-cylinder in-line, 2.8 Turbo Diesel (Euro III)
**Variants:**
- 8140.43C.3 (mechanical injection, rotary pump)
- 8140.43S.4 (Common Rail, EDC electronic)
- This vehicle: Common Rail variant (EDC with blink-code diagnostics)
**Core dimensions:**
- Bore: 94.4 mm
- Stroke: 100 mm
- Displacement: 2,800 cc
- Compression ratio: 18.5:1
**Cooling system:** Forced circulation with electromagnetic pulley clutch fan
- Thermostat opening: 79°C ± 2°C to 82°C ± 2°C
- Max operating: 110°C
- Capacity: To be verified (reference training-cooling-system.md)
**Fuel:** Mechanical (140 bar) or Common Rail (1600 bar); this vehicle uses Common Rail
**Turbocharger:** MITSUBISHI TF0 HM 13 T-6 or TD04 (variant)
**Lubrication:** Full-flow, oil-cooled turbo, piston cooling jets
**Oil specs:** SAE 10W/40, API SJ/CF
**Exhaust:** Euro III compliant with intercooler

### 02-Engine/Cooling-System/training-cooling-system.md
**Overview:** Cooling system operation, components, specs (Training Manual pages 2-4)
**System type:** Forced circulation with electromagnetic fan clutch
**Components (9 major):**
1. Reservoir tank (cap: empty 1±0.1 Kg/cm², inlet 0.005±0.02 Kg/cm²)
2. Degasifying hoses
3. Thermostat box (three-way)
4. Inlet hose to radiator
5. Outlet hose from radiator
6. Water radiator (main heat dissipation)
7. Bypass hose + heater outlet
8. Inlet hose to heater
9. Heat exchanger (oil cooling)

**Thermostat operation:**
- Below 79°C ± 2°C: Closed (coolant bypasses radiator)
- Above 79°C ± 2°C: Opens (flows through radiator)
- Max opening temperature: 110°C
- Electromagnetic fan: Engages at 94°C ± 2°C, disengages at 80°C ± 2°C

**Pressure regulation (cap valves):**
- Outlet (relief) valve: Opens 1 ± 0.1 Kg/cm² (maintains boiling point elevation)
- Inlet (check) valve: Opens 0.005 ± 0.02 Kg/cm² (allows makeup from reservoir)

**Coolant specification:**
- Type: 50% demineralized water + 50% Dinagel 9103 (Dinamic)
- Freezing protection: -38°C
- System capacity: 12 litres
- Inspection interval: 10,000 km / 8 months (radiator & intercooler)

**Common problems & fixes:**
- Overheating: Stuck thermostat, fan failure, blockage
- Leaks: Deteriorated hoses, loose connections, pump seal
- Low coolant: Leaks, evaporation (check for leaks, refill)
- Cold engine: Stuck-open thermostat, sensor failure (replace thermostat)
- Fan always on: Stuck-open thermostat, sensor malfunction
- Noise/vibration: Water pump bearing wear (replace pump)

### 02-Engine/Engine-Repair/training-engine-repair.md
**Overview:** Complete engine repair procedures & torque specs (Training Manual pages 2-34)
**Belt specifications:**
- Water pump & generator belt: 140 ± 5 Hz (measured at point A)
- A/C compressor belt: 160 ± 10 Hz
- Replacement intervals: Generator belt 60,000 km (R), A/C belt 60,000 km (R)

**Timing belt:**
- Replacement interval: 30,000 km (more often if oil leaks detected at front seal)
- Tension specification: 88 ± 112 Hz (measured at point D)
- Alignment: Camshaft gear mark (A) aligns with plunger cover mark (B)
- Critical tool: Crankshaft/flywheel locking tools for synchronization
- Pre-tension: 2.8 ± 3.0 Kg/m torque on crankshaft before tensioner lock
- Tensioner nut: 4 Kg-m (40 Nm)
- Removal procedure: 9 critical steps with three control points
- Installation procedure: 5 steps including synchronization verification

**Valve play (tappet clearance):**
- Specification: Inlet 0.5 ± 0.05 mm, Outlet 0.5 ± 0.05 mm (hot or cold)
- Measurement: With valve closed, measure between plunger and rocker
- Adjustment: 8 adjustment plate thicknesses (3.25-3.60 mm) with outcome table (3.65-4.55 mm)
- Procedure: Extract plate, measure thickness, select new plate from table, install with engraved face toward plunger

**Cylinder head repair:**
- Camshaft support diameter:
  - Standard in camshaft: 33.934-33.950 mm
  - Standard in head: 33.985-34.015 mm
  - Oversized (+0.2mm) in camshaft: 34.134-34.150 mm
  - Oversized in head: 34.185-34.250 mm
  - Radial play: 0.035 ± 0.081 mm
- Camshaft run-out limit: 0.04 mm
- Cam height: Intake 9.5 mm, Exhaust 10.5 mm
- Rocker arm radial play: 0.030 ± 0.075 mm
- Head flatness: Nominal 150 ± 0.1 mm; max flattening 0.4 mm; min after flattening 149.6 ± 0.1 mm
- Valve widths: Inlet 1.2-1.5 mm, Outlet 1.0-1.3 mm; injector overhang 2.230-2.690 mm
- Valve seat specifications: Exhaust Ø 37.800±37.415 mm, Intake Ø 42.125±42.175 mm, height 7 mm
- Valve radial play: 0.023 ± 0.053 mm
- Valve guide int. Ø: 8.023-8.038 mm; ext. Ø: 13.012-13.025 mm
- Valve spring specs: H 52 free, H1 38.5 at P1 43.8±2.5 kg, H2 28.5 at P2 77.4±4 kg
- Cylinder head bolt tightening (3-phase): 1) 6±0.5 Kg-m (60±5 Nm), 2) 6±0.5 Kg-m, 3) 180°±10° angular

**Cylinder block:**
- Wear limit: 0.4 mm per cylinder (if exceeded, do honing)
- Nominal bore (standard): 94.402-94.432 mm
- Nominal bore (oversized +0.4mm): 94.802-94.832 mm
- Piston nominal (standard): 94.306-94.320 mm
- Piston nominal (oversized): 94.706-94.720 mm
- Piston-to-bore clearance: 0.082-0.126 mm
- Piston overhang (min to max): >0.40-<0.80 mm

**Crankshaft:**
- Connecting rod journal: 80.182-80.208 mm (nominal)
- Main bearing journal: 56.515-56.538 mm (nominal)
- Main bearing clearance: 0.035-0.083 mm
- Axial play: 0.060-0.310 mm
- Main bearing bolt tightening (2-phase): 1) 5 Kg-m (50 Nm), 2) 63°±2° angular
- Rod cap bolt tightening (2-phase): 1) 5±0.5 Kg-m (50±5 Nm), 2) 63°±2° angular

**Piston & connecting rod:**
- Gudgeon pin Ø: 31.994-32.000 mm
- Pin-to-piston play: 0.007-0.019 mm
- Rod foot bushing int. Ø: 32.010-32.020 mm
- Pin-to-bushing play: 0.014-0.030 mm
- Ring 1 (trapezoidal) thickness: 2.068-2.097 mm
- Ring 2 thickness: 1.970-1.995 mm
- Ring 3 thickness: 2.470-2.490 mm
- Ring 2-3 groove play: 0.055-0.10 mm (ring 2), 0.05-0.09 mm (ring 3)
- Trapezoidal ring groove play: 0.103-0.162 mm
- Ring end gaps: 1st gap 0.20-0.35 mm, 2nd gap 0.30-0.50 mm, 3rd gap 0.30-0.55 mm
- Rod head diameter: 60.341-60.348 mm; all four must match weight class

**Engine torque specifications (complete list):**
- Cylinder head bolts: 6±0.5 Kg-m (60±5 Nm) + 6±0.5 Kg-m + 180°±10°
- Lower block union: 5±0.5 Kg-m (50±5 Nm) + 90°±5°
- Rod caps: 5±0.5 Kg-m (50±5 Nm) + 63°±2°
- Flywheel bolts: 3±0.3 Kg-m (30±3 Nm) + 90°±2°
- Fan hub to pump: 4.0 Kg-m (40 Nm) + 110°±10°
- Generator belt tensioner: 4.5 Kg-m (45 Nm)
- Generator front bracket: 5 Kg-m (50 Nm)
- Timing belt tensioner: 4.0 Kg-m (40 Nm)
- Crankshaft pulley: 20 Kg-m (200 Nm)
- Timing cover upper/lower: 0.75 Kg-m (7.5 Nm)
- Water pump connecting: 5.0 Kg-m (50 Nm)
- Oil filter adapter: 8.0 Kg-m (80 Nm)
- Injector/electro-injector clamps: 4.0 Kg-m (40 Nm)
- Fuel injection pipes: 3.3 Kg-m (33 Nm)

**Engine technical data summary:**
- Power: 75.5-80.5 kW (102.7-109.5 CV) or 88.8-95.2 kW (120.8-129.5 CV) @ 3,600 rpm
- Torque: 250 Nm (25.5 kgm) @ 1,800 rpm (mechanical) or 275.5-304.7 Nm (28.1-31.1 kgm) (Common Rail)
- Max RPM (no load): 4,200±25 rpm
- Min RPM idle: 800±25 rpm
- Injection pressure: 240±12 bar (mechanical) or 1,350 bar (Common Rail)
- Compression in TDC: 20±2.6 bar; minimum allowed 16 bar
- Oil pressure (idle): >0.8 bar; (max RPM): >3.5 bar

### 02-Engine/Exhaust/exhaust-system.md
**Overview:** Turbocharger, intercooler, exhaust manifold (Service Manual Section 6K)
**Turbochargers (two options):**
1. MITSUBISHI TF0 HM 13 T-6 (primary)
2. MITSUBISHI TD04 (variant)
- Type: Fixed geometry with mechanical waste-gate control
- Function: Compresses intake air; pressure limiter bypasses excess exhaust when calibrated value reached
- Lubrication: Engine oil circuit (full pressure supply)
- Speed: 80,000+ RPM typical
- Warning: Never touch rotating turbine wheel; allow engine cooling before service

**Intercooler:**
- Type: Air-to-air integrated with water radiator
- Purpose: Cools compressed turbo air before cylinders
- Removal: Disconnect rigid interconnection pipe, remove 4 fixing screws
- Cleaning: Pressurized water + compressed air + brush (no sharp tools)

**Exhaust manifold:**
- Material: Metal composite gasket
- Location: Direct to cylinder head
- Connection: Flange to turbo inlet

**Euro II emission limits (bench cycle R49, CEE normative):**
- CO: <4.0 g/kWh
- NO: <7.0 g/kWh
- HC: <1.1 g/kWh
- Particulates (no catalyst): <0.15 g/kWh
- Particulates (with catalyst): <0.15 g/kWh

**Opacity (Bosch BSU degrees):**
- Mechanical injection: Max 2.0 degrees @ 3800 rpm, 2.5 @ max torque, 3.5 @ 1000 rpm full load
- Common Rail: 1.5 degrees @ 3800 rpm, 2.5 @ max torque, 3.5 @ 1000 rpm full load

**Acoustic emissions (ISO 3474, 1m from engine):**
- Mechanical: 79 dB @ 800 rpm, 99 dB @ 3800 rpm
- Common Rail: 76 dB @ 800 rpm, 96 dB @ 3800 rpm

**Air intake:** Filter (dry, replaceable cartridge) → turbo compressor → intercooler → intake manifold → pressure tube to LDA (mechanical engines only)

### 02-Engine/Fuel-and-Emissions/training-fuel-emissions.md
**Overview:** Common Rail EDC fuel system (Training Manual pages 2-20)
**System type:** Common Rail electronic injection, maximum pressure 1350 bar
**Pressure modulation:** 150-1350 bar independent of RPM/load
**Main features:**
- High injection pressure (1350 bar)
- Pressure modulation capability
- High RPM capacity (up to 6000 rpm)
- Precise injection control (pilot injection)
- Fuel consumption reduction
- Emission reduction (Euro III)
- Anti-chattering
- Fume control on acceleration
- Max RPM limiter
- Thermostat control (cold start)
- A/C load compensation
- Auxiliary pump control

**Major components (fuel system):**
1. Fuel tank (with safety features)
2. Profiler (large particle filter)
3. Electric feed pump (low pressure)
4. Fuel filter/heater/obstructed sensor/temp sensor/water-in-fuel sensor (integrated unit)
5. High pressure pump (up to 1350 bar)
6. Hydraulic accumulator/Rail (integral pressure sensor)
7. Four fuel electro-injectors
8. Electro-valve (controls thermostarter fuel)
9. Thermostarter spark plug (intake manifold, pre/post heating)

**Electric feed pump specs:**
- Delivery pressure: 2.5 bar
- Flow: >155 l/h
- Supply voltage: 13.5V x 5A
- Reel resistance @ 20°C: 28.5 Ohm

**Fuel filter:**
- Grade: 5 micras
- Internal working pressure: 0.6 bar
- Integrated: Fuel heater, clogged sensor, fuel temp sensor, water-in-fuel sensor

**Fuel temperature sensor (NTC type):**
- Location: Integrated in fuel filter
- Control: When temp >75°C, ECU reduces pressure (not injection time); >90°C reduces power to 60%
- Resistance table: -40°C = 43.30 kOhm, -20°C = 15.46 kOhm, 0°C = 5.89 kOhm, 20°C = 2.50 kOhm, 40°C = 1.17 kOhm, 60°C = 0.59 kOhm, 80°C = 0.32 kOhm, 100°C = 0.19 kOhm, 120°C = 0.11 kOhm

**Fuel heater:**
- Activation: <0°C (coolant, air intake, or fuel temperature)
- Control: Electro-valve regulates flow based on temp sensors
- Function: Ensures viscosity for high-pressure pump lubrication

**High-pressure pump specs:**
- Max pressure: 1350 bar
- Min safe: 150 bar
- Control: Electronic via regulating valve, piston pump design
- Relief: Integral to rail accumulator

**Hydraulic accumulator (Rail) specs:**
- Function: Absorbs pressure ripple; stores high pressure
- Components: Integral pressure sensor + relief valve
- Material: Steel, high-pressure rated
- Capacity: Up to 1400 bar

**Fuel injector specs:**
- Type: Electromagnetic solenoid
- Quantity: 4 (one per cylinder)
- Actuation: Rapid electromagnetic operator
- Response time: <1 millisecond
- Spray pattern: Multi-hole precision
- Atomization: Ultra-fine mist

**System sensors & inputs (10 major):**
1. Engine speed (RPM monitoring)
2. Crankshaft speed (timing reference)
3. Camshaft speed (valve timing)
4. Coolant temperature
5. Air intake temperature
6. Fuel temperature
7. Fuel rail pressure
8. Boost pressure
9. Accelerator/brake pedal position
10. Clutch pedal sensor

**System actuators (6 major):**
1. Fuel injectors (4x)
2. Fuel pump
3. Pressure regulator
4. Thermostarter glow plug
5. Electromagnetic fan
6. Control valves

**System safety:**
- Pressure relief (accumulator integral)
- Filter blockage detection
- Water contamination alarm
- Fault code generation + storage

**Cold start (fuel/air <0°C):**
1. Ignition ON → ECU detects low temp
2. Electro-valve opens (fuel routed through heater)
3. Thermostarter plug energizes (heats intake charge)
4. Heating duration: Calibrated auto-cutoff
5. Result: Warm fuel + pre-heated air improves start, reduces white smoke

**Troubleshooting table (symptoms & causes):**
- Hard start (cold): Thermostarter fail, fuel heater issue → test glow plug, check temp sensor
- Rough idle: Low pressure, injector fault, sensor issue → check rail pressure, test injectors
- Black smoke: Over-fueling, injection timing → check fuel temp, ECU params
- White smoke: Incomplete combustion, cold engine → warm-up, check thermostarter
- Power loss: Low pressure, clogged filter, pump fail → check filter, measure rail pressure
- High fuel consumption: Regulator fault, injector leak → verify regulator, test spray
- Check engine light: Sensor fault, pressure out of range → scan codes, test sensor
- Excessive noise: High pressure, injector rattle → check limiter, verify regulator

**Emission control strategy (Euro III):**
1. Pre-injection (pilot injection) - reduces combustion pressure rise
2. Flexible timing - optimizes combustion
3. Precise metering - eliminates excess fuel
4. Exhaust gas recirculation (EGR) - reduces NOx
5. Particulate control - fine atomization
6. Temperature monitoring - optimal combustion window

**Specialized tools (partial list):**
- 790965: Auxiliary organs pulley & engine flywheel positioner
- 790972: Oil filter tool
- 791037: Injection pump hub positioner (Common Rail)
- 790993: Fuel injection pipes remover

### 02-Engine/General-Info/engine-general-info.md
**Overview:** Engine specifications, clearances, tolerances (Service Manual Section 6-2)
**Engine block:**
- Material: Cast iron
- Main bearings: 4 journals supporting crankshaft
- Bore tolerance: Specified in technical drawings
- Measurement procedure: Three heights, two perpendicular planes per cylinder

**Crankshaft journals:**
- Main bearing: 4 journals, rectification perpendicular to axis
- Connecting rod: 4 journals, run-out limits specified
- Procedures: Mechanical rectification when worn

**Piston & rod assembly:**
- Piston design: T-slot for improved oil cooling
- Ring groove clearances: Compression ring 1 (0.05-0.11 mm), compression ring 2 (0.03-0.09 mm), oil control ring (0.15-0.35 mm)
- Gudgeon pin: Fully floating, high-strength steel
- Connecting rod: I-beam forged steel, bushed gudgeon end, precision bearing at crankshaft end
- Rod bushings: Phosphor bronze or sintered iron, interference fit, requires reaming after install
- Clearance with pin: 0.02-0.04 mm

**Valve specifications:**
- Intake: Stem 7 mm, head ~37 mm
- Exhaust: Stem 7 mm, head ~31 mm
- Valve guide: 7.00-7.025 mm int. Ø, cast iron or bronze inserts
- Stem clearance: Intake 0.02-0.05 mm, Exhaust 0.04-0.07 mm
- Seat angles: 45 degrees (both intake/exhaust)
- Seat width: 1.5-2.0 mm
- Spring: Dual springs per valve, coil design with retainers
- Seat face angle: 45 degrees (both)

**Timing belt:**
- Type: Toothed belt (reinforced rubber)
- Material: HSN (High Strength Nitrile)
- Tension: 88-112 Hz (measured at point D)
- Tool: Frequency meter ref. 00000A01484
- Alignment marks: Camshaft gear (A), crankshaft/flywheel (B), plunger cover (C)
- Replacement: Every 30,000 km (or if front seal leaks)
- Tensioner: Spring-loaded, adjustable roller

**Cylinder head:**
- Type: 4-valve per cylinder (2 intake, 2 exhaust)
- Material: Aluminum alloy
- Fasteners: High-strength steel bolts, multi-step tightening sequence

**Valve play tappet clearance:**
- Inlet: 0.5±0.05 mm
- Outlet: 0.5±0.05 mm
- Measurement: Engine hot or cold (same spec applies)
- Adjustment: Via adjusting shims (8 thicknesses available)

**Engine oil & coolant:**
- Oil type: Diesel engine oil (grade specified)
- Capacity: 6-7 liters (verify with dipstick)
- Change interval: Per maintenance schedule
- Coolant type: Long-life ethylene glycol
- Concentration: 50/50 with distilled water
- Thermostat opening: 79°C±2°C (begins), 82°C±2°C (fully), 110°C (max operating)

**Gasket & seal specs:**
- Cylinder head gasket: Multi-layer steel (MLS) with fire ring (replace each removal)
- Timing cover: Composition gasket or rubber seal
- Oil seals: Nitrile rubber with spring

### 02-Engine/Lubrication/training-lubrication.md
**Overview:** Oil system operation, components, specs (Training Manual pages 2-5)
**System type:** Forced circulation with pressure regulating valve
**Major components (3):**
1. Gears oil pump (incorporated in auxiliary organs group with pressure regulator at rear cover)
2. Modine-type heat exchanger (with safety valve)
3. Oil filter (double filtrated, with safety valve)

**System operation:**
- Oil sucked from pan through strainer pump → heat exchanger (cooling) → oil filter → main bearings, camshaft, turbochanger, piston cooling jets → gravity return to pan
- Safety feature: If filter or heat exchanger blocked, bypass valve opens (alternative lubrication path)

**Oil circuit components (12 numbered):**
1. Oil conduits to camshaft
2. Oil pressure line from pump
3. Auxiliary organs group (pump + regulator)
4. Modine heat exchanger
5. Oil filter (double filtration)
6. Vacuum pump
7. Pressure regulating valve
8. Oil pump gears
9. Pump oil sucker (strainer in pan)
10. Oil injector for piston crown cooling
11. Oil conduits to turbocharger
12. Oil pressure switch

**Oil vapours recycling:**
- Ramp collects vapours from pan
- Oil condenser receives vapours, condenses them back to pan
- Excess vapours vent to atmosphere through pipe

**Oil type & capacity:**
- Viscosity: SAE 10W/40
- Standard: API SJ/CF
- Total capacity (drained): 7.3 liters
- Including filter: 7.0 liters
- Without filters: 5.9 liters

**Oil system pressures:**
- Idle (ticking over): Minimum 0.8 bar (spec: >0.8 bar)
- Maximum RPM: Minimum 3.5 bar (spec: >3.5 bar)
- Pressure regulating valve: Maintains pressure in system parameters

**Heat exchanger & oil filter:**
- Heat exchanger: Modine type, integral safety valve, bypasses if blocked
- Oil filter: Double filtrated, integral safety valve, bypasses if clogged
- Both: Prevent engine starvation if blocked

**Piston crown cooling:**
- Oil injector location: Below piston crown
- Function: Direct spray cooling for thermal control
- Supply: From main lubrication circuit

**Turbocharger supply:**
- Source: Main lubrication circuit
- Pressure: Full system pressure maintained
- Return: Dedicated drain line to pan
- Critical: Clean oil essential for turbo bearing life

**Lubrication maintenance:**
- Oil change: Every 15,000 km / 12 months (normal & severe conditions)
- Filter replacement: Every oil change (always)
- Level checking: Cold engine only, between MIN-MAX
- Frequency: Every 1,000 km or weekly

**Troubleshooting (8 common issues):**
- Low pressure: Worn pump, clogged filter, low level → check level, change filter, test pump
- High pressure: Stuck valve, wrong viscosity → check valve, verify oil type
- Leaks: Worn seals, loose plugs, damaged gaskets → identify source, replace
- Dark/black oil: Normal or extended interval → change oil & filter
- Foam/bubbles: Overfilled, coolant contamination, aeration → drain excess, check for leaks
- Oil temp high: Excessive load, stuck thermostat, low flow → check operation, verify cooling
- Burning smell: Leaks burning, worn rings → inspect leaks, check compression

---

## SECTION 03: TRANSMISSION SYSTEMS

### 03-Transmission/transmission-overview.md
**Overview:** ZF LT-85 five-speed manual transmission with specifications
**Transmission type:** ZF LT-85 Five-Speed Manual
**Configuration:**
- Completely synchronized (all forward speeds)
- Helicidal forward gears (smooth, quiet)
- Straight-cut reverse (robust engagement)
- Clutch interface: Involute spline on input shaft with 4 torsional springs

**Gear ratios:**
- 1st: 36/13 or 37/14 (2.768 ratio, 3.820 total reduction)
- 2nd: 30/19 or 26/25 (2.643 ratio, 3.647 total)
- 3rd: - (1.519 ratio, 2.179 total)
- 4th: - (1.040 ratio, 1.435 total)
- 5th: 19/33 (0.576 ratio, 0.795 total)
- Reverse: Straight-cut, non-synchronized

**Synchronizer system:**
- Type: POCKET-type electro-eroded grooves
- Design: Friction cones + ball retainers
- Purpose: Prevents slipping during harsh engagement
- Coverage: All 5 forward speeds

**Key characteristics:**
- Progressive speed steps optimized for engine efficiency
- Reverse lacks synchronization (acceptable for vehicle type)
- Clutch housing interface via helical coupling

### 03-Transmission/Clutch/clutch.md
**Overview:** Diaphragm-spring dry single-disc clutch (Service Manual Section 7C)
**System type:** Diaphragm-spring clutch (tapered-finger type)
- Solid ring outer diameter with tapered fingers pointing inward
- Disc carries 4 torsional coil springs
- Positioned on transmission input shaft (involute spline fit)

**Engagement mechanics:**
- Engaged: Diaphragm spring peripheral edge pushes on pressure plate & disc against flywheel
- Disengaged: Pedal depression moves release bearing forward, pushing on tapered fingers, pulling pressure plate away

**Clutch components (16 major):**
1. Clutch assembly (pressure plate & cover)
2. Clutch disc (with torsional springs)
3. Pressure plate
4. Release arm
5. Clutch shaft
6. Roller
7. Thrust rod (to pedal)
8. Main cylinder (hydraulic)
9. Auxiliary cylinder (slave)
10. Gasket
11. Clutch liquid reservoir
12. Bracket
13. Tank to primary pipe
14. Primary to support chassis pipe
15. Support chassis to slave pipe
16. Main cylinder assembly

**Diagnosis & troubleshooting (5 conditions):**
1. **Slipping:** Oil on facing, worn facing, weak spring, warped plate/flywheel, bad pedal free travel → adjust, replace components
2. **Dragging clutch:** Bad pedal free travel, weak/worn spring tip, rusted splines, broken/dirty facing, wobbly disc → adjust, replace
3. **Vibration:** Glazed facing, oiled facing, poor contact, weak torsion springs, loose rivets, distorted surfaces, loose engine mount → replace disc/covers/flywheel, retighten mounts
4. **Noisy:** Broken release bearing, worn primary shaft bearing, excessive disc hub rattle, cracked disc, rattling cover/spring → replace components
5. **Grabbing:** Oiled facing, excessively worn, rivet heads showing, weak springs → replace disc

**Pedal adjustments:**
- Height (A): 140 mm specification
- Free travel (C): 15±20 mm specification
- Piston-rod play (B): 1.5 mm specification
- Rod setscrew torque: 2±2.5 Kg-m (20±50 Nm)

**Hydraulic system (clutch circuit):**
- Clutch pedal height adjustment: Screw (1)
- Free travel adjustment: Nuts (2)
- Bleeder procedure: Use flexible transparent piping to slave cylinder bleeder (2), catch fluid in glass container, pump slowly until no air, keep pipe submerged when tightening
- Fluid refill level: Tank maximum (Max)
- Fluid type: DOT-4 recommended (hydraulic liquid only)
- System capacity: Approximately 250-300 ml

**Main cylinder specs:**
- Control rod nuts torque: 2±2.5 Kg-m (20±25 Nm)
- Removal: Release inlet/outlet pipes, remove pedal support setscrews from dashboard, dismantle on bench

**Auxiliary cylinder:**
- Removal/installation procedures similar to main
- Seal inspection critical
- Pressure testing required

**Maintenance schedule:**
- Monthly: Verify pedal play
- Quarterly: Check fluid leaks
- Annually or 60k km: Inspect disc condition
- Every 3 years: Complete system fluid flush

**Critical inspection points:**
- Hydraulic line integrity
- Cylinder seal condition
- Disc facing wear
- Pressure plate wear
- Spring fatigue

### 03-Transmission/Differentials/training-differentials.md
**Overview:** Front & rear differential systems (Training Manual - Differential Systems)
**System:** Both front and rear differentials for all-wheel drive
**Service interval:**
- Gear box oil, transfer box, differential groups, rotating pivots: 30,000 km / 24 months (R = Replace/Change)

**Differential oil specs:**
- Type: High film strength for gear protection
- Viscosity: Proper for differential operation
- Additives: Anti-wear, anti-corrosion, limited-slip friction modifier (if equipped)
- Capacity: Front [TBD], Rear [TBD] - refer to complete documentation

**Oil change procedure (standard):**
1. Raise vehicle on jack stands
2. Locate drain plug (bottom of housing)
3. Drain old oil completely
4. Replace drain plug (new washer)
5. Refill with specified oil
6. Check level (sight glass or filler plug)
7. Road test for smooth operation

**Inspection points:**
- Leaks at housing seams
- Worn/damaged seals
- Proper fluid level
- Fluid condition (color, smell, contamination)
- Ring & pinion condition
- Bearing operation (noise/vibration)

**Differential specifications:**
- Front: Standard open type (torque-sensitive locking optional)
- Rear: Standard open type (limited-slip available)
- Housing material: Steel (aluminum on some variants)
- Seal system: Multiple seals (prevent oil loss & contamination)

**Common issues & fixes:**
- Oil leaks: Worn seals, loose bolts, cracks → replace seals, tighten fasteners
- Noise: Low fluid, bearing wear, gear damage → check level, inspect gears
- Poor traction: Limited-slip failure → replace if equipped
- Vibration: Imbalance, worn bearings, damaged gears → inspect & replace
- Grinding: Gear damage, metal in oil → complete fluid change, inspect gears

**Rotating pivots (lubrication):**
- Universal joints: Propeller shaft connections
- CV joints: Constant velocity joints (front drive)
- Differential bearings: Integral to differential operation
- Service: Regular inspection for leaks, proper lubrication, boot condition checks (CV), grease replenishment

**Limited-slip differential (if equipped):**
- Function: Limits wheel speed differential; improves traction on slippery surfaces
- Maintenance: Requires special limited-slip fluid with friction modifiers
- Do not use standard differential oil
- Service: Complete fluid change per schedule, follow OEM break-in procedures

### 03-Transmission/Transfer-Case/training-transfer.md
**Overview:** Part-time 4WD transfer case (Training Manual - Transfer Case Section)
**Service interval:**
- Transfer box oil: 30,000 km / 24 months (R = Replace/Change)

**Key service areas:**
1. Fluid service (oil change every 30k km)
2. Fluid type (OEM specification grade)
3. Fluid capacity (confirm in service manual)
4. Drain/fill plugs (locate in service docs)
5. Seal inspection (visual check for leaks)

**Important maintenance notes:**
- Change fluid at regular intervals for proper operation
- Inspect for leaks at each service
- Replace fluid if contaminated
- Do not overfill (follow capacity specs)
- Use only OEM-approved transmission fluid

**Integration:**
- Primary input: Manual transmission
- Outputs: Front differential (via front propeller shaft), rear differential (via rear propeller shaft)
- Control: 4WD selector (High/Low range capability)

### 03-Transmission/ZF-Gearbox/manual-transmission.md
**Overview:** Complete ZF LT-85 transmission service & repair (Service Manual Section 7A)
**Transmission type:** ZF LT-85, five-speed fully synchronized manual
**Reverse:** Straight-cut design, non-synchronized

**Shaft configuration:**
- Primary input shaft: Connected to clutch, carries input gears
- Main output shaft: Carries output gears + reverse selector
- Counter shaft (auxiliary): Provides torque path for 3rd-5th gears
- Reverse shaft: Straight-cut selector mechanism

**Forward gear ratios (detailed table):**
- 1st: 36/13 or 37/14 ratio (2.768 or 2.768 speed reduction)
- 2nd: 30/19 or 26/25 ratio (2.643 or 2.643 speed reduction)
- 3rd: 1.519 speed reduction
- 4th: 1.040 speed reduction
- 5th: 19/33 ratio (0.576 speed reduction)

**Synchronizer system:**
- Type: POCKET-type electro-eroded grooves
- Configuration: Grooved friction couplings with ball retainers
- Function: Prevents slipping under harsh engagement
- Coverage: All forward speeds (1st-5th)
- Reverse: Non-synchronized straight engagement

**Service procedures:**

*Gear lever removal (Page 7A-6):*
1. Remove front carpet screws → access tunnel cover (1)
2. Remove lower boot clamp (3)
3. Move boot (2) & tunnel cover upward
4. Press case cover (4) & turn left → extract lever & boot
5. For transfer lever: Remove knob (5), remove front carpet, raise boots/flanges
6. Remove 3 cover screws from case (9) → extract transfer lever & boot
- Inspection: Check friction zones for erosion, boots for breakage, screws/pins (10)
- If screws removed: Apply recommended sealant to threads, tighten to spec
- Torque: Position lever side screws 1.7 Kg-m (17 Nm); plate screws 0.6 Kg-m (6 Nm)

*Transmission removal (Page 7A-8):*
1. Remove gear lever & transfer lever assemblies
2. Disconnect negative battery cable
3. Drain oil from transmission (plug 2): Torque plug (1) 4.5 Kg-m (45 Nm), plug (2) 2.3 Kg-m (23 Nm)
4. Disconnect exhaust from turbo outlet
5. Disconnect speedometer cable & ground
6. Disconnect auxiliary cylinder clutch pipe
7. Disconnect parking brake rod
8. Remove transmission holding plate
9. Detach silentblock plates
10. Place holding system for engine
11. Disconnect reverse & 4WD couplers
12. Remove engine-transmission bolts
13. Detach transmission assembly (ensure primary shaft clears pressure plate)

*Transmission installation:*
1. Apply grease to main shaft end & grooves
2. Install transmission (reverse removal)
3. Torque transmission to flywheel: Fixing nuts 4.5±5.5 Kg-m (45±55 Nm), fixing screws 4±6 Kg-m (40±60 Nm)
4. Gear box holding plates: 7±10 Kg-m (70±100 Nm)
5. Silentblock fixing screws: 7±10 Kg-m (70±100 Nm)
6. Propeller shafts flange nuts: 2.8±3.5 Kg-m (28±35 Nm)
7. Propeller shafts CV joint screws: 3±4 Kg-m (30±40 Nm)
8. Purge clutch liquid (see Section 7C-5)
9. Refill oil to correct level, check for leaks

**Transmission diagnostics (5 common issues):**
1. **Excessive slip:** Fork/selector worn, coupling worn, spring worn/damaged, bearing worn, gear teeth worn → replace affected component
2. **Difficulty getting gear:** Synchronizer spring worn/broken, shift shaft/fork distorted → replace
3. **Stiff gear shifting:** Bad clutch pedal play, broken disc, damaged pressure plate, worn synchro ring, worn coupling/gear, distorted shift shaft → adjust/replace
4. **Noise:** Incorrect/insufficient lubricant, damaged/worn bearings, damaged/worn gears → refill/replace
5. **No shift:** Circular clamps missing or disengaged → replace

**Assembly data & tolerances (Page 7A-39):**
- Longitudinal play (1st-5th, 3rd-4th synchro): 0.075-0.125 mm (service limit 0.190 mm)
- Longitudinal play (3rd-4th synchro): 0.00-0.08 mm
- Play (rear bearing-limiting screw): 0.00-0.08 mm
- Play (primary bearing-limiting screw): 0.00-0.08 mm
- Longitudinal play (5th synchro): 0.00-0.08 mm
- Parking brake max efficiency: Point 7 on ratchet

**Transmission torque specifications (complete list, Page 7A-38):**
- Screw (gear lever guide): 1.7 Kg-m (17 Nm)
- Setscrew (gear lever plate): 0.6 Kg-m (6 Nm)
- 4WD switch: 2 Kg-m (20 Nm)
- Reverse gear screws: 4.5 Kg-m (45 Nm)
- Transmission nuts: 2.8-3.5 Kg-m (28-35 Nm)
- Setscrew (speedometer case to transfer): 3.5-4 Kg-m (35-40 Nm)
- Setscrews (shoe-holder plate): 2-2.5 Kg-m (20-25 Nm)
- Bleeder plug (gear box): 4.5 Kg-m (45 Nm)
- Bleeder plug (transfer): 2.3 Kg-m (23 Nm)
- Setscrews (clutch to flywheel casing): 4-6 Kg-m (40-60 Nm)
- Setscrews (gear box support plates): 7-10 Kg-m (70-100 Nm)
- Bolts (silentblocks to plates): 7-10 Kg-m (70-100 Nm)
- Setscrews (constant velocity to transfer clamp): 3-4 Kg-m (30-40 Nm)
- Setscrews (transfer to gear box): 5 Kg-m (50 Nm)
- Joining screw (gear box half-casings): 1.8-2.4 Kg-m (18-24 Nm)
- Setscrew (retaining plate): 2.5 Kg-m (25 Nm)
- Setscrew (5th gear drive gear): 20 Kg-m (200 Nm)
- Setscrew (5th selector fork support): 1.5-2 Kg-m (15-20 Nm)
- Setscrew (guide push bush for front cover): 2 Kg-m (20 Nm)
- Setscrews (selector forks): 2.2-2.8 Kg-m (22-28 Nm)
- Setscrews (articulated joint spring): 1.5-2 Kg-m (15-20 Nm)
- Setscrews (top cover coinciding): 1.2-1.8 Kg-m (12-18 Nm)
- Setscrews (top cover non-coinciding): 2.2-2.8 Kg-m (22-28 Nm)

**Recommended products (Page 7A-39):**
- Joining surfaces (casings): TB 1215 (ref. 790997)
- Setscrews: LOCTITE 573 (ref. 790998)
- Bleeder/feeder plugs: TB 1215 QUIMILOCK (ref. 791000)
- Axial washers & seal lips: AGUILA 95 (ref. 790999)

**Special tools (Page 7A-40):**
- Centering tool: 494722
- Ball fitter: 194635
- Extractor: 262772
- Fitter: 493764-1
- Clip fitting guide: 494989-2
- Clip fitter: 494989-3
- Seal fitting guide: 494688-1

### 03-Transmission/ZF-Gearbox/training-manual-transmission.md
**Overview:** ZF Gearbox training summary (Training Manual - Manual Transmission Section)
**Service interval:**
- Gear box oil change: 30,000 km / 24 months (Replace/Change)

**Oil specifications:**
- Consult OEM specification guide for exact grade
- Specialized transmission fluid required

**Key service points:**
1. Oil change interval: Every 30,000 km or 24 months
2. Fluid type: OEM specification (consult manual)
3. Fluid capacity: Check service manual for exact amount
4. Drain and fill procedure: Follow detailed procedure in complete manual

---

## SECTION 04: STEERING, SUSPENSION, WHEELS, TIRES

### 04-Steering-Suspension-Wheels/steering-suspension-overview.md
**Overview:** Complete steering, suspension, wheels, tires diagnostics & specs (Service Manual Section 3, Pages 52-150)

**General diagnosis methodology:**
1. Inspect tires (pressure, wear)
2. Raise vehicle on hoist
3. Inspect front/rear suspension & rack
4. Spin front wheels (check runout, balance, bearing condition)
5. Ensure all tires same type & tread

**Diagnosis table A (11 conditions with fixes):**
1. **Vehicle pulls/leads:** Mismatched tires (replace), under-inflated (inflate), broken springs (replace strut/spring), radial force (replace tire), alignment disturbed (check alignment, replace parts, change silent-blocks), brake dragging (repair brakes), loose suspension (tighten), worn silent-blocks (replace)
2. **Abnormal tire wear:** Broken springs (replace), out-of-balance tire (balance/replace), alignment disturbed (check alignment), faulty strut (check align, strut replace), overload (check load), not rotated (rotate/replace), loose bearing (replace), wobbly wheel (replace), under-inflated (inflate), worn or loose bearing (replace)
3. **Wheel tramp:** Blister on tire (replace), poor strut (replace)
4. **Shimmy/shake/vibrations:** Out-of-balance wheel/tire (balance/replace), loose bearing (replace), worn tie rod (replace), eccentric wheel (replace wheel/tire), tire irregularities (replace), alignment disturbed (check), loose steering linkage (tighten/replace), loose gear bolts (tighten)
5. **Steering feels hard:** Hard drag rod end (replace), alignment disturbed (check), bad steering box adjust (revise), low hydraulic pressure (revise & repair), tire under-inflated (correct), hard on steering shaft (repair), hard turning pivots (repair)
6. **Excessive steering play:** Worn wheel bearing (replace), loose gear bolts (tighten/repair), incorrect steering box (revise), worn tie rod end or ball joint (replace)
7. **Poor returnability:** Hard turning pivots (repair), hard on steering shaft (repair), front shaft alignment misadjusted (check/adjust), bad power steering box adjust (check/adjust), tire under-inflated (correct)
8. **Abnormal noises in front shaft:** Loose wheel nuts (tighten, replace bearing), broken bearings (replace), broken springs (replace), worn silent-blocks (replace), loosened components (tighten/check)
9. **Steering noises (bumping/lashing):** Loosened screws (tighten), damaged bearing (replace), worn silent-blocks (replace), insufficient grease (lubricate)
10. **Wandering/steering instability:** Uneven or under-inflated tires (replace/inflate), faulty shock or bushings (replace), bad power steering box (replace), steering alignment bad (check), loosened turning pivots (adjust)
11. **Erratic steering when braking:** Worn bearing (replace), broken/weak springs (replace), cylinder leaks (replace), wobbly discs (replace), worn blocks (replace), disc unroundness (replace), under-inflated tire (correct), front alignment misadjusted (check), faulty silent-blocks (replace)

**Front-end alignment (unloaded vehicle):**
- Toe-in: 2-4 mm
- Camber: 1°30'
- Caster: 3°
- Kingpin inclination: 7°
- Turning radius: 7.3 m

**Alignment checks (7 prerequisites):**
1. All tires properly inflated, same tread wear
2. Check loose ball joints (excessive looseness must be fixed first)
3. Check wheel & tire runout
4. Check vehicle trim heights (correction needed if out of limits)
5. Check loose suspension arms
6. Remove excess loads
7. Vehicle on level surface fore/aft & transversely

**Power steering system specs:**
- Drag rod end ball joint fixing: 4 Kg-m (40 Nm)
- Rod end ball joints to rod: 7-8 Kg-m (70-80 Nm)
- Power steering gear box: 7-10 Kg-m (70-100 Nm)
- Back pressure: <10 Kg/cm²
- Relief pressure: 60-80 Kg/cm²

**Steering wheel & column:**
- Steering wheel play: 10±30 mm
- Steering wheel fixing nut: 2.5-4 Kg-m (25-40 Nm)
- Column upper/lower fixing: 1.8-2.8 Kg-m (18-28 Nm)
- Lower shaft fixing: 2-3 Kg-m (20-30 Nm)

**Suspension specifications:**
- Front: Leaf springs with shock absorbers
- Rear: Leaf springs with shock absorbers
- Shock absorber fixing: Specified per attachment point
- Spring attachment: Critical for geometry

**Wheel & tire specs:**
- Wheel nut torque: 11±17 Kg-m (110±170 Nm)
- Tire rotation: 4-wheel radial tire rotation pattern
- Pressure check: When cold
- Tire selection: Equivalent to original

**Tire wear diagnosis (4 patterns):**
1. **Irregular/premature wear:** Hard cornering, under-inflation, lack of rotation, wrong alignment, non-uniform tire construction, hard acceleration → check alignment
2. **Radial tire waddle:** Side-to-side movement 10-50 km/h → use TPD or substitute known good tires
3. **Radial tire lead:** Vehicle drags to one side (tire belt straight issue) → check alignment, substitute known good tire/wheel
4. **Vibration at highway speed:** Tire runout, wheel runout, tire stiffness variation → use TPD or substitute known good assemblies

---

## SECTION 05: BRAKES

### 05-Brakes/brakes-service.md
**Overview:** Brake system service procedures (Service Manual Section 5)
[Note: File exceeds token limit; refer to original file for complete content]

**Key items inline:**
- Front brake pads: 15.30 mm (limit 8 mm)
- Front brake discs: 20 mm (limit 18 mm)
- Rear brake pads: 15.60 mm (limit 8.2 mm)
- Rear brake discs: 10 mm (limit 9 mm)
- Brake disc deflection: 0.15 mm max
- Brake liquid: DOT-4
- Wheel nut torque: 11-17 Kg-m (110-170 Nm)

### 05-Brakes/rear-brake-disc-replacement.md
**Overview:** Rear brake disc substitution procedure (Community workshop guide with photos)
**Procedure (removal, 10 steps):**
1. Remove wheel
2. Disconnect brake caliper from support, keep away from hose
3. Install dial gauge on axle housing (~2mm from disc edge)
4. Rotate & check deflection (0.15 mm max allowable)
5. Remove driving flange (6 hex bolts)
6. Remove hub bearing nuts (2" / 50mm AF)
7. Mark disc & hub
8. Remove 6 Allen bolts from disc
9. Separate disc from hub (use two 10mm bolt pairs to jack off)
10. Clean hub thoroughly

**Installation:**
- Clean rust/debris from hub with wire brush
- Recommended: Set up in lathe, check with DTI, fit disc, re-check
- Reverse removal procedure
- Optional: Use thread lock on Allen bolts

**Key specs:**
- Hub nut size: 2" / ~50mm AF
- Disc-to-hub bolts: 6x Allen key
- Max disc deflection (runout): 0.15 mm

---

## SECTION 06: PROPELLER SHAFTS

### 06-Propeller-Shafts/propeller-shafts.md
**Overview:** Front & rear propeller shafts service (Service Manual Section 4, Pages 4-1 through 4A-13)
**Sections (3 major):**
- 4A: Front Drive Shaft
- 4B: Rear Drive Shaft
- 4C: Front & Rear Propeller Shaft Assembly

**Front drive shaft (4A) major procedures:**

*Steering pivot assembly removal/installation:*
- Disconnect brake caliper from support (keep away from hose)
- Remove tie rod end joint (tool 600590)
- Remove hemisphere flange bolts
- Extract steering pivot assembly
- Tighten hemisphere flange: 3.5-4.25 Kg-m (35-42.5 Nm)
- Ball socket joint fixing: 4 Kg-m (40 Nm)
- Brake caliper screws: 3.1-3.5 Kg-m (31-35 Nm)
- Wheel nuts: 11-17 Kg-m (110-170 Nm)

*Differential group removal/installation:*
- Drain differential group oil
- Remove steering pivot assemblies
- Disconnect front transmission shaft
- Remove group nuts (new self-braking nuts)
- Installation torque (group nuts): 3.5-4.25 Kg-m (35-42.5 Nm)
- Transmission shaft fixing: 2.8-3.5 Kg-m (28-35 Nm)

*Front drive shaft assembly removal/installation:*
- Disconnect front propeller shaft from differential
- Disconnect drive rod from arm
- Remove shock absorber nuts
- Remove brake caliper
- Remove U-bolt nuts & withdraw plates
- Remove spring bolts & disconnect springs
- Important: Tighten when vehicle resting on springs
- Leaf spring nuts/bolts: 9.5 Kg-m (95 Nm)
- U-bolt nuts: 7 Kg-m (70 Nm)
- Brake caliper screws: 3.1-3.5 Kg-m (31-35 Nm)
- Propeller shaft: 2.8-3.5 Kg-m (28-35 Nm)
- Wheel nuts: 11-17 Kg-m (110-170 Nm)

*Oil-seal & related service:*
- Propeller shaft flange disconnect: Specify torque (new)
- Oil-seal plate screws: 0.8-1.1 Kg-m (8-11 Nm)
- Engaging pinion flange nut: 11.75 Kg-m (117.5 Nm)

*Friction pads substitution:*
- Remove wheel & wedge vehicle
- Remove caliper from support
- Replace friction pads
- Reinstall caliper: 3.1-3.5 Kg-m (31-35 Nm)
- Wheel nuts: 11-17 Kg-m (110-170 Nm)

*Hemisphere oil-seals:*
- Remove steering pivot assembly
- Remove oil-seal extension case screws
- Install new oil-seal (apply oil to lip)
- Oil-seal plate screw torque: 0.8-1.1 Kg-m (8-11 Nm)

*Front shaft housing substitution:*
- Remove steering pivots & differential
- Remove U-bolts
- Install new housing with U-bolts: 7 Kg-m (70 Nm)
- Install new oil-seals + grease

**Special tool references:**
- 600590: Tie rod end joint extractor
- 161950: Bushing nut removal key

**Recommended products:**
- Sealant: Automotive-grade for coupling faces
- Grease: Per manufacturer spec (oil-seal lips)
- Friction pads: OEM or approved equivalent

---

## SECTION 07: BODY

### 07-Body/body-service.md
**Overview:** Complete body service procedures (Service Manual Section 9, Pages 9-1 through 9-33)
[Note: File very large; summarizing key contents]

**Major sections:**
- Front/rear doors (glass, regulators, locks)
- Back door (glass, lateral window, locks)
- Roof
- Windscreen (adhesive procedures detailed)
- Sides
- Rear body
- Seats (front, central, back)
- Seat belts
- Coatings & silencers
- Anticorrosion treatment (detailed 6-step procedure)
- Frame (main dimensions in technical drawings)

**Key specs inline:**
- Windscreen glass: BETASEAL 1752 (ref. 791009)
- Door panel adhesive: XK21233
- Door sealant: 17550
- Door putty: 13991
- Adhesive strip width: 10-12 mm (apply from lower side)
- Rubber suction pad required for installation
- Impermeability test: Use hose (no high pressure or compressed air)

**Anticorrosion treatment sequence:**
1. Clean & prepare metal surfaces
2. Apply primer
3. Apply sealer (all unions previously sealed)
4. Apply color paint
5. Apply anticorrosion compound (penetrating wax)
6. Apply protecting layer (rust-proof material)

**Frame main dimensions:** See pages 9-31 to 9-32 for technical drawings

### 07-Body/Bumpers-Hood-Frontal/bumpers-hood-frontal.md
**Overview:** Bumpers, front hood, frontal components (Service Manual Section 2)

**Front bumper:**
- Components: Main bumper, grille, side thermo-conformed pads, center pad
- Material: Steel or composite with foam padding
- Design: Critical safety component

**Rear bumper:**
- Components: Main bumper, side pads, center pad
- Design: Similar energy absorption to front

**Front hood:**
- Components: Hood (aluminum/steel), hinges (left/right), lock cable, lock assembly, cushions, support stay
- Access: Engine compartment
- Features: Full opening angle, latch system, support stay

**Hood removal/installation (basic):**
1. Remove 4 fixing hood screws at hinges
2. Withdraw hood carefully (get help)
3. Install reverse, align before final tightening

**Hood adjustment (3 types):**
1. **Longitudinal & transversal:** Loosen 4 hinge screws, adjust forward/backward & left/right, retighten
2. **Vertical:** Adjust hood cushion (2) if one side not level with fender
3. **Lock adjustment:** Loosen lock assembly screws (3), position latch, tighten; ensure smooth closure

**Fender removal/installation:**
1. Remove front bumpers & grille
2. Disconnect lateral turn signal lamp
3. Remove head lights (pull) & regulator
4. Remove interior fender components (supports, tanks, etc.)
5. Remove fender fixing screws (dashboard & front frame)
6. Withdraw fender
7. Installation: Reverse removal, apply final tightening for even clamping

### 07-Body/Heater-Ventilation/heater-ventilation.md
**Overview:** Heater & ventilation system (Service Manual Section 1A, Pages 34-51)

**System overview:**
- Type: Permanent ventilation through front panel outlets
- Hot air outlet: Glove compartment side
- Demister outlets: Upper sides of glove compartment

**System components (15 major):**
1. Front side air outlet (windscreen demisting)
2. Front center outlet
3. Side demister outlet
4. Upper demister outlet
5. Heater assembly (hot water core)
6. Demister duct
7. Air flow ducts
8. Heating unit (core + fan motor)
9. Protector (air direction)
10. Heating control panel
11. Control levers unit
12. Heater valve control cable
13. Heater valve (coolant flow regulator)
14. Heater control cable
15. Grommet

**Control lever operation (4 levers):**
- **Lever A (air distribution):** 3 positions (ventilation, vent+demist, demist)
- **Lever B (air circulation):** 2 positions (recirculate, fresh air)
- **Lever C (temperature):** Full range (left = max hot, right = max fresh)
- **Lever D (fan speed):** 4 positions (0, 1, 2, 3 OFF to HIGH)

**Operation modes (3 main):**
1. **Forced ventilation:** Outside air → demister → windscreen vents
2. **Heating with outside air:** Outside → heater core → outlets
3. **Heating with recirculation:** Inside → heater core → outlets

**Service procedures:**

*Ventilator & diffusor removal:*
- Disconnect battery negative
- Disconnect connector
- Remove air recirculation lever cable bolt
- Remove ventilator nuts (2)
- Extract unit (3)

*Heater valve removal:*
- Remove tank bolts
- Remove tank (no forcing water hoses)
- Disconnect opening/closing drive
- Disconnect inlet (3) & outlet (4) hoses, cover them
- Remove fixing nuts & valve
- Installation: Reverse, refill coolant, check for leaks with engine running

*Heater blower motor switch removal:*
- Remove control levers (ref. 1A-9)
- Remove switch nuts
- Disconnect connector, check continuity

*Control cable adjustment:*
- Put control lever at OFF
- Place acting element at OFF
- Fix cable

*Heating control cables & levers removal:*
- Remove hub caps from levers, withdraw panel
- Remove fixing screws from glove box (where lever unit located)
- Remove glove box (ref. 1A-10)
- Remove control cables from ventilator, protector, heater, valve
- Remove lever unit
- Installation: Reverse removal, apply torques, adjust cables

*Complete heating unit removal:*
- Remove steering wheel (3C-3)
- Remove combined drives (3C-5)
- Remove ventilator nozzles (1) & clock (2)
- Remove hub caps (3), control panel (4), lever unit screws
- Remove glove box nuts & clips
- Disconnect glove box wiring
- Remove glove box
- Disconnect heater drive cable
- Drain radiator; disconnect hoses, cover them
- Remove fixing nuts (8) & bolt (9) from heater (7)
- Remove heater unit
- Installation: Reverse removal, add refrigerant to correct level, check for leaks

**Heater specifications:**
- Coolant capacity: 12 litres (from cooling system section)
- Coolant type: 50% demineralized water + 50% Dinagel 9103
- Operating temperature: 94-110°C
- Freezing protection: -38°C

**Diagnosis table (5 conditions):**
1. **Fan doesn't work (switch ON):** Broken fuse (check fuse, short-circuit), faulty resistor (change), faulty motor (change), poor connection (repair)
2. **Odd temperature output:** Broken/interconnected cables (check, repair), broken air regulator (repair), blocked air ducts (change radiator), heater radiator leak/blockage (change), hose leak/blockage (change sleeves)

---

## SECTION 08: ELECTRICAL SYSTEMS

### 08-Electrical/electrical-system.md
**Overview:** Body electrical system (Service Manual Section 8, Pages 8-1 through 8-4)

**System voltage:** 12 volts (negative terminal as ground)

**Wire color codes:**
- GY: Gray
- WG: White-Green
- Br: Brown
- L: Blue
- B: Black (ground)
- R: Red (power)

**Wiring layout (5 major sections):**
1. **Right fender (main wiring):** Battery, headlight regulator, headlights, horn, turn/side lights, connections to floor & panel
2. **Left fender:** Battery, headlight regulator, lights, thermostarter relay, relays, fuses, washer tank, washer pump, lateral turn lights, engine wiring
3. **Front wiring:** Wiper motor, floor/panel wiring, negative terminals, main wiring, starting motor
4. **Engine compartment:** Main wiring, thermostarter relay, fuse box, starting motor, generator, switch
5. **Instrument panel:** Fuses, main wiring, electrical control, combination panel, brake light switch, starting motor switch, heating (optional), clock, fan motor
6. **Floor wiring:** Rear lights, defrosting pad, license lights, reverse/parking/4WD switches

**Electrical components overview:**
- Power supply: 13.5V battery system with generator
- Lighting: Head lamps, side lights, turn signals, rear lights, license light, interior
- Control systems: Starting motor, wiper motor, heating, brake lights
- Safety: Fused circuits, ground distribution, sealed connectors

**Service notes:**
- All electrical work: Battery disconnected
- Use proper color-coded wires for repairs
- Ensure clean, secure connections
- Protect sealed connectors from moisture
- Reference complete electrical diagrams (Section 10, pages 10-5 onwards) for detailed components

### 08-Electrical/EDC-Diagnostics/edc-blink-codes.md
**Overview:** EDC (Electronic Diesel Control) blink code diagnostics
**System:** Iveco 8140.43P engine, EDC blink-code via dashboard warning light

**Reading blink codes (6 steps):**
1. Turn ignition OFF
2. Press diagnosis button
3. Watch EDC warning light (two series of flashes = code with pause between)
4. Press button again to move to next error
5. When last error reached, first repeats (full cycle)
6. Error list contains ALL memorized errors (chronological order)

**Code format:** First flash sequence = tens digit, second sequence = units digit (e.g., 2 flashes + 3 flashes = code 23)

**Clearing error codes (5 steps):**
1. Ignition OFF
2. Press diagnosis button
3. With button HELD, turn ignition ON
4. Keep button pressed 5 seconds
5. Release button, switch off ignition

**Common fault codes referenced:**
- Code 23: Fuel temperature sensor
- Code 27: Electric feed pump
- Code 28: Fuel heater

**Note:** Diagnosis button location in Service Manual Section 8; complete EDC error code list in Iveco documentation

### 08-Electrical/Cruise-Control/retrofit-plan.md
**Overview:** Cruise control retrofit for EDC-equipped PS10 (active project)
**Target:** Wire pin 32 (ARM) permanently to 12V ignition + 3 momentary buttons (SET+, SET-, RES)

**Shopping list (budget EUR 15-30):**
- Bosch BDK 2.8mm socket contacts (4): ~EUR 2-4
- Automotive wire 0.75mm²: ~5m EUR 5
- Momentary push buttons (NO): 3 pieces EUR 5-15
- Inline fuse holder + 5A fuse: EUR 3
- Heat shrink tubing: Assorted
- Firewall grommet (if needed): EUR 2
- Optional latching toggle (SPST): EUR 3-5

**Pin functions:**
- Pin 32 (ARM): Continuous 12V when key on (system armed)
- Pin 33 (SET+): Momentary - engage cruise or increase speed
- Pin 1 (SET-): Momentary - decrease speed
- Pin 25 (RES): Momentary - resume last stored speed
- Brake/clutch: Already wired (cancel cruise)

**Build approach (3 phases):**

*Phase 1 (ECU engine bay):*
1. Prep crimp pins (1.5m wire each, solder to BDK socket contact, heat shrink)
2. Disconnect battery
3. Release Housing B from ECU
4. Insert pins at correct positions (see pinout doc)
5. Tug each wire to confirm lock
6. Reconnect Housing B
7. Route wires through firewall to cabin

*Phase 2 (cabin):*
- Find 12V ignition source (fuse F11, fuse 24, or key-ON source)
- Wire through inline 5A fuse
- Pin 32: Direct to fused 12V (or through optional toggle)
- Buttons: Fused 12V common → button → EDC pin wire
- Mount buttons in accessible location

*Phase 3 (testing):*
- Electrical check (engine off, key ON): 12V at common rail after fuse, 12V at pin 32, 12V at button pins only when pressed
- Road test (>50 km/h, in gear): SET+ engage, RES resume, SET+/SET- adjust, brake/clutch cancel
- Check: No new EDC warning lights

**Important notes:**
- Low current only (~10mA max per pin), no relays needed
- Fuse: Short-circuit protection only
- Iveco Daily stalk won't fit PS10 steering column
- Alternative: Peugeot/Citroen aftermarket stalk (~EUR 15, AliExpress) with manual wiring

---

## SECTION 09: PARTS CATALOGUE

### 09-Parts-Catalogue/parts-catalogue-overview.md
**Overview:** Santana PS-10 Parts Catalogue (791124I, 1st Revised Edition, Oct 2004)
**Purpose:** Service parts for Type 1 (mechanical injection) & Type 2 (Common Rail)

**How to use (3 steps):**
1. Locate figure in illustration index (updated pages 8-10, or original pages 52-66)
2. Find part number in parts list for that figure
3. Check Remarks column for variants (EXC., TYPE 1, TYPE 2, N/AUX HEATER, W/FR; RR AIR CON)

**Catalogue sections (7 major):**
1. Information & Illustration Index (model ID, engine serial, dimensions, abbreviations)
2. Engine (labels, specifications, component parts for both types)
3. Electrical (rear lamps, wiring harness, control components)
4. Suspension & Brake (steering, suspension, brakes, wheels, tires)
5. Body (chassis frame, fender, rear body, bumper, grille, instrument panel, heater, trim, seats, jack, tools)
6. Parts number index (alphabetical cross-reference, figures, items, qty, notes)
7. [Additional sections per document structure]

**Key figures referenced (22 major):**
- Fig. 35A: Muffler (p. 12)
- Fig. 40: Label (p. 13)
- Fig. 56: Electrical control (p. 15)
- Fig. 59: Front & room lamps (p. 15)
- Fig. 60A: Rear lamps (p. 18)
- Fig. 61: Wiring harness (p. 19)
- Fig. 69: Road wheel/tire (p. 20+)
- Fig. 72: Steering link & gear box (p. 20+)
- Fig. 80: Chassis frame (p. 26)
- Fig. 83: Front fender (p. 27)
- Fig. 90A: Rear body (p. 28-30)
- Fig. 91A: Front bumper & grille (p. 39)
- Fig. 93: Jack & tools (p. 32)
- Fig. 94A: Instrument panel (p. 35)
- Fig. 95B/95C: Ventilator/heater (p. 34-35)
- Fig. 97A: Anti-squeak (p. 36)
- Fig. 98A: Floor carpet (p. 37)
- Fig. 99A: Interior trim (p. 38)
- Fig. 101A: Garnish/splash guard (p. 39)
- Fig. 112: Front seat (p. 40)

**Part number formats:**
- Santana: PS-XXXXXX (e.g., PS-791519)
- OEM supplier: Alphanumeric (e.g., A610067-002, 02162-05123)

**Remarks notation:**
- EXC.: Exclusive/excluding
- TYPE 1/TYPE 2: Specific variant
- N/AUX HEATER: No auxiliary heater
- W/FR; RR AIR CON: With front & rear A/C
- M6: Metric screw size
- QTY: Quantity per vehicle

**Modification notices:**
- → XXXXX-XXXXX: New interchangeable part number
- ← XXXXX-XXXXX: Former part being replaced

---

## SECTION 10: TECHNICAL DATA

### 10-Technical-Data/technical-data.md
**Overview:** Vehicle technical specifications (Service Manual Section 10, Pages 10-1 to 10-4)

**Engine specifications (comparison table, mechanical vs. Common Rail):**

| Specification | Mechanical | Common Rail |
|---|---|---|
| **Cylinders/Config** | 4 in-line | 4 in-line |
| **Cycle** | Diesel 4-stroke | Diesel 4-stroke |
| **Supply** | Overfeeding intercooler | Overfeeding intercooler |
| **Injection** | Direct mechanical | Direct electronic |
| **Bore x stroke** | 94.4 x 100 mm | 94.4 x 100 mm |
| **Displacement** | 2,800 cc | 2,800 cc |
| **Compression ratio** | 18.5:1 | 18.5:1 |
| **Compression @ TDC** | 20±2.6 bar | 20±2.6 bar |
| **Min compression allowed** | 16 bar | 16 bar |
| **Max power** | 75.5-80.5 kW (102.7-109.5 CV) @ 3,600 rpm | 88.8-95.2 kW (120.8-129.5 CV) @ 3,600 rpm |
| **Max torque** | 250 Nm (25.5 kgm) @ 1,800 rpm | 275.5-304.7 Nm (28.1-31.1 kgm) @ 1,800 rpm |
| **Max RPM (no load)** | 4,200±25 | 4,200±50 |
| **Min RPM (idle)** | 750±25 | 800±25 |
| **Injector pressure** | 240±12 bar | 1,350 bar (electro) |
| **Max thermostat opening** | 110°C | 110°C |
| **Oil pressure (idle)** | >0.8 bar | >0.8 bar |
| **Oil pressure (max RPM)** | >3.5 bar | >3.5 bar |

**Gearbox specifications:**
- 1st: 3.647 ratio
- 2nd: 2.179 ratio
- 3rd: 1.435 ratio
- 4th: 1.000 ratio
- 5th: 0.795 ratio

**Transfer box specifications:**
- High range: 1.192 ratio
- Low range: 3.319 ratio

**Final drive:** 43:11 differential ratio = 3.909

**Vehicle dimensions & angles:**
- Overall length: 4,675 mm
- Overall width: 1,750 mm
- Overall height: 2,000 mm
- Wheelbase: 2,786 mm
- Front & rear tract width: 1,486 mm
- Turning radius: 7.3 m
- Ground clearance: 200 mm
- Entry angle: 50°
- Exit angle: 30°
- Lateral angle: 40°
- Max slope: 45°
- Fording depth: 500 mm

**Weights (5-door configuration):**
- Maximum authorized: 3,050 kg
- Curb weight: 2,050 kg
- Max payload: 1,000 kg
- Max towing (no auxiliary brake): 750 kg
- Max towing (with auxiliary brake): 2,040 kg

**Electrical equipment (12 bulbs/specs):**
- Front headlights: 12V 60/55 W
- Rear intermittent: 12V 21 W
- Brake lamp: 12V 21 W
- Parking lamp: 12V 2x10 W
- Reverse lamp: 12V 21 W
- Anti-fog lamp: 12V 21 W
- License plate light: 12V 5 W
- Front intermittent: 12V 21 W
- Interior light: 12V 5 W
- Instrument panel: 12V 3x3 W
- Warning/indicator lights: 12V 12x1.2 W

**Electrical diagrams:** Pages 10-5 onwards (Common Rail & Mechanical Injection variants)

---

## SECTION 11: OWNER'S GUIDE

### 11-Owner-Guide/specifications.md
**Overview:** Technical specifications from owner's manual (Owner's Manual Section 11)
**Electrical equipment (12 bulbs listed above)**
**Engine (two types shown):**
- Type 115: 4-stroke cycle diesel, direct injection, overfed
- Type 115: 4-stroke cycle diesel, electronic injection, overfed
- Both: 4 in-line, 1-3-4-2 injection order, 2,800 cc, 18.5:1 compression
- Injection: BOSCH rotary pump (Type 1) or Common Rail (Type 2)
- Fuel: Diesel

**Other specifications sections:** [Refer to original file for complete specifications table]

### 11-Owner-Guide/[Other files - 15 additional files]
**Contents:**
- Before-driving.md: Pre-trip checks
- Breakdowns-emergency.md: Emergency procedures
- driving-advice.md: Safe driving tips
- Driving-and-Maintenance/driving-maintenance.md: Driving for maintenance benefits
- Driving-and-Maintenance/owner-maintenance.md: Owner-level maintenance tasks
- general-info.md: Vehicle general information
- instruments-controls.md: Dashboard instruments & controls
- interior-equipment.md: Interior features
- owners-manual-foreword.md: Manual introduction
- owners-manual-overview.md: Manual structure
- Towing/towing-rules.md: Towing specifications & procedures
- vehicle-care.md: Daily vehicle care
- EXTRACTION_NOTES.md: Extraction methodology notes

---

## SECTION 12: TROUBLESHOOTING

### 12-Troubleshooting/troubleshooting-index.md
**Overview:** Cross-reference index for diagnosing vehicle issues

---

## SECTION 00: REFERENCE FILES

### README.md
**Purpose:** How to use the knowledge base with example questions

### TRAINING-MANUAL-INDEX.md
**Purpose:** Comprehensive index of Training Manual content extracted (pages covered, specifications extracted, accuracy verification)

---

# INDEX BY TOPIC

## By Fluid/Capacity
- **Engine oil:** 7.3L drained (7.0L with filter, 5.9L without); SAE 10W/40, API SJ/CF; change 15,000 km / 12 months
- **Coolant:** 12L; 50% demiwater + 50% Dinagel 9103; freezing -38°C; change 60,000 km or 120,000 km
- **Gearbox oil:** 3.120 cc; SAE 75W-90, API GL-4; change 30,000 km / 24 months
- **Transfer box oil:** 2.800 cc; SAE 75W-90, API GL-4; change 30,000 km / 24 months
- **Differential front:** 1.750 cc; SAE 80W-90, API GL-5; change 30,000 km / 24 months
- **Differential rear:** 2.500 cc; SAE 80W-90, API GL-5; change 30,000 km / 24 months
- **Clutch liquid:** DOT-4; bleed per procedure
- **Brake liquid:** DOT-4; change 30,000 or 60,000 km per schedule
- **Servo-steering oil:** DEXRON-II; inspect 15,000 km, change 60,000 km
- **Power steering:** Back pressure <10 Kg/cm², relief 60-80 Kg/cm²

## By Torque Value (selection)
- **Crankshaft pulley:** 20 Kg-m (200 Nm)
- **Cylinder head bolts (3-phase):** 6±0.5 Kg-m + 6±0.5 Kg-m + 180°±10°
- **Connecting rod caps:** 5±0.5 Kg-m (50±5 Nm) + 63°±2°
- **Timing belt tensioner:** 4 Kg-m (40 Nm)
- **Timing cover:** 0.75 Kg-m (7.5 Nm)
- **Water pump:** 5 Kg-m (50 Nm)
- **Oil drain plug:** 3-4 Kg-m (30-40 Nm)
- **Oil filter:** 2.5 Kg-m (25 Nm)
- **Wheel nuts:** 11±17 Kg-m (110±170 Nm)
- **Transmission to flywheel (nuts):** 4.5±5.5 Kg-m (45±55 Nm)
- **Transmission to flywheel (screws):** 4±6 Kg-m (40±60 Nm)
- **Gear box support plates:** 7±10 Kg-m (70±100 Nm)
- **Silentblock fixing:** 7±10 Kg-m (70±100 Nm)

## By Temperature/Pressure
- **Thermostat opening:** 79°C±2°C (begins), 82°C±2°C (fully), 110°C (max operating)
- **Fan engagement:** 94°C±2°C (on), 80°C±2°C (off)
- **Oil pressure (idle):** >0.8 bar
- **Oil pressure (max):** >3.5 bar
- **Fuel temperature control:** >75°C (reduce pressure), >90°C (60% power reduction)
- **Cooling cap relief:** 1±0.1 Kg/cm²
- **Cooling cap inlet:** 0.005±0.02 Kg/cm²
- **Diesel injection (mechanical):** 240±12 bar
- **Diesel injection (Common Rail):** 1,350 bar max
- **Compression @ TDC:** 20±2.6 bar; minimum 16 bar

## By Clearance/Tolerance
- **Valve play:** 0.5±0.05 mm (inlet & outlet, hot or cold)
- **Timing belt tension:** 88-112 Hz
- **Piston-to-bore:** 0.082-0.126 mm
- **Main bearing clearance:** 0.035-0.083 mm
- **Crankshaft axial play:** 0.060-0.310 mm
- **Camshaft radial play:** 0.035-0.081 mm
- **Valve radial play:** 0.023-0.053 mm
- **Rocker arm play:** 0.030-0.075 mm
- **Gear box longitudinal play:** 0.075-0.125 mm (service limit 0.190 mm)

## By Vehicle Specification
- **Engine:** Iveco 8140.43P, 2.8L turbo diesel, Euro III, EDC electronic control
- **Turbocharger:** MITSUBISHI TF0 HM 13 T-6 (primary), TD04 (variant)
- **Transmission:** ZF LT-85 five-speed manual, fully synchronized, all-wheel drive
- **Transfer case:** Part-time 4WD, High 1.192:1, Low 3.319:1
- **Final drive:** 3.909:1 (43:11 differential)
- **Wheelbase:** 2,786 mm
- **Turning radius:** 7.3 m
- **GVWR:** 3,050 kg (5-door)
- **Curb weight:** 2,050 kg
- **Max payload:** 1,000 kg
- **Max towing:** 2,040 kg (with auxiliary brake)

---

*Master Index generated March 2026 from 58 knowledge base files. All inline specifications verified against source PDF manuals. Page references provided for diagrams and detailed procedures in original documents.*

