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
  - [`200_footer_bond_inspection.md`](./ELECTRICAL/200_footer_bond_inspection.md): Footer bond (Ufer ground / concrete-encased grounding electrode) — GEC verification, listed clamp requirements, NEC 250.
- [`PLUMBING/`](./PLUMBING/): Plumbing review protocols.
- [`STRUCTURAL/`](./STRUCTURAL/): Structural visual assessment protocols.
  - [`101_footer_inspection.md`](./STRUCTURAL/101_footer_inspection.md): Pre-pour footer (footing) verification — dimensions, rebar, soil bearing, dowels.
- [`STANDARDS_FRAMEWORK.md`](./STANDARDS_FRAMEWORK.md): IEBC/IRC/IBC + ASTM/ISO grounding model for protocols.
- [`PROTOCOL_TEMPLATE.md`](./PROTOCOL_TEMPLATE.md): Standardized protocol format for future modules.

## Contributing

1. All procedures must be **field-verified**. Do not copy codebook text without practical context.
2. Clearly label **destructive vs. non-destructive** steps.
3. Include **stop conditions** where proceeding introduces safety or liability risk.
4. Prefer checklists and pass/fail criteria over narrative prose.

## Next Modules (Draft Structure)

```text
residential-field-protocols/
├─ structural/
│  └─ 01_crack_classification.md
├─ plumbing/
│  └─ 01_functional_flow_test.md
└─ hvac/
   └─ 01_delta_t_split.md
```


## Improvement Priorities (Recommended Next Pass)

1. Normalize directory naming (choose upper-case or lower-case discipline folders and keep one convention).
2. Add a protocol metadata header for every module (version, author/reviewer PE, revision date, jurisdiction assumptions).
3. Add quick field forms/checklists per module to improve repeatability and evidence quality.
4. Add a standards trace table in each protocol separating required code basis vs guidance references.
