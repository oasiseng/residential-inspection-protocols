# Protocol 202: Electrical 1st Rough — Construction Phase Rough-In Inspection

> **Inspection Type:** Electrical — Rough-In (Pre-Drywall)
> **Version:** 1.0
> **Jurisdiction Basis:** Florida Building Code (FBC), 8th Edition — Electrical Volume; NEC 2023 (as adopted by Florida)
> **Author/Reviewer:** [Oasis Engineering]
> **Revision Date:** 2026-03-24

---

## 1) Scope

Pre-drywall inspection of the electrical rough-in system for single-family residential new construction. This protocol covers the inspection window **after framing is complete and all electrical wiring, boxes, and conduit are installed through the framing, but before drywall enclosure**.

### In Scope
- All branch circuit conductors (NM-B, UF-B, THHN/THWN in conduit) installed within framing.
- All electrical outlet boxes, switch boxes, and device boxes secured and properly positioned.
- Wire gauge, circuit assignments, and dedicated circuit requirements per NEC 210 and approved plans.
- Receptacle layout compliance (NEC 210.52).
- GFCI and AFCI protective device locations (NEC 210.8 and 210.12).
- Electrical panel location, main service sizing, and branch breaker assignments.
- Smoke and carbon monoxide detector locations (hard-wired circuits).
- Grounding electrode system and bonding (reference [Protocol 200](./200_footer_bond_inspection.md) for Ufer ground).
- Conduit fill, support, and installation where applicable.

### Out of Scope
- Final receptacle/switch device installation (occurs after drywall).
- Concealed wiring or boxes after drywall closure.
- Post-construction testing (continuity, insulation resistance, load testing).
- Final panel labeling or circuit directory completion.

---

## 2) Objective

Determine whether the electrical rough-in is ready for drywall coverage by verifying:
- **PASS:** All wiring, boxes, and circuit assignments meet approved plans and NEC standards.
- **HOLD:** Minor corrections needed before drywall authorization.
- **FAIL / STOP WORK:** Critical deficiencies requiring rework or redesign.

Once drywall is installed, verification of concealed wiring is not possible. This is the final inspection window for the branch circuit distribution system.

---

## 3) Code & Standard Basis

### Required (Code)
| Reference | Section | Requirement |
|---|---|---|
| NEC 2023 (FL adopted) | 210.8 | GFCI protection required locations |
| NEC 2023 (FL adopted) | 210.12 | AFCI protection for dwelling unit circuits |
| NEC 2023 (FL adopted) | 210.52 | Receptacle outlet spacing and location requirements |
| NEC 2023 (FL adopted) | 210.4(A) | Multiwire branch circuit rules |
| NEC 2023 (FL adopted) | 240.4(D) | Overcurrent protection for small conductors |
| NEC 2023 (FL adopted) | 250 (all) | Grounding and bonding requirements |
| NEC 2023 (FL adopted) | 300.3(B) | Conductors of same circuit must be grouped together |
| NEC 2023 (FL adopted) | 310.15(C) | Ampacity derating for bundled conductors |
| NEC 2023 (FL adopted) | 314.16 | Outlet box fill calculations |
| NEC 2023 (FL adopted) | 314.27(C) | Support requirements for ceiling-mounted equipment (fans) |
| NEC 2023 (FL adopted) | 334.30 | Securing and support of NM cable |
| FBC-R (8th Ed.) | R314 | Smoke and carbon monoxide detectors (hard-wired with battery backup) |
| FBC-R (8th Ed.) | Chapter 27 | Electrical system (references NEC as adopted) |

### Guidance (Standards)
| Reference | Use |
|---|---|
| NFPA 70 (NEC) | Complete electrical installation standard |
| NFPA 72 | National Fire Alarm Code (smoke/CO detector interconnection) |
| UL 413 | Safety standard for construction and industrial wiring systems |
| UL 498 | Attachment plugs and receptacles |

---

## 4) Tools Required

