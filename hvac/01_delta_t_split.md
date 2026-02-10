# Protocol: A/C Delta-T Split Check (Thermometer + Anemometer)

## Scope
Non-invasive cooling performance screen for residential split systems using return/supply temperature difference and basic airflow indicators.

## Purpose
- Determine whether cooling output is in a functional range.
- Identify when performance is likely degraded and requires licensed HVAC follow-up.
- Avoid unnecessary invasive refrigerant-side intervention during initial field triage.

## Code Grounding (Performance Context)
- **IEBC Performance Compliance Methods (Chapter 14):** Evaluate whether existing HVAC performance remains adequate for intended occupancy conditions.
- **IRC Existing Structures (R102.7):** Existing systems can remain when functioning safely; assessment emphasizes in-service performance.

## Tools
- Digital thermometer (fast response preferred)
- Basic anemometer (for relative register airflow checks)
- Notepad/field form
- Camera

## Safety + Non-Destructive Limits
- Do **not** connect refrigerant manifold gauges during initial screening unless justified by prior non-invasive findings and performed by a licensed HVAC technician.
- Do **not** vent refrigerant or disturb sealed refrigerant components.
- Keep panel removal minimal and within safe access boundaries.

## Preconditions
- Thermostat set to COOL with at least 10–15 minutes of stable runtime.
- Doors/windows in normal occupied condition.
- Filter present and reasonably clean enough for a valid screen.

## Step 1: Measure Return and Supply Air Temperatures
1. Measure **return air temperature** at return grille or nearest accessible return plenum point.
2. Measure **supply air temperature** at a representative supply register near the air handler (avoid first minute of startup).
3. Compute **Delta-T (Split) = Return − Supply**.

### Target Range
- Typical functional target: **16°F to 22°F split** under steady operation.

## Step 2: Relative Airflow Screen (Anemometer)
- Take quick relative readings at multiple supply registers.
- Look for major imbalance (very low/near-zero velocity in one branch vs. others).
- Correlate airflow irregularities with comfort complaints and room distribution.

## Step 3: Interpretation
- **Pass (Functional):** Delta-T in target range with generally consistent airflow.
- **Monitor:** Borderline split or moderate airflow imbalance with no immediate safety issue.
- **Escalate:** Split persistently below ~16°F or above ~22°F (context-dependent), icing signs, short cycling, or severe airflow deficiency.

## What AI Gets Wrong
- **Gauge-first advice:** LLMs often jump straight to manifold gauges and “check charge” before completing non-invasive diagnostics.
- **Invasiveness blind spot:** Connecting gauges can introduce refrigerant loss/contamination risk and should not be routine triage.
- **Single-cause assumptions:** AI may assume refrigerant charge is the only issue while ignoring airflow, filter, coil, or duct distribution factors.

## Documentation Minimum
- Return and supply measurement locations.
- Runtime conditions at time of measurement.
- Calculated Delta-T value.
- Relative airflow notes by room/register.
- Final classification: Pass / Monitor / Escalate.
