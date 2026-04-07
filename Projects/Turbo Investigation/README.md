# Turbo Investigation - Santana PS10 (24-BX-HS)

Investigating stuck wastegate, boost leaks, and whistle noise.

## Turbocharger Identification

Two turbo variants exist for the PS10 per the Parts Catalogue (FIG.21):
- **TYPE 1:** Santana P/N A240013-010, likely Mitsubishi TF035HM-13T-6
- **TYPE 2:** Santana P/N A240016-000, likely Mitsubishi TD04

Label on the turbo is too dirty to read. Need to clean the ID plate on the compressor housing (cold side) with brake cleaner and brass brush. Key identifier: part number prefix 49135 = TF035, 49377 = TD04.

## Stuck Wastegate

Wastegate actuator is pneumatic (boost pressure operated via hose from compressor to diaphragm canister with rod). The rod is stuck and won't move by hand. Most likely cause: carbon/soot seizure at the wastegate flap pivot inside the turbine housing.

A stuck-closed wastegate means unregulated boost pressure. This is the primary concern.

## Wastegate Actuator Hose and Boost Leak (2026-04-02)

Pressure-tested the boost hose system at 0.5 bar and found:
- **Leak on a larger boost hose**, plan is to patch for now
- **Smaller wastegate actuator reference hose**, diameter not specified in any Santana manual. Typical TD04/TF035 wastegate hose is ~4mm ID. The hoses expanded visibly at 0.5 bar, indicating age degradation.
- **Wastegate actuator test plan:** apply ~1 bar to the actuator to check for rod movement. Expected crack pressure is 0.7-1.0 bar. Do not exceed 1.5 bar (diaphragm risk).
- Replacement hose should be silicone, rated for 3+ bar boost pressure.

## Boost Whistle Noise

New whistle above 2000 RPM under load, mainly at ~100 km/h, disappears instantly off-throttle. Audible from right side / passenger footwell area. Garage said "normal, no leaks" but this diagnosis is likely wrong.

Found a very small leak at the intercooler-to-intake hose (soft breeze, not audible, under 0.5 bar test pressure). Also found a larger hose leak during further pressure testing.

**Conclusion:** Multiple small boost leaks confirmed. The stuck wastegate combined with degraded hoses are the likely cause.

## Next Steps

1. Patch big hose leak
2. Test wastegate actuator at 1 bar
3. Reassess whistle after fixes
4. Clean and read turbo ID plate
