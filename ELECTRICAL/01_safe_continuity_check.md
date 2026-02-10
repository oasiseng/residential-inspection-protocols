# Protocol: Electrical Field Verification (Finished Home)

**Scope:** Verification of electrical rough-in and safety in a finished home (devices installed) where power is currently disconnected.  
**Goal:** Confirm absence of dead shorts and ground faults before energizing.  
**Tools Required:** Multimeter (Low Z preferred), Klein ET600 (optional, restricted use).

## 🛑 Safety Stop

- **Assume system is live** until proven otherwise.
- **Lockout/Tagout** main breaker if possible.
- **Do NOT** use insulation test (Megger) mode on main bus bars.

## Step 1: The “Impedance Map” (Multimeter Only)

Since light bulbs and electronics are installed, use resistance values to distinguish loads from faults.

### A. Setup

1. **Main breaker:** OFF.
2. **Branch breakers:** ON.
3. **Meter setting:** Resistance (Ω).

### B. The Sweep

Measure resistance at the main lugs/breaker:

| Test Points | Expected Reading | Interpretation | Action |
| :--- | :--- | :--- | :--- |
| **Line A to Ground** | **OL (Open Loop)** | ✅ Safe. Insulation intact. | If < 1kΩ, stop and find fault. |
| **Line B to Ground** | **OL (Open Loop)** | ✅ Safe. Insulation intact. | If < 1kΩ, stop and find fault. |
| **Neutral to Ground** | **OL (Open Loop)** | ⚠️ Conditional | See Step C below. |
| **Line to Neutral** | **5Ω - 500Ω** | ✅ Load detected. | Normal for finished homes. |
| **Line to Neutral** | **< 1.0Ω** | ❌ Dead short. | **Do not energize.** |

### C. Neutral-Ground Bond Check

In a main service panel, neutral and ground are bonded. Isolate to test.

1. Select a sample circuit.
2. **Disconnect** the white neutral wire from the bus bar.
3. Measure **neutral wire** to **ground bar**.
4. **Result:** Must be **OL**.
   - If continuity beeps: the neutral is touching ground in a receptacle box (common rough-in error). This often trips AFCI/GFCI breakers instantly.

## Step 2: Spot-Check Insulation (Optional)

**Only** for dedicated lines where you can visually verify disconnection.

- **Candidates:** HVAC compressor, water heater, range.
- **Procedure:**
  1. Physically disconnect wires at the appliance.
  2. Megger at 500V (line-ground).
  3. **Pass criteria:** > 50 MΩ.
  4. Reconnect immediately.

## Step 3: Controlled Energization

1. Turn **all** breakers OFF.
2. Turn **main breaker** ON.
3. Energize one circuit at a time.
   - **Listen:** For pop or hum.
   - **Verify:** Check voltage at one outlet on that circuit.
