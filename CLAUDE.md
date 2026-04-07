# Santana PS10 Knowledge Base Project

## Vehicle
This project contains documentation for a **2006 Santana PS10** station wagon (Type 1/Type 2).
- **Engine:** Iveco 8140.43P, 2.8 Turbo Diesel, Euro III
- **Turbocharger:** Mitsubishi TD04 (or TF0 HM 13 T-6 depending on variant)
- **Gearbox:** ZF LT-85 manual transmission (updated variant)
- **Transfer:** Part-time 4WD
- **Odometer:** ~120,000 km
- **Registration (NL):** 24-BX-HS

## Project Structure
- `/Manuals/` - Original PDF manuals (do not modify). These are the **source of truth**.
- `/Knowledge Base/` - Extracted markdown summaries organized by vehicle system
- `/Verzekering/` - Insurance documents (Dutch)

## How to Answer Questions - CRITICAL

**The number one rule: never guess or hallucinate specifications, part numbers, torque values, or procedures.**

### Precomputed Index Layer (use FIRST)
The `/Knowledge Base/00-Master-Index/` folder contains precomputed lookup files. Start here for most questions:

| File | Use when... |
|------|-------------|
| `master-index.md` | You need to find which KB file covers a topic, or need inline specs without opening other files |
| `quick-reference-specs.md` | Any question about torque values, fluid capacities, clearances, pressures, electrical specs, dimensions, weights |
| `part-number-crossref.md` | Any question about part numbers (Santana, Iveco, Bosch, ZF cross-references) |
| `pdf-page-index.md` | You need to look something up in the original PDF and need the exact page range |
| `kb-gap-audit.md` | Check whether a topic has been extracted to the KB or is only in the PDFs |

### Lookup Flow
1. **Check the index files first.** For specs, parts, or general info, `quick-reference-specs.md` or `part-number-crossref.md` often has the answer in one read. Done.
2. **If more detail is needed,** use `master-index.md` to find the right KB file, then read that file.
3. **If the KB doesn't cover it,** use `pdf-page-index.md` to jump to the exact PDF page. No scanning.
4. **Web search** only for topics not in the manuals (aftermarket parts, community fixes, cross-references).
5. **General knowledge** from training data can frame answers, but label it as such.

### Source Attribution
- Only cite sources for safety-critical info (torque you'll tighten to, parts you'll order, procedures you'll follow).
- For general/conversational questions, skip the per-fact attribution. Keep answers direct.
- If you cannot verify something: say so clearly.

## Source PDFs and Page Ranges
These are the original manuals to read when verification is needed:

| Manual | File | Size | Key Content |
|--------|------|------|-------------|
| Service Manual | `Service Manual PS10.pdf` | 627pg | Workshop procedures, torque specs, diagnostics |
| Parts Catalogue | `002  ZF equipped Parts catalogue (updated parts info).pdf` | ~300pg | Part numbers, exploded diagrams |
| Owner's Manual | `004   Owner's manual 791160-2L (English-French).pdf` | 245pg | Driver info, specs, warning lights |
| Training Manual | `Santana Training Manual.pdf` | 274pg | Dealer training, maintenance schedules, engine/transmission detail |
| Rear Brakes | `Rear Brakes 5-29.pdf` | 1pg | Rear brake disc replacement |

## Searching Strategy
- **Start with `/Knowledge Base/00-Master-Index/`** - the precomputed files answer most questions in one read
- **For specs:** `quick-reference-specs.md` has 1000+ values (torque, capacity, clearance, pressure, electrical)
- **For parts:** `part-number-crossref.md` has 122+ entries with Santana/OEM cross-references
- **For deeper detail:** `master-index.md` points to the right KB file with inline key specs
- **For PDF lookups:** `pdf-page-index.md` maps topics to exact page ranges across all 5 manuals
- **Grep across KB** only when the index files don't cover it, or for unusual keywords
- For wiring/diagrams, always refer to the PDF since diagrams cannot be represented in markdown
- Check `kb-gap-audit.md` to know if a topic exists in the KB or only in the PDFs

## Important Notes
- This is the **ZF gearbox** (LT-85) variant, not the earlier transmission. Parts and procedures may differ from non-ZF PS10s.
- The engine is the **8140.43P** (Euro III with EDC), not to be confused with earlier 8140.43 variants (Euro II).
- The Parts Catalogue contains both updated (1st REM, pages 3-43) and original figures (pages 44+). Check updated pages first.
- Some PDF content is image-based (scanned). The knowledge base markdown contains extracted text; refer to the PDF for diagrams and images.
- EDC diagnostics use a blink-code system via a dashboard diagnosis button.
- KB extraction files have been audited against source PDFs (see `deep-audit-report.md`). Trust KB values for routine lookups; verify against PDF only if a value seems wrong or for first-time safety-critical work.

## Maintenance Context
At 120,000 km the vehicle has completed a full maintenance cycle. The next cycle repeats from the beginning of the schedule. Key upcoming items mirror the 15,000 km service interval items.

## Working Preferences

### No Hallucination (reinforces the #1 rule above)
Never guess specifications, part numbers, torque values, or repair procedures. The owner works on this vehicle themselves; incorrect values could cause real damage. Layer answers with clearly labeled sources: (1) general knowledge about the platform, (2) Knowledge Base extracts, (3) verified from original PDF pages, (4) web search. If something cannot be verified, say so explicitly. Always offer to check the original PDF when the user needs certainty.

### Part Number Cross-Referencing
Santana catalog numbers often differ from the underlying Iveco, Bosch, or other OEM part numbers for the same component. When looking up parts, always search by both Santana and OEM numbers. When presenting part information, show both numbers where available. Using only one numbering system may miss available parts or lead to ordering wrong components.

## Active Projects

Check `Projects/*/README.md` for current project state. Active projects:
- **Cruise Control Retrofit** - `Projects/Cruise Control Retrofit/` (blocked by speedometer fix)
- **Turbo Investigation** - `Projects/Turbo Investigation/` (wastegate flutter after freeing)
- **Speedometer Issue** - `Projects/Speedometer Issue/` (heat-related drift, blocks cruise control)

## Where Context Lives

| Location | Contains |
|----------|----------|
| This file (`CLAUDE.md`) | Behavioral rules, vehicle specs, lookup instructions |
| `Projects/*/README.md` | Active project state, decisions, next steps |
| `Knowledge Base/Owner/` | Owner-specific data (oil choice, preferences) |
| `Knowledge Base/` | Vehicle technical data extracted from manuals |
| `Manuals/` | Original source PDFs (source of truth) |