| Tool | Minimum Spec | Notes |
|---|---|---|
| Tape measure | 25 ft, 1/16 in. graduations | For receptacle height, spacing, and cable support intervals |
| Outlet box fill reference card | NEC Table 314.16(A) | For box fill calculations |
| Wire gauge caliper / micrometer | Reads #6–#14 AWG | Verify conductor size |
| Approved electrical plans (sealed set) | Current revision | Must match permit set on file |
| Circuit schedule / load calculation | From structural EOR | Verify circuit amperage and wire gauge matching |
| Camera with timestamp | Date/time/GPS | All photos must include scale reference and context |
| Voltage tester (non-contact) | CAT III rated | For safety verification (main should be de-energized during rough-in) |
| Field notebook / inspection form | — | Record all measurements and observations |
| Magnifying glass or loop | 10x magnification | Read wire markings and bar deformations |

---

## 5) Safety + Non-Destructive Limits

- **Energized panels:** Do not inspect energized electrical panels or service equipment. The main service disconnect should be OFF during rough-in inspection.
- **Do not** cut, strip, or probe conductors to "test" insulation or continuity.
- **Do not** move wires or boxes to reposition them without contractor authorization.
- **Do not** pull on or stress NM cable runs to check security.
- **Working heights:** Use appropriate fall protection if accessing ceiling boxes or second-floor wiring above 6 ft.
- **Stop condition:** If the main panel is energized before rough-in sign-off, or if evidence of unauthorized modifications is present — STOP and notify the contractor and electrical inspector.

---

## 6) Preconditions

- [ ] Approved electrical plans (sealed) are on-site and match the permit set.
- [ ] Framing is complete and inspected by structural.
- [ ] All rough-in wiring, boxes, and conduit are installed.
- [ ] Main service panel is not yet energized (or is de-energized for inspection).
- [ ] Contractor confirms the rough-in is complete and ready for inspection.
- [ ] Site has adequate lighting for visual inspection.
- [ ] Drywall installation has not yet begun.

---

## 7) Procedure Steps

### Step 1: Verify Electrical Plans and Service Sizing

1. Obtain the approved electrical plans (sealed set) and confirm current revision.
2. Verify the main service **amperage rating**:
   - Single-family residential typical: 100 A (minimum per NEC 230.42(C)(1)), 150 A, or 200 A.
   - Verify against plans and that the main breaker matches the service entrance conductor size.
3. Check the **service entrance conductor size** (main lugs in panel):
   - Service conductor must be sized per main breaker amperage (NEC 240.4).
   - Typical: 100 A = 2/0 Al, 150 A = 1/0 Al or #2 Cu, 200 A = 4/0 Al or #2/0 Cu.
4. Verify the **panel location** matches plans:
   - Accessible, not in bathrooms or hazardous locations.
   - Proper clearance: 30 in. wide × 36 in. deep × 78 in. high working clearance (NEC 110.26).
5. Confirm the **grounding electrode system** is in place (see [Protocol 200](./200_footer_bond_inspection.md) for Ufer ground connection to rebar).

### Step 2: Verify Dedicated Circuit Requirements

Verify all **required dedicated circuits** are installed per NEC 210.11 and 210.52:

1. **Kitchen countertop:** (2) separate 20 A circuits minimum, each serving only countertop receptacles.
   - Verify two dedicated 20 A breakers with #12 AWG conductors (NEC 210.11(C)(1)(i)).
2. **Laundry:** dedicated 20 A circuit for washer location.
   - Single 20 A breaker, #12 AWG (NEC 210.11(C)(2)).
3. **Bathroom:** dedicated 20 A circuit for bathroom receptacles (one circuit per bathroom minimum; larger homes may have multiple).
   - #12 AWG, 20 A breaker (NEC 210.11(C)(3)).
4. **Garage:** at least one 20 A circuit for garage receptacles (in addition to door opener circuit if ceiling-mounted).
   - #12 AWG, 20 A breaker.
5. **HVAC equipment:** dedicated 240 V circuit (sizing per equipment nameplate, typically 15–30 A).
   - Verify breaker and conductor size match HVAC equipment requirements.
6. **Water heater:** dedicated 240 V circuit (sizing per equipment nameplate, typically 20–30 A).
   - Verify breaker size and conductor gauge.
