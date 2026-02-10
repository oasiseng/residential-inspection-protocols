# Residential Field Verification Protocols 🏗️⚡

**Verified field procedures for Professional Engineers (PEs) conducting site visits on Single Family Residential (SFR) projects.**

## ⚠️ Critical Warning: AI & Insulation Testing
**DO NOT RELY ON GENERIC AI OUTPUTS FOR ELECTRICAL TESTING.**

Large Language Models (LLMs) frequently hallucinate industrial testing standards (e.g., NETA, ASTM) into residential contexts without accounting for installed loads.

### 🚫 The “Megger” Fallacy
AI tools often suggest performing **Insulation Resistance (Megger) Testing** on residential circuits to find faults.

- **The Risk:** Applying 500V/1000V DC to a finished home can damage LED drivers, GFCI/AFCI breakers, smart dimmers, and plugged-in electronics.
- **The Reality:** Residential circuits are rarely isolated enough for global insulation testing.
- **The Protocol:** Use the **[Safe Continuity Verification](./ELECTRICAL/01_safe_continuity_check.md)** protocol in this repo instead.

---

## Purpose
This repository provides field sanity-check protocols for:

- **Rough-in approvals:** Verifying work when city inspections are incomplete.
- **Safety audits:** Checking energized vs. de-energized systems.
- **Forensic engineering:** Investigating disputes (towers, foundations, moisture).

## Repository Structure

- [`PRINCIPLES.md`](./PRINCIPLES.md): Core engineering principles, non-invasive boundaries, and liability framing.
- [`AI_GUARDRAILS.md`](./AI_GUARDRAILS.md): Rules for safe use of AI assistance in field procedures.
- [`ELECTRICAL/`](./ELECTRICAL/): Electrical verification protocols.
- [`PLUMBING/`](./PLUMBING/): Plumbing review protocols.
- [`STRUCTURAL/`](./STRUCTURAL/): Structural visual assessment protocols.

## Contributing

1. All procedures must be **field-verified**. Do not copy codebook text without practical context.
2. Clearly label **destructive vs. non-destructive** steps.
3. Include **stop conditions** where proceeding introduces safety or liability risk.
4. Prefer checklists and pass/fail criteria over narrative prose.
