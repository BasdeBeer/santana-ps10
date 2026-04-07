# Turbo Investigation - Santana PS10 (24-BX-HS)

Investigating wastegate flutter, boost leaks, and whistle noise.

## Turbo Confirmed

**Mitsubishi TD04L** (was uncertain before, now confirmed by reading the plate):
- Mitsubishi MFD: 49377-07000 (superseded by 49377-07010)
- Iveco P/N: 500372214
- Santana P/N: A240016-000 (TYPE 2 per Parts Catalogue FIG.21)

## Wastegate Issue

**Problem:** Actuator rod was stuck extended (out) = wastegate flap held permanently open = underboost + flutter/whistle at 2000-2500 RPM / ~100 km/h under load. Stops when lifting throttle.

**Temporary fix (April 2026, ~121,400 km):** Freed with MoS2 penetrating oil (not silicone, which burns off at exhaust temps). Worked rod back and forth.

**Current status:** Still fluttering after refit. Likely the flap is not seating fully due to actuator angle or weak spring.

**Fixes to try:**
- Adjust rod nut (one full turn increments)
- Add steel spacers/washers to actuator bracket for finer adjustment
- Do NOT weld or permanently close the wastegate; no boost limit = engine damage
- At steady 100 km/h the wastegate should be mostly closed; flutter = flap chattering at threshold

Note: slight play on the flap pivot is normal.

**Permanent fix:** Replace wastegate actuator (~EUR 85 from Depotop.com, or EUR 30-80 on eBay/AliExpress). Must match original boost pressure rating.

## Boost Leaks

Pressure-tested at 0.5 bar and found:
- Leak on a larger boost hose (patched)
- Very small leak at intercooler-to-intake hose
- Wastegate actuator reference hose (~4mm ID) expanded visibly, indicating age degradation; replace with silicone rated for 3+ bar

## Boost Gauge

Recommended: mechanical 0-2 bar gauge, tee into wastegate actuator pressure line. Confirms actual boost and wastegate behavior. Shows both vacuum (off-throttle) and boost (under load).

## Next Steps

1. Adjust wastegate rod nut / try spacers to eliminate flutter
2. If flutter persists, replace actuator (~EUR 85)
3. Install boost gauge to verify behavior
4. Replace degraded boost hoses with silicone
