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
