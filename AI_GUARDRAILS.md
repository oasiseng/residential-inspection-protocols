# AI Guardrails for Engineering Field Procedures

## Purpose
Define safe boundaries for using AI tools when preparing, adapting, or reviewing residential field verification protocols.

## Allowed Uses

- Drafting checklists from already-verified internal procedures.
- Reformatting procedures for clarity.
- Generating reminder prompts for documentation completeness.
- Comparing wording against known standards already selected by the engineer.

## Prohibited Uses

- Accepting AI-generated test methods without field validation.
- Using AI outputs as the sole basis for safety-critical decisions.
- Applying industrial/utility testing methods directly to occupied residential systems.
- Treating AI citations as verified unless primary references are reviewed.

## Required Human Checks

1. Confirm scope matches residential conditions.
2. Confirm each step is non-destructive unless explicitly justified.
3. Confirm stop conditions and pass/fail criteria are present.
4. Confirm tool settings cannot damage connected devices.
5. Confirm protocol aligns with local AHJ/code context.

## Red Flags That Require Rejection

- “Megger the full panel in a finished home.”
- Missing isolation/disconnection requirements.
- No warnings about installed electronics.
- No escalation path for ambiguous readings.

## Governance
Any AI-assisted change to a protocol must be reviewed and approved by a qualified engineer before use in the field.
