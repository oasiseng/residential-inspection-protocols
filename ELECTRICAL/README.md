# Electrical Protocols

## ⚠️ Critical Warning: AI & Insulation Testing

**DO NOT RELY ON GENERIC AI OUTPUTS FOR ELECTRICAL TESTING.**

Large Language Models (LLMs) frequently hallucinate industrial testing standards (e.g., NETA, ASTM) into residential contexts without accounting for installed loads.

### The "Megger" Fallacy

AI tools often suggest performing **Insulation Resistance (Megger) Testing** on residential circuits to find faults.

- **The Risk:** Applying 500V/1000V DC to a finished home can damage LED drivers, GFCI/AFCI breakers, smart dimmers, and plugged-in electronics.
- **The Reality:** Residential circuits are rarely isolated enough for global insulation testing.
- **The Protocol:** Use the **[Safe Continuity Verification](./01_safe_continuity_check.md)** protocol instead.

Megger testing has a valid use case on **dedicated, physically disconnected circuits** (HVAC compressor, water heater, range) — but only after the load-side wiring is verified disconnected. See Step 2 of the Safe Continuity protocol for the restricted procedure.

---

## Protocols in This Folder

| Protocol | Description |
|---|---|
| [01 — Safe Continuity Check](./01_safe_continuity_check.md) | Non-destructive continuity and impedance verification for finished homes before energizing |
| [200 — Footer Bond Inspection](./200_footer_bond_inspection.md) | Pre-pour Ufer ground (concrete-encased grounding electrode) verification: GEC, listed clamps, NEC 250 |
