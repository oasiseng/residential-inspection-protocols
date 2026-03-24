# Residential Inspection Protocols

**Open-source, field-verified inspection protocols for residential construction and existing homes.**

Built by [Oasis Engineering](https://oasisengineering.com) — a structural and forensic engineering firm based in Florida. These protocols are what we actually use in the field on single-family residential (SFR) projects, and we're sharing them so junior engineers, building inspectors, and contractors have a reliable, code-grounded reference instead of guessing or relying on generic AI outputs that miss critical details.

Need an engineer letter for your project? See our [inspection and engineering letter services](https://oasisengineering.com/letters).

---

## What This Repo Is

A growing library of **step-by-step inspection protocols** covering structural, electrical, plumbing, and HVAC disciplines for residential construction. Each protocol includes:

- **Scope and objective** — what the inspection covers (and what it doesn't).
- **Code and standard basis** — specific FBC, NEC, ACI, IRC, and ASTM references with section numbers, not vague “per code” language.
- **Procedure steps** — the actual field sequence, written for someone holding a tape measure at the trench, not sitting at a desk.
- **Pass / Hold / Fail criteria** — clear decision framework so the inspection produces a definitive result.
- **What AI gets wrong** — each protocol flags the most common errors that LLMs and generic checklists produce for that specific inspection. We've seen these mistakes in the wild and they can be dangerous.
- **Photo documentation checklist** — shot-by-shot list so the inspection record is complete and defensible.
- **Escalation path** — when to stop and who to call.

## Who This Is For

- **Junior engineers and EIs** building field experience before or after their PE.
- **Building inspectors** who want a second reference beyond the codebook.
- **Contractors and superintendents** who want to know what the engineer is checking and pass the first time.
- **PE firms** looking for a protocol template they can adapt to their own practice.
- **Anyone studying for the PE exam** who wants to see how code provisions translate to real field decisions.

## Jurisdiction

Protocols are primarily written for **Florida Building Code (FBC)** and **NEC** as adopted in Florida, with ACI 318 and IRC references where applicable. The principles and inspection logic apply broadly, but always verify against your local Authority Having Jurisdiction (AHJ).

---

## Protocols

### New Construction Inspections
| Protocol | Discipline | Description |
|---|---|---|
| [101 — Footer](./STRUCTURAL/101_footer_inspection.md) | Structural | Pre-pour footing verification: trench dimensions, longitudinal rebar, lap splices, vertical dowels, bearing soil, 3 in. cover |
| [103 — Column](./STRUCTURAL/103_column.md) | Structural | Pre-pour/pre-grout column verification: vertical bars, ties/stirrups (135° hooks), lap splice zones, cover, CMU and cast-in-place |
| [104 — Foundation Steel](./STRUCTURAL/104_foundation_steel.md) | Structural | Complete foundation reinforcement system verification: bar schedule, splice integration, corners/intersections, support and cover |
| [105 — Foundation Walls / Stem Walls](./STRUCTURAL/105_foundation_walls_stem_walls.md) | Structural | CMU stem wall pre-grout verification: block coursing, vertical/horizontal rebar, bond beam, shearwall reinforcement, cell prep |
| [106 — Slab](./STRUCTURAL/106_slab.md) | Structural | Slab-on-grade pre-pour: subgrade compaction, vapor barrier, WWF elevation on chairs, under-slab plumbing, thickness/elevation |
| [121 — Fill Cells](./STRUCTURAL/121_fill_cells.md) | Structural | CMU grout placement verification: pre-grout cell inspection, consolidation, lift heights, grout material, TMS 402/602 |
| [200 — Footer Bond](./ELECTRICAL/200_footer_bond_inspection.md) | Electrical | Concrete-encased grounding electrode (Ufer ground): GEC size, listed clamp vs. non-listed clamp, NEC 250.52(A)(3), NEC 250.70 |

### Existing Home Inspections
| Protocol | Discipline | Description |
|---|---|---|
| [Crack Classification](./STRUCTURAL/01_crack_classification.md) | Structural | Visual crack classification: shrinkage/thermal vs. settlement/lateral, escalation triggers |
| [Deck Visual Assessment](./STRUCTURAL/01_deck_visual_assessment.md) | Structural | Deck and exterior structure visual assessment |
| [Safe Continuity Check](./ELECTRICAL/01_safe_continuity_check.md) | Electrical | Non-destructive continuity verification for residential circuits |
| [Functional Flow Test](./PLUMBING/01_functional_flow_test.md) | Plumbing | Water supply functional flow and pressure assessment |
| [Non-Invasive Plumbing Review](./PLUMBING/01_noninvasive_plumbing_review.md) | Plumbing | Visual plumbing system review without opening finishes |
| [Delta-T Split](./hvac/01_delta_t_split.md) | HVAC | Supply/return temperature differential check for AC performance |

## Reference Documents

- [`PRINCIPLES.md`](./PRINCIPLES.md) — Core engineering principles: safety-first, non-invasive by default, field reality over theoretical purity.
- [`AI_GUARDRAILS.md`](./AI_GUARDRAILS.md) — Rules for safe use of AI assistance in field procedures.
- [`STANDARDS_FRAMEWORK.md`](./STANDARDS_FRAMEWORK.md) — IEBC/IRC/IBC + ASTM/ISO grounding model for how we cite standards.
- [`PROTOCOL_TEMPLATE.md`](./PROTOCOL_TEMPLATE.md) — Standardized 11-section template for writing new protocols.

## Contributing

1. All procedures must be **field-verified**. Do not copy codebook text without practical context.
2. Clearly label **destructive vs. non-destructive** steps.
3. Include **stop conditions** where proceeding introduces safety or liability risk.
4. Prefer checklists and pass/fail criteria over narrative prose.
5. Follow the [Protocol Template](./PROTOCOL_TEMPLATE.md) for new modules.

## License

[MIT](./LICENSE)