7. **Range / Built-in oven:** dedicated 240 V circuit (typically 40–50 A, #8 or #6 AWG).
   - Verify against equipment nameplate and plans.
8. **Dishwasher:** dedicated 20 A, 120 V circuit.
   - #12 AWG (can share general-purpose circuit per some interpretations, but verify against plans).
9. **Garbage disposal:** dedicated 15–20 A, 120 V circuit.
   - #14 AWG (15 A) or #12 AWG (20 A).
10. **Exterior circuits:** dedicated 20 A circuits for outdoor receptacles (front and back; 210.52(E)).

### Step 3: Verify Wire Gauge and Ampacity

For **every visible branch circuit**, verify that the wire gauge matches the circuit amperage per NEC 240.4(D):

| Amperage | Wire Gauge (Cu.) | Wire Gauge (Al.) |
|---|---|---|
| 15 A | #14 AWG | #12 AWG |
| 20 A | #12 AWG | #10 AWG |
| 30 A | #10 AWG | #8 AWG |
| 40 A | #8 AWG | #6 AWG |
| 50 A | #6 AWG | #4 AWG |

**Action:** Trace each circuit from the panel to the first outlet/box, note the breaker amperage, and verify the conductor size matches the table above.

**Bundling / derating:** If more than 3 current-carrying conductors are bundled together in the same run, apply **ambient temperature and bundling derating** per NEC 310.15(C). Most NM cable bundles in residential are not heavily bundled, but if a conduit contains multiple circuits, verify derating was applied in the load calculation.

### Step 4: Verify Box Placement, Security, and Fill

1. **Outlet and switch box locations:**
   - Verify boxes are **properly secured to studs** — not loose or floating.
   - Boxes must be set at the **correct depth** for the finish material (typically 1/2 in. drywall = box sticks out ~1/2 in. from the stud face).
   - Rough-in template or standard depths: receptacles 12–18 in. above finished floor (AFF), switches 48 in. AFF (verify against plans).

2. **Box fill calculation** per NEC 314.16:
   - Count each **conductor** = 1 volume unit per NEC 314.16(B)(1).
   - Each **clamp or support** = 1 volume unit (NEC 314.16(B)(4)).
   - Each **device** (receptacle, switch) = 2 volume units (NEC 314.16(B)(5)).
   - Each **equipment grounding conductor** = 1 volume unit (NEC 314.16(B)(1)).
   - Add up total units and compare to the box volume (marked on the box, typically 18–25 cu. in. for standard 2×4 boxes).
   - **Red flag:** Overfilled boxes (exceeding rated volume) are a fire hazard and code violation.

   **Example:** A standard outlet box with (1) two-wire NM cable entering, (1) receptacle device, (1) ground wire = 1 + 1 + 1 + 2 (device) + 1 (ground) = 6 volume units. If the box is 18 cu. in., 6 units at ~2.25 cu. in. per unit = ~13.5 cu. in. used (well within limits).

3. **Weatherproof boxes:**
   - Any boxes on the exterior must be **weatherproof, listed boxes** with gaskets.
   - Verify boxes for exterior receptacles (front, back) and any outdoor equipment.

4. **Ceiling fan boxes:**
   - If a ceiling fan location is specified in plans, verify a **fan-rated box** is installed.
   - Standard octagon or rectangular boxes are **NOT rated for fan support**.
   - A ceiling fan box must be **specifically listed for fan support** per NEC 314.27(C) and must have dynamic support rating (typically 35 lbs or higher).
   - Verify the box is rated in the plans and/or contractor documentation.

### Step 5: Verify NM Cable Support and Securing (NEC 334.30)

NM cable securing requirements are among the most commonly missed in the field:

1. **Within 12 inches of every box:**
   - NM cable must be **stapled or clamped within 12 inches of every outlet or junction box** (NEC 334.30(A)).
   - Measure the distance from the box to the first staple/clamp. If >12 in., it's a deficiency.

2. **At intervals not exceeding 4.5 feet:**
   - In addition to the 12 in. requirement, cable must be secured at intervals not exceeding 4.5 feet.
   - Walk the cable runs and verify staples/clamps are placed at consistent intervals (typically 36 in. is conservative).

3. **No damaged insulation:**
   - Inspect all visible NM cable for cuts, abrasion, or insulation damage.
   - Cable should not contact sharp edges or corners without a **bushing or protective sleeve** (NEC 300.4).

4. **Cable routing:**
   - NM cable must not be run across the top of joists in attics (must be run through holes in joists or along the face of joists with support).
   - Cable must not be run through or across concrete or masonry without conduit protection.
   - Cable run through framing must maintain 1.25 in. clearance from edges, or have a protective bushing if closer (NEC 300.4).

### Step 6: Verify Receptacle Outlet Requirements (NEC 210.52)

1. **General wall receptacles:**
   - No point along any wall space may be more than 6 ft from a receptacle (i.e., receptacles every 12 ft).
   - Measure wall spaces and verify receptacle spacing.
   - Living areas (bedrooms, living room, dining room) require this spacing; garages and basements follow the same rule.

2. **Kitchen countertop receptacles** (NEC 210.52(C)):
   - At least one receptacle within 24 in. of **each end** of the countertop.
   - No point along the countertop more than 24 in. from a receptacle.
   - Receptacles above a sink or stove are not permitted (except as needed for specific appliances).
   - Verify island and peninsula countertops have receptacles (at least one per island/peninsula).

3. **Bathroom receptacles** (NEC 210.52(D)):
   - At least one receptacle within 36 in. of the **outside edge of each basin** (sink).
   - Receptacle must be supplied by a dedicated 20 A circuit.

4. **Laundry room receptacle** (NEC 210.52(F)):
   - Dedicated 20 A receptacle within 6 ft of the washer location (or as specified in plans).

5. **Garage receptacles** (NEC 210.52(G)):
   - At least one receptacle accessible in the garage (in addition to door opener circuit if present).
   - Verify location is accessible and not behind equipment.

6. **Outdoor receptacles** (NEC 210.52(E)):
   - At least one receptacle on the **front** of the dwelling.
   - At least one receptacle on the **back** (or side) of the dwelling.
   - Receptacles must be no more than 6.5 ft above grade.

### Step 7: Verify GFCI Protection Locations (NEC 210.8)

GFCI protection is required in many more locations than "kitchen and bathroom." Verify all **required GFCI locations** have protection:

1. **Bathrooms:** All receptacles (NEC 210.8(A)(1)).
2. **Kitchens:** All receptacles serving countertops (NEC 210.8(A)(2)).
3. **Garages:** All receptacles, including dedicated circuits (NEC 210.8(A)(3)).
4. **Outdoor areas:** All receptacles (NEC 210.8(A)(5)).
5. **Crawlspaces:** Receptacles in crawlspaces at or below grade (NEC 210.8(A)(4)).
6. **Unfinished basements:** All receptacles (NEC 210.8(A)(6)).
7. **Laundry rooms:** Receptacles within 6 ft of a sink (NEC 210.8(A)(11)).
8. **Wet bar sinks and other sinks:** If not in a kitchen (NEC 210.8(A)(8)).
9. **Boathouses:** All receptacles (NEC 210.8(A)(9)).

**Method of protection:**
- GFCI can be at the **receptacle outlet** (GFCI receptacle) or upstream at a **GFCI breaker** in the panel.
- If GFCI breaker is used, all downstream receptacles on that circuit are protected.
- Verify that protection is **present and listed** (not future or promised).

### Step 8: Verify AFCI Protection (NEC 210.12)

**AFCI (Arc-Fault Circuit Interrupter) protection** is required for virtually all habitable room circuits in Florida residential:

1. **Required locations** (NEC 210.12):
   - Bedrooms (all circuits)
   - Living rooms
   - Dining rooms
   - Family rooms
   - Dens
   - Hallways
   - Closets
   - Sunrooms (heated/cooled)
   - Recreation rooms
   - Essentially all circuits in all **habitable rooms**

2. **Not required:**
   - Garage circuits
   - Laundry room circuits
   - Bathroom circuits (though GFCI is required)
   - Circuits to fixed appliances (range, dryer, water heater) — though branch circuits in those rooms still need AFCI

3. **Method of protection:**
   - AFCI protection is typically provided by **combination AFCI breakers** in the panel (not AFCI receptacles for branch circuits in residential).
   - Verify breakers in the panel are **labeled AFCI** or **CAFCI** (combination).

4. **Common Florida error:**
   - Many contractors mistakenly believe AFCI is only required in bedrooms (old code).
   - Current NEC (as adopted by Florida) requires AFCI in all habitable rooms.
   - Verify the panel schedule and breaker lineup; breakers should be marked AFCI/CAFCI for most 15/20 A circuits.

### Step 9: Verify Smoke and CO Detector Hard-Wired Circuits

1. **Smoke detectors** (FBC-R R314 / NFPA 72):
   - Hard-wired smoke detectors required in each **bedroom**, **outside each sleeping area** (in hallway), and **each level** of the dwelling.
   - Must have **battery backup**.
   - Must be **interconnected** (so one detector triggers all).
   - Verify dedicated circuit or shared circuit is routed to all detector locations.
   - Boxes must be rated for smoke detector mounting.

2. **Carbon monoxide detectors** (FBC-R R315):
   - Required if the home has fuel-burning appliances (gas furnace, gas water heater, fireplace) or an **attached garage**.
   - Must be hard-wired with battery backup.
   - Typically installed at entry points from garages or near bedrooms.
   - Verify dedicated or shared circuit is routed to all CO detector locations.

3. **Circuit specification:**
   - Smoke/CO detectors are typically fed from a dedicated 15 A or 20 A circuit.
   - Boxes must be properly sized for the detector terminals.

### Step 10: Verify Panel and Service Configuration

1. **Main breaker sizing:**
   - Verify the main breaker amperage matches the service size (100 A, 150 A, 200 A).
   - Breaker must not be oversized relative to service entrance conductor size.

2. **Branch breaker assignment:**
   - Verify **every breaker slot** in the panel is labeled or scheduled with the circuit assignment (room/area and amperage).
   - Double-check high-amperage breakers (240 V, 40–50 A) are for the correct appliances (range, water heater, HVAC).

3. **Grounding and bonding:**
   - Main bonding jumper must be present and sized per NEC 250.28 (typically #2 Cu or equivalent for 200 A service).
   - Verify **neutral and ground bars** are properly installed in the panel (neutral bar bonded to ground bar at main disconnect only).
   - Water pipe bonding and gas pipe bonding: verify bonding conductors from the main panel ground/neutral bus to water meter and (if applicable) gas meter.

4. **Clearance and accessibility:**
   - Verify the panel has **30 in. width × 36 in. depth × 78 in. height working clearance** (NEC 110.26).
   - Verify the panel is not located in a bathroom, hazardous location, or concealed space.

### Step 11: Verify Conduit Installation (where applicable)

If the plans specify conduit for any portions of the rough-in:

1. **Proper fill ratio:**
   - Conduit fill is limited per NEC Chapter 9, Table 1:
     - **1 conductor:** 53% fill
     - **2 conductors:** 31% fill
     - **3+ conductors:** 40% fill
   - Verify the number of conductors in each conduit run does not exceed maximum fill.

2. **Proper connectors and supports:**
   - Conduit must be secured at supports every 3 ft (NEC 344.30(A)).
   - Transition from conduit to NM cable (or vice versa) must use appropriate fittings (conduit body with bushing, not just a splice).

3. **Expansion fittings:**
   - If conduit is exposed to temperature extremes (attic runs), expansion fittings may be required per equipment manufacturer specs and NEC 342.44.

### Step 12: Final Walkthrough and Documentation

1. Walk the entire home and verify all rough-in elements are in place:
   - Branch circuits from panel to each room.
   - All dedicated circuits installed.
   - All required receptacles, switches, and boxes.
   - All GFCI and AFCI protections accounted for.
   - Smoke and CO detector circuits routed.

2. Photograph:
   - Overall panel with breaker lineup visible.
   - Panel interior (door open) showing main breaker and grounding/bonding.
   - Representative branch circuit runs in framing (attic, basement, wall cavities).
   - Kitchen counter receptacle layout (spacing verification).
   - Bathroom receptacle locations.
   - Exterior receptacle boxes (front and back).
   - Garage receptacle and door opener circuits.
   - NM cable securing/stapling (close-up showing 12 in. proximity to box and 4.5 ft intervals).
   - Ceiling fan box (if present) showing fan-rated listing.
   - Smoke and CO detector box locations.
   - Any deficiencies with close-up and context.

3. Record all observations on the field inspection form.

---

## 8) Interpretation Criteria

| Result | Condition |
|---|---|
| **PASS** | All circuits installed per plans, wire gauge matches amperage, dedicated circuits present, receptacle layout complies with NEC 210.52, GFCI and AFCI protection locations identified, NM cable properly secured (12 in. and 4.5 ft), box fill acceptable, all required boxes present and secured, smoke/CO circuits routed, panel and service sizing correct |
| **HOLD** | Minor deficiency correctable before drywall (e.g., missing staple on cable run, one receptacle out of position, box not fully secured but repositionable) |
| **FAIL** | Wrong wire gauge for circuit amperage, missing dedicated circuits, GFCI/AFCI protection not present at required locations, overfilled boxes, ceiling fan on standard box, damaged insulation, panel breakers not labeled, grounding/bonding missing, smoke/CO circuits not routed |

---

## 9) What AI Gets Wrong

1. **Undercounts box fill.** AI frequently miscalculates box fill by forgetting to add the volume for clamps, equipment grounding conductors, and devices. The most common error is not adding 2 volume units per device; a 2-gang box with 2 switches and a shared neutral is often miscalculated as "4 wires" when it's actually 6–7 volume units. Over-filled boxes are a fire hazard and code violation.

2. **Misses AFCI requirements for habitable rooms.** Many AI responses default to old code that required AFCI only in bedrooms. Current NEC (as adopted by Florida) requires AFCI protection in all habitable rooms (bedrooms, living rooms, dining rooms, family rooms, dens, hallways, closets, sunrooms, recreation rooms). AI frequently undercounts required AFCI breakers.

3. **Gets NM cable support wrong.** AI often says "staple every 4 feet" but omits the critical 12-inch requirement from every box. The correct rule is: **within 12 inches of every box AND at intervals not exceeding 4.5 feet**. Missing the box-proximity staple is the most common deficiency in the field and the one AI most frequently misses.

4. **Treats ceiling fan boxes as standard boxes.** A box supporting a ceiling fan must be specifically **listed for fan support** per NEC 314.27(C) and have a dynamic load rating (typically 35 lbs or higher). Standard octagon or rectangular boxes are not rated for the dynamic loading of a spinning fan and will fail. AI rarely flags this critical deficiency.

5. **Oversimplifies GFCI locations.** AI lists "kitchen and bathroom" but misses garage, outdoor, crawlspace, unfinished basement, laundry (within 6 ft of sink), boathouses, and other required locations under NEC 210.8. The GFCI location list has significantly expanded in recent NEC editions, and AI commonly undercounts required GFCI protections.

---

## 10) Documentation Minimum

- [ ] Project address, permit number, date, time, weather conditions.
- [ ] Name and PE license number (or electrical inspector ID) of inspecting engineer.
- [ ] Plan sheet reference (electrical plan revision and date).
- [ ] Service amperage rating and main breaker size.
- [ ] Service entrance conductor size (main lugs).
- [ ] Panel location and working clearance verification.
- [ ] Grounding electrode system connection verification ([Protocol 200](./200_footer_bond_inspection.md)).
- [ ] Bonding (water pipe, gas pipe) confirmation.
- [ ] Dedicated circuit checklist: kitchen (2×20A), laundry (20A), bathroom (20A per bathroom), garage (20A), HVAC, water heater, range, dishwasher, disposal.
- [ ] Wire gauge verification for all visible branch circuits (spot-check minimum 10 circuits).
- [ ] NM cable securing verification (12 in. from boxes, 4.5 ft intervals) — spot-check minimum 5 runs.
- [ ] Receptacle layout verification per NEC 210.52 (general spacing, kitchen countertop, bathroom, laundry, garage, outdoor).
- [ ] GFCI location checklist: bathroom, kitchen, garage, outdoor, crawlspace, basement, laundry, other wet locations.
- [ ] AFCI protection locations (breaker lineup in panel).
- [ ] Smoke and CO detector circuits (box locations noted).
- [ ] Ceiling fan box verification (if applicable) — note fan-rated listing.
- [ ] Box fill spot-check calculations (minimum 3 boxes).
- [ ] Deficiency list (if any) with required corrective actions.
- [ ] Photo set with scale reference (minimum 15–20 photos per inspection).
- [ ] Final disposition: PASS / HOLD / FAIL with inspector signature.
- [ ] Limitations statement: "This inspection is limited to visual observation of accessible rough-in conditions before drywall enclosure. Concealed conditions after drywall are excluded from scope."

---

## 11) Escalation Path

| Trigger | Action |
|---|---|
| Wire gauge does not match circuit amperage (e.g., #14 AWG on 20A breaker) | Fail → require rewiring of affected circuit |
| Missing dedicated circuit (kitchen, laundry, bathroom, appliance) | Fail → require installation before proceeding |
| GFCI protection not present at required location | Hold → require GFCI receptacle or breaker installation |
| AFCI protection missing for habitable room circuits | Hold → require AFCI breaker installation in panel |
| Overfilled outlet box (exceeds rated volume) | Hold → require box replacement or conductor/device relocation |
| Ceiling fan on standard (non-fan-rated) box | Fail → require replacement with fan-rated box |
| NM cable damaged or run without bushing at sharp edge | Hold → require sleeve/bushing installation or cable relocation |
| NM cable not secured within 12 in. of box or exceeds 4.5 ft intervals | Hold → require additional staples/clamps |
| Smoke or CO detector circuits not routed to planned locations | Hold → require circuit installation |
| Panel working clearance inadequate (<30 in. width, <36 in. depth, <78 in. height) | Fail → requires panel relocation or service redesign |
| Main bonding jumper missing or improperly sized | Fail → require bonding conductor installation per NEC 250.28 |
| Service entrance conductor size does not match main breaker | Fail → notify EOR for service redesign |

---

## Field Photo Checklist

Use this shot list for consistent documentation:

1. **Panel wide shot** — entire panel door and surroundings showing location and clearance.
2. **Panel interior — breaker lineup** — open door showing all breakers, main breaker, and labels (or lack thereof).
3. **Grounding and bonding detail** — main bonding jumper, ground bar, neutral bar, bonding conductors to water/gas meters.
4. **Service entrance conductors** — main lugs showing conductor sizing and termination.
5. **Kitchen counter layout** — overhead or angled shot showing receptacle spacing along counters.
6. **Kitchen dedicated circuits** — close-up of breaker box showing (2) 20A breakers labeled for kitchen.
7. **Bathroom receptacle** — showing location relative to sink basin (verify within 36 in.).
8. **Laundry dedicated circuit** — receptacle location relative to planned washer location.
9. **Garage receptacle and door opener** — showing circuits and accessibility.
10. **Outdoor receptacles** — front and back of house showing receptacle boxes and weatherproofing.
11. **NM cable securing near box** — tape measure showing distance from box to first staple/clamp (verify ≤12 in.).
12. **NM cable interval spacing** — tape measure showing distance between staples/clamps (verify ≤4.5 ft).
13. **Ceiling fan box** — close-up showing fan-rated listing on box label (if applicable).
14. **Smoke detector boxes** — location in bedroom and outside sleeping area.
15. **CO detector box** — location near garage entry or bedrooms (if required).
16. **Box fill verification** — close-up of an outlet or switch box showing conductors and fill (with count noted on form).
17. **Damaged or unsecured cable** — any deficiencies with clear identification and measurement.
18. **Overall home view** — property address, permit board, or context shot showing the home being inspected.
19. **Attic wiring runs** — representative cable runs showing routing and support.
20. **Basement or crawlspace wiring** — representative runs and GFCI locations (if applicable).
