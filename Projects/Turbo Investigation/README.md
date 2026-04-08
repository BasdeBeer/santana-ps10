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

**Permanent fix:** Replace wastegate actuator (see Sourcing section below). Must match original boost pressure rating.

## Factory Boost Pressure (Verified)

**Maximum boost pressure: 1.45 ± 0.039 bar**

Source: `Service Manual PS10.pdf`, Section 6A "Engine Repair", General Characteristics → "OVERFEEDING" table, **page 227**. The table column is headed for the 8140.43S.4 (Common Rail with intercooler). Engine plate on this vehicle reads 8140.43P; the same Mitsubishi TD04 turbo is used across the 8140.43 family so the spec is expected to apply, but a 43P-specific column has not been confirmed. Verify by re-reading pages around 227 if certainty is needed.

Implication: any replacement actuator must have a spring rated to crack at ~1.4-1.5 bar gauge. **Earlier "0.8-1.0 bar" estimates were general knowledge and are wrong for this engine.**

## Sourcing (EU only — see `Knowledge Base/Owner/sourcing-preferences.md`)

### Preferred whole-turbo source (verified live, NL-domestic)
- **Turboshop.nl** — `https://www.turboshop.nl/4937707000.html`
  - **Brand-new factory Mitsubishi turbo** (not reman, not exchange)
  - Mitsubishi P/N 49377-07000, fits Iveco Daily III 2.8 (8140.43)
  - €352.35 + €15 shipping = ~€367 total
  - 3 in stock as of 2026-04-08, ships in 1-6 days
  - 2-year factory warranty
  - No core deposit / no exchange required
  - Vendor based in NL — domestic shipping, Dutch consumer law

### Preferred standalone-actuator source (verified live, requires contact form)
- **Depotop.com (FR)** — `https://depotop.com/actuator/wastegate-49377-07010`
  - "Actuator pour IVECO 49377-07000 / 49377-07010", ~€85 TTC
  - Spring rating not published — must request via on-site form
  - Form text to send (in French) is in conversation history; ask for spring rating in bar before ordering

### Other verified EU whole-turbo options (backup)
- Turbodepot.fr — `https://turbodepot.fr/produit/turbo-iveco-daily-2-8d-mitsubishi-49377-07000-et-49377-07010/` — €285 reman, FR
- Turboservice24.de — `https://www.turboservice24.de/en/turbocharger-iveco-daily-iii-2-8-l/92-kw-125-hp/8140-43s/49377-07010-49377-07000_759641_5429` — €299 exchange, DE (requires core return)
- Centromotoriturbo.com — `https://centromotoriturbo.com/products/turbocompressore-revisionato-mitsubishi-49377-07000-per-fiat-ducato-iveco-daily-opel-movano-renault-master` — €320 reman, IT
- Turboshop.th-group.eu (Turbo's Hoet) — `https://turboshop.th-group.eu/en/turbo/allinclusive/mxt49377-07010` — €442.55, BE

### Excluded (non-EU per owner sourcing preference)
- turborebuild.co.uk (UK, post-Brexit customs)
- store.kinugawaturbosystems.com (US)
- fedicturbo.com (US)
- AliExpress (CN)

## Replacement Decision

Two viable paths:

**Path 1 — Actuator only (~€85, small in-situ job):**
- Pros: cheapest, smallest job (2 bolts + 1 E-clip + 1 hose, no exhaust/oil/coolant disturbance, 1-2 hours), reversible (keep old actuator as fallback)
- Cons: spring rate uncertain until Depotop replies, bracket bolts may be seized after 121k km of heat cycling, doesn't address cartridge wear if any
- Pick if: turbo cartridge passes physical inspection (no shaft play, no oil in housing)

**Path 2 — Brand-new whole turbo from turboshop.nl (~€367, half-day to full-day job):**
- Pros: brand-new genuine Mitsubishi, NL domestic vendor, 2 yr warranty, no spring-rate guesswork, no core return, ~150k km of zero turbo worries afterward
- Cons: 4× the cost, much bigger install (manifold studs, oil feed/return, coolant lines, downpipe, intercooler piping), risk of seized exhaust fasteners
- Pick if: turbo cartridge fails inspection OR willing to pay for "buy once, forget"

**Recommended approach:** inspect cartridge first (10 min: pull intake hose, wiggle compressor wheel, look for oil), then pick path based on result.

## In-Situ Actuator Replacement Procedure (research summary)

The actuator on a TD04L 49377-07000 **can** be replaced with the turbo still on the engine:
- 2× 12mm bolts thread directly into the aluminum compressor housing (accessible from outside)
- Rod connects to wastegate arm via simple **E-clip on a pin** (no crimped/screwed joint)
- No oil feed, coolant lines, or heat shield removal required
- Rod thread is M6×1.0 (1 turn = 1mm length change)

Procedure:
1. **Mark current rod position** (count threads under locknut, photo) — preserves boost setting
2. Disconnect vacuum reference hose
3. Pop E-clip off clevis pin (flat screwdriver) — have spare E-clips ready
4. Slide clevis off wastegate arm pin
5. Undo 2× 12mm bracket bolts from compressor housing
6. Transfer bracket to new actuator if needed; set rod length to match old preload
7. Reinstall in reverse, snug bolts only (~6.5 Nm into soft aluminum, do not overtorque)

Gotchas:
- **Seized bracket bolts** — soak with penetrant 24-48h beforehand, heat-cycle the bracket area (NOT the housing) with a propane torch, let cool naturally, repeat
- **Tight clearance** — use a stubby 12mm socket, may need to flex intercooler/intake hose aside
- **Don't grease the new rod** — should run clean and dry

Bench test before driving: hand pump 0.7-0.9 bar to actuator nipple, watch for 1-2mm rod travel. Do not exceed 1.0 bar during test.

Setup: preload rod 1-2mm (1-2 full turns from flap-just-closed) so wastegate seats firmly at idle.

## Boost Leaks

Pressure-tested at 0.5 bar and found:
- Leak on a larger boost hose (patched)
- Very small leak at intercooler-to-intake hose
- Wastegate actuator reference hose (~4mm ID) expanded visibly, indicating age degradation; replace with silicone rated for 3+ bar

## Boost Gauge

Recommended: mechanical 0-2 bar gauge, tee into wastegate actuator pressure line. Confirms actual boost and wastegate behavior. Shows both vacuum (off-throttle) and boost (under load).

## Next Steps

1. **Inspect turbo cartridge** — pull intake hose, wiggle compressor wheel for axial/radial play, check housing for oil. Decides actuator-only vs whole-turbo.
2. **Soak bracket bolts** with penetrating oil now (front-loading — gives best chance of clean removal whichever path is chosen)
3. **If turbo passes inspection:**
   - Submit Depotop contact form with French message asking for spring rating in bar (target ~1.4-1.5 bar)
   - Order spare E-clips at the same time
   - Adjust wastegate rod nut / try spacers in the meantime to reduce flutter
4. **If turbo fails inspection:**
   - Order brand-new Mitsubishi from turboshop.nl (€367, 3 in stock)
   - Plan whole-turbo swap (manifold studs, oil/coolant, downpipe)
5. Install mechanical 0-2 bar boost gauge tee'd into wastegate reference line — verifies real boost and wastegate behavior after the fix
6. Replace degraded boost hoses with silicone rated for 3+ bar
