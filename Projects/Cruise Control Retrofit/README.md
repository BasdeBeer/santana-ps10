# Cruise Control Retrofit - Santana PS10 (24-BX-HS)

Retrofitting cruise control using the existing Bosch MS 6.3 EDC capability with custom buttons.

## Files

- [Shopping List](shopping-list.md) - What to buy and where
- [Wiring Plan](wiring-plan.md) - How to wire it, step by step
- [EDC Housing B Pinout](edc-housing-b-pinout.md) - Full connector pin reference
- [Research Notes](research-notes.md) - Forum findings and background info

## The Short Version

The ECU already supports cruise control. Brake and clutch switches are already wired. You just need to:

1. Buy 4x Bosch BDK 2.8mm crimp pins (P/N 1928498056)
2. Solder wires to them
3. Insert into EDC Housing B at pins 1, 25, 32, 33
4. Route wires through firewall to cabin
5. Connect to momentary buttons fed by fused 12V ignition
6. Test

Minimum viable: just wire pin 33 (SET+) for "hold current speed". Brake/clutch cancel automatically.

## Key Technical Details

**Pin 32 (cable 8154) uses normally-closed logic.** Continuous 12V = system armed. 0V = system off + stored speed erased. Source: Iveco forum t8593 and Aufbauherstellerschulung document.

**Recommended wiring:** Wire pin 32 permanently to fused 12V ignition (no toggle needed). System arms with key, disarms with key. Brake/clutch cancel safely. Only 3 momentary buttons needed: SET+ (pin 33), SET- (pin 1), RES (pin 25).

**Decision:** Simple permanent wire on pin 32 (preferred over toggle switch).

## Background

- Forum evidence: 140+ posts confirm every electronically-injected 1999-2006 Daily III worked plug-and-play. No ECU coding needed. PS10 has the same MS 6.3 EDC with 8140.43P engine.
- **Fallback if not enabled:** Send ECU to specialist (ECU Connection UK, ~EUR 150-300) for 24C16 EEPROM bench programming. 38-pin round diagnostic connector with K-Line protocol; standard OBD tools don't work.
- **Why:** Highway cruise comfort. No stalk fits PS10 column.
