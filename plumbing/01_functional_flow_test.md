# Protocol: Functional Flow Test (No Pressure Gauges)

## Scope
Non-destructive functional verification of residential domestic water performance in existing homes using fixture behavior only.

## Purpose
- Evaluate practical service performance under simultaneous demand.
- Screen for likely supply restrictions, valve failures, or distribution imbalance.
- Avoid invasive pressure testing methods that increase leak risk in older systems.

## Code Grounding (Performance Context)
- **IEBC Performance Compliance Methods (Chapter 14):** Focus on whether system function remains acceptable for intended use and safety.
- **IRC Existing Structures (R102.7):** Existing systems may remain when they perform safely; field assessment emphasizes operation and risk.

## Tools
- Stopwatch/timer
- Thermometer (optional for hot-water stability checks)
- Notepad/field form
- Camera

## Safety + Non-Destructive Limits
- Do **not** isolate and pressurize piping with air/water for hydrostatic testing in finished occupied homes.
- Do **not** force seized valves.
- Stop test if active leakage develops at stops, supplies, or fixture connections.

## Step 1: Pre-Test Walkthrough
1. Confirm water service is on and ask occupants about known weak fixtures.
2. Visually inspect accessible angle stops, supply lines, and fixture bases for existing leaks.
3. Establish baseline flow at a lavatory faucet (subjective steady stream check).

## Step 2: The Three Fixture Drill
Run all three in sequence and then simultaneously:

1. **Shower ON** at typical use setting.
2. **Flush toilet** nearest that bathroom group.
3. **Open sink faucet** (same bathroom or adjacent branch) and observe:
   - Flow drop severity.
   - Pressure recovery time after toilet refill cycle.
   - Temperature stability (if mixed/hot water in use).

Repeat in a second plumbing zone if the house has multiple branches/floors.

## Step 3: Performance Interpretation
- **Pass (Functional):** Temporary reduction with quick recovery; no abnormal noise; no leakage triggered.
- **Monitor:** Noticeable but tolerable drop, slow recovery, intermittent fluctuation.
- **Escalate:** Severe drop to trickle, prolonged recovery, repeated hammer/chatter, or leak initiation during test.

## Step 4: Ancillary Checks (Non-Destructive)
- Operate highest and lowest fixtures to screen for distribution imbalance.
- Observe water heater area for pressure/temperature relief discharge signs.
- Note aerator clog indicators (localized low flow vs. house-wide deficiency).

## What AI Gets Wrong
- **Unsafe hydrostatic advice:** AI often recommends shutting water off and pumping air/water into legacy lines—this can trigger leaks at aged angle stops and brittle seals.
- **Over-diagnosis from one symptom:** AI may call low flow a “main failure” without fixture-by-fixture functional testing.
- **Ignores occupancy risk:** Generic guidance may not account for liability from inducing leaks in finished spaces.

## Documentation Minimum
- Fixtures tested and sequence used.
- Observed flow behavior and recovery timing.
- Leak/no-leak result during demand condition.
- Final classification: Pass / Monitor / Escalate.
