# RestoKit Unified Field Knowledge Base
**Version:** 1.0  
**Last Updated:** 2026-06-09  
**Purpose:** Single coherent source of truth for RestoKit voice AI and field reference. All decision logic is expressed as **connected reasoning** (the "why" graph) rather than isolated rules. Every section is designed for quick hopping via clear keys and anchors. Nothing from the source files is lost — all practical field reasoning, voice prompts, red flags, working rules, and cross-connections are preserved and synthesized.

---

## How to Use This Document

- **Quick hopping**: Search for `[Key: something]` or use the Table of Contents anchors.
- **Voice mode (Tech / Field)**: Read the **Voice Prompt** and **Decision Logic** boxes. Focus on what to say and the immediate branching.
- **Deep mode**: Read the **Reasoning** sections for the full "why" graph — how one decision affects downstream risk, cost, callbacks, and liability.
- **Graph thinking**: Decision points are written as connected logic (e.g., "If X then Y because Z, which then raises the probability of A in Phase 3").

This document turns the modular source files into one navigable operational graph while keeping the raw practical power of the original field notes.

---

## Table of Contents (Quick Hop Keys)

1. [Core Philosophy & Invariants](#core-philosophy--invariants)
2. [Job Flow Overview — The High-Level Graph](#job-flow-overview--the-high-level-graph)
3. [Phase 1: Initial Assessment](#phase-1-initial-assessment)
4. [Phase 2: Engineering Controls & Containment](#phase-2-engineering-controls--containment)
5. [Phase 3: Water Extraction](#phase-3-water-extraction)
6. [Phase 4: Structural Drying & Monitoring](#phase-4-structural-drying--monitoring)
7. [Phase 5: Contents Handling & Restoration](#phase-5-contents-handling--restoration)
8. [Special Cases & High-Risk Logic](#special-cases--high-risk-logic)
9. [Final Verification & Closeout](#final-verification--closeout)
10. [Equipment Logic & Sizing](#equipment-logic--sizing)
11. [Material Science Quick Reference](#material-science-quick-reference)
12. [Cross-Cutting Decision Graphs](#cross-cutting-decision-graphs)
13. [Voice Style & Communication Notes](#voice-style--communication-notes)

---

## Core Philosophy & Invariants

**Primary Goal**: Return the structure and contents to a stable, pre-loss condition (or better) while protecting people, minimizing secondary damage, and creating defensible documentation.

**Non-Negotiable Invariants** (these tie every decision together):

- **Safety hierarchy**: Engineering controls > Administrative > PPE. Never rely on PPE alone when engineering controls can be applied.
- **Source first, always**: Stop the water, verify it is stopped, then extract. Containment is important but secondary to stopping migration.
- **Hidden problems are the norm**: Cause of loss is frequently behind walls, under floors, or in cavities. Assume nothing from visible water alone.
- **Time is the enemy on contaminated water**: Category 2/3 + >48h dwell in warm conditions dramatically increases bacterial and mold risk. This single fact drives most removal vs drying decisions.
- **Documentation protects everyone**: Pre-existing conditions, scope changes, homeowner statements, and moisture trends must be captured before work begins and throughout. Photos + notes beat memory.
- **Realistic Day 1 scope**: Most emergency water losses are limited to signed authorization, source isolation, bulk extraction, basic containment, and drying setup. Full demo and detailed mapping usually happen Day 2 after equipment has run.
- **Over-promising destroys trust**: Be honest about what can realistically be dried vs what must be removed, especially on porous materials with time or contamination.

These invariants are the spine of the entire graph. Every later decision traces back to one or more of them.

---

## Job Flow Overview — The High-Level Graph

A typical job follows this connected sequence. Each phase feeds the next; shortcuts create downstream failures.

```
Arrival & Safety
    ↓
Signed Authorization (non-negotiable gate)
    ↓
Source Isolation + Verification
    ↓
Initial Assessment (Category + Class + Hidden Source Hunt + Pre-existing Documentation)
    ↓
Engineering Controls Decision (based on Category, mold risk, dwell time, red flags)
    ↓
Extraction (outer edges inward, protect paths first)
    ↓
Post-Extraction Re-assessment (moisture map update)
    ↓
Drying Setup (psychrometric baseline + goals + equipment placement)
    ↓
Active Monitoring & Adjustment Loop (daily until goals met)
    ↓
Final Verification (moisture + visual + structural + contents)
    ↓
Controlled Teardown + Customer Walkthrough + Documentation Package
    ↓
Closeout + Warranty Education
```

**Key branching logic that ties the graph**:
- If Category 3 or visible mold or strong musty odor → full containment + negative pressure + upgraded PPE **before** intrusive work.
- If >48h dwell on Category 2/3 in warm conditions → treat as higher risk for mold/bacteria → more aggressive removal and containment.
- If hidden moisture suspected (high readings in cavities, musty smell, previous failed drying) → open for inspection rather than heroic drying attempts.
- If electronics/appliances involved in fire + water → high corrosion risk → usually recommend replacement rather than cleaning.

---

## Phase 1: Initial Assessment

**[Key: initial-assessment]**

### Purpose
Quickly classify the loss, identify immediate hazards, determine realistic Day 1 scope, establish engineering control level, and document pre-existing conditions before any physical work.

### Non-Negotiable First Gate
**Signed work authorization** must be complete before touching anything — including shutting off water or moving equipment. This protects everyone and sets expectations.

### Core Reasoning Chain
1. **Safety walk (360 exterior + interior)**: Look for structural compromise, electrical hazards near water, downed lines, gas smells. If any life-safety issue → stop and escalate before entry.
2. **Customer interview as investigation**: When did it start? Claimed source? How long sitting? Previous water/mold? Occupant symptoms? These answers often reveal whether this is simple clean water or something more complex (internal leak vs storm, fast vs slow, hidden history).
3. **Source isolation + verification**: Shut off at angle stop or main. **Visually confirm** it stopped (e.g., hold flapper open on toilet supply failure). Never assume the valve worked.
4. **Hidden source hunting**: Cause of loss is frequently internal (supply line, appliance, drain) rather than obvious external. Use systematic moisture metering. Visible water is often not the origin.
5. **Category determination** (drives everything downstream):
   - **Category 1 (Clean)**: Sanitary source, clear, no odor. Lower containment/PPE usually sufficient. Still extract aggressively — clean water becomes dirty fast.
   - **Category 2 (Gray)**: Some contamination (appliances, showers, sinks). Elevated PPE and possible containment. Risk rises sharply after 24–48h.
   - **Category 3 (Black)**: Grossly contaminated or sewage. High risk. Full containment + negative pressure + upgraded PPE **before** intrusive work. Long dwell makes this worse.
6. **Class determination** (drives drying strategy):
   - Class 1: Minimal absorption — easy extraction + drying.
   - Class 2: Significant absorption into carpet/pad, some wicking into walls/cabinets (most common).
   - Class 3: Overhead water — high evaporation load, ceilings/upper walls/insulation involved.
   - Class 4: Dense materials or long-term saturation — specialty methods or removal often required.
7. **Pre-existing conditions documentation**: Photograph everything questionable **before** work. Note old stains, previous repairs, wear that doesn't match the current loss timeline. Homeowner statements about "it's been like that for years" must be captured.
8. **Red flag triggers** (immediate escalation):
   - Visible mold or strong musty/sewage odor
   - Sagging ceilings (stabilize with zip pole ASAP)
   - Standing water near electrical panels/outlets
   - Older home (pre-1980) with suspect materials → assume asbestos/lead until tested
   - Confined space or poor ventilation

### Realistic Day 1 Scope (Critical for Expectation Management)
On most emergency water losses, Day 1 is limited to:
- Signed paperwork + customer communication
- Source isolation + verification
- Bulk water extraction
- Basic containment (where it meaningfully reduces air volume)
- Drying equipment setup (air movers + dehumidifiers)

Full demo, detailed moisture mapping, and aggressive wall/ceiling removal usually happen on Day 2 after equipment has run 12–24 hours. Trying to do everything in one visit leads to poor decisions and cross-contamination.

**Voice Prompt (Field Tech)**: "Customer just signed. First things: verify water is actually off at the source, check for sagging ceilings that need immediate stabilization, lay floor protection before moving equipment, and classify category conservatively. What's your read on hidden source risk and how long it's been sitting?"

---

## Phase 2: Engineering Controls & Containment

**[Key: containment]**

### Core Reasoning
Containment prevents cross-contamination, protects unaffected areas, and controls airborne particulates/spores/odors. On Category 3, mold, or strong odor jobs it is non-negotiable **before** intrusive work. On clean Category 1 with good layout it can sometimes be lighter.

**Real-world field adjustment**: Extraction often happens before full poly containment on wet jobs because stopping water migration is priority #1 and wet plastic is miserable to work with. Quick floor protection + extraction first, then build proper barriers once the area is drier and safer.

### Decision Logic (Connected)
- **If Category 3 or visible mold or strong musty/sewage odor or confined space** → Full containment + negative pressure + HEPA scrubbing + upgraded PPE (Tyvek, respirator) **before** demo or heavy disturbance.
- **If Category 2 with dwell >24–48h or visible slime/mold risk** → Limited to full containment depending on layout and risk of migration.
- **If Category 1, no mold, good ventilation, limited affected area** → Basic floor protection + critical barriers at doorways/HVAC may be sufficient.
- Negative pressure target: -0.02 to -0.05 in. w.c. (higher for high-risk mold/Cat 3).
- Exhaust negative air to exterior, away from intakes and unaffected areas.
- Always protect HVAC registers inside containment.

### Setup Sequence (Practical Order)
1. Floor protection + corner guards in high-traffic unaffected paths (prevents tracking).
2. Extraction / bulk water removal (stop the spread).
3. Build vertical barriers (ZipWall or equivalent) floor-to-ceiling.
4. Seal all seams, penetrations, outlets, HVAC.
5. Create airlock/decon at entry if full containment required.
6. Set negative air machine + verify pressure and airflow direction.
7. Post signage and document with photos.

**Common failure mode**: Building full containment before extraction on wet jobs makes everything slower and messier. Prioritize stopping water first.

**Voice Prompt**: "Category 3 with some dwell time. We need full containment and negative pressure before we start opening walls. Confirm manometer reading and that exhaust is going outside."

---

## Phase 3: Water Extraction

**[Key: water-extraction]**

### Core Reasoning
Mechanical removal of liquid water is almost always better than trying to dry it in place. The more water you extract, the less work the drying equipment has to do and the lower the secondary damage risk (mold, warping, corrosion).

**Technique that ties to downstream success**:
- Work from **outer edges of visible wet area inward** toward heaviest saturation. Starting in the center pushes water into unaffected areas.
- Carpet wand near baseboards: Set wand at the wall and **pull outward** — never push toward the baseboard (the lip drives water under the baseboard into the wall cavity).
- Extract until water removal slows significantly on the last passes.

### Decision Logic
- **If standing water present** → Submersible pumps or wet vacs first.
- **If carpet/pad** → Aggressive wand extraction before deciding on pad removal. Pad is usually removed if saturated >24h or Category 2/3.
- **If Category 3 with dwell** → More aggressive material removal (cut higher than visible line — 12–18" above water line to interval of 2' minimum on walls) because bacteria and mold move fast behind finishes.
- Always maintain engineering controls during extraction on contaminated jobs. Extraction can aerosolize contaminants.

**Post-extraction handoff**: Re-scan with moisture meter, update map, confirm no standing water remains, then move to drying setup.

**Voice Prompt**: "Heavy standing water in a finished basement, Category 2. Start extraction from the edges working in. Pull the wand toward you at the walls. How much water are we seeing on the first few passes?"

---

## Phase 4: Structural Drying & Monitoring

**[Key: structural-drying]**

### Core Reasoning (Psychrometry in Plain Language)
Drying is about creating and maintaining a **vapor pressure gradient**. You want the air around the wet material to be drier (lower vapor pressure) than the moisture inside the material. Moisture moves from high to low until equilibrium.

- Air movers break the humid boundary layer and deliver moist air to the dehumidifier.
- Dehumidifiers remove moisture from the air (they don't magically pull it from walls).
- Without good directed airflow across wet surfaces, even powerful dehumidifiers have limited effect.
- Temperature matters: Warmer air holds more moisture. Too much heat without enough dehu capacity can slow drying.

### Drying Goals (Practical Targets)
Return affected materials to moisture levels consistent with **unaffected materials in the same environment** (equilibrium moisture content for that building and climate). Not "bone dry."

- Wood structural members: ~12–14% MC typical target.
- Drywall: Back to normal for that building (surface + probe where possible).
- Concrete slabs: To ambient equilibrium (they hold moisture longer).

**Document baseline readings in unaffected areas early** — this is your target, not a universal chart number.

### Equipment Placement Logic (Connected to Monitoring Success)
- Dehumidifiers: Centrally or pulling from wettest zone. Good clearance around intake/exhaust. Proper condensate routing.
- Air movers: Create directed flow across wet surfaces (walls, floors, ceilings). One per 10–14 linear feet of affected wall as starting rule. Angle to lift moisture without creating dead zones or excessive dust on contaminated jobs.
- Small closed rooms (bathrooms, closets): Often need their own dedicated dehumidifier.
- When two rooms become one air volume (wall removed), one properly sized dehu can sometimes handle both — but you can still use two for speed.

### Monitoring & Adjustment Loop (The Daily Walk)
Every monitoring visit:
1. Re-verify engineering controls are still intact and effective (hard gate on Category 2/3 or mold jobs).
2. Take consistent readings at the same fixed locations (temp, RH, GPP, material moisture).
3. Check dehumidifier performance (inlet vs outlet grains — healthy unit pulls 15–25 grains on active job).
4. Feel for proper airflow patterns and dead zones.
5. Analyze trend vs goals. Calculate daily drying rate.
6. Adjust only what the data justifies (reposition, add/remove capacity, investigate hidden moisture if readings stall or rise).
7. Document everything with photos.

**Pull equipment when**: Moisture readings stabilized in target range, 24h+ trend shows no rebound, no visible/olfactory signs of ongoing issues, hidden areas addressed.

**Common failure**: Assuming "it's been running for X days so it must be dry." Let the trend and multiple verification methods (meter + visual + smell + IR if available) tell you.

**Voice Prompt (Daily Monitoring)**: "Walk the job the same way every day. Start at the dehu — what's inlet vs outlet? Check every air mover is aimed correctly and running. Take readings in the exact same spots as Day 1. Any cold spots or new musty smells? Make at least one intentional adjustment based on what you see."

---

## Phase 5: Contents Handling & Restoration

**[Key: contents]**

### Core Reasoning
Contents work is often more emotionally charged than structural work. Homeowners remember how their stuff was handled. Good documentation and conservative decisions on contaminated porous items protect everyone.

### Decision Logic (Clean-in-Place vs Pack-Out vs Discard)
- **Clean-in-place preferred when**: Item not heavily damaged, can be cleaned effectively on site without cross-contamination risk, lower cost and disruption.
- **Pack-out when**: Heavy smoke/water/mold contamination, needs specialty cleaning/ozone/hydroxyl/controlled drying, risk of cross-contamination if left in structure. Common for clothing, documents, electronics, porous furniture, artwork.
- **Default bias on fire/smoke jobs**: Pack out more rather than less. Smoke penetrates deeper than most people realize.
- **Discard / aggressive trash on**: Heavily contaminated porous materials (fabric, particle board, insulation) especially after long dwell. Often cheaper and faster than cleaning with low success probability.

**Sort on-site first** before packing: Trash / Pack-out (worth sending to facility) / Clean-on-site. Work from least damaged to most damaged to avoid re-contaminating clean items.

**High-value / sentimental / electronics / documents**: Photograph before moving. These often need specialty vendors. Flag early.

**Security & chain of custody**: Numbered bins, master inventory, secure storage, homeowner sign-off when possible. Theft claims happen — good documentation reduces them dramatically.

**Voice Prompt**: "Heavy smoke from kitchen fire throughout the house. On fire jobs we default to packing out more rather than less because smoke is sneaky. What matters most to the homeowner? Let's photograph everything before we touch it."

---

## Special Cases & High-Risk Logic

**[Key: special-cases]**

### Fire & Smoke
- Smoke usually does more damage than the flames. Water from firefighters creates a combined fire + water problem (higher corrosion and mold risk).
- Protein (grease) smoke = sticky, yellowish, hard-to-clean, strong odor. Natural (wood/paper) smoke = drier, powdery, easier to clean.
- HVAC is a major distribution system for smoke. Assess early; often shut down until evaluated.
- Electronics/appliances after smoke + moisture = high hidden corrosion risk. Many fail weeks/months later even if they work initially. Be honest about replacement likelihood.
- Long dwell smoke (especially 3+ weeks with HVAC circulation) significantly increases likelihood that porous materials and drywall need removal rather than cleaning/sealing.

### Mold & Long-Dwell Contaminated Water
- Mold needs moisture + time + warmth + nutrients. Significant risk starts after ~24–48h in warm conditions.
- Category 3 + dwell >48h → treat as higher risk. Cut higher than visible damage. More aggressive removal.
- Hidden mold warning: Surface readings can look fine while the back side of drywall or insulation is covered. Probe or open when readings don't make sense or musty odor is present.
- Do not try to dry moldy materials in place in most cases. Source removal is cleaner and more defensible.

### HVAC Involvement
- HVAC moves air — and therefore moisture, spores, smoke, and odors.
- On water/mold jobs: Check if system was running during/after the event. Assume possible spread.
- On fire/smoke: Usually shut down until assessed. Smoke in ducts can linger and re-contaminate.
- Filters almost always replaced. Registers can often be cleaned. Ductwork and air handler/coils often need professional evaluation — heavy contamination frequently leads to replacement of flex duct or sections.

### Corrosion (Fire + Water)
- Acidic smoke residue + moisture = accelerated corrosion on metals and electronics.
- Fast extraction and drying helps but does not eliminate risk in hidden areas.
- Be upfront with homeowners/adjusters about replacement likelihood for electronics and appliances.

### Category 3 Long Dwell
- Two+ days sitting is often enough for significant bacterial and mold growth behind tile, in wall cavities, under flooring.
- Expect more aggressive demo. Cut higher. Wider containment. Higher PPE.

---

## Final Verification & Closeout

**[Key: final-verification]**

### Core Reasoning
Final verification is the last hard gate before declaring the job complete. It protects against callbacks from hidden moisture or secondary issues and creates the defensible documentation package.

### Sequence (Non-Negotiable Order)
1. Re-verify engineering controls are still intact (hard gate).
2. Final psychrometric and moisture readings at all the same fixed locations used throughout the job. Compare against drying goals set in drying-setup.
3. Structural and contents final inspection (inside cavities, under floors, behind appliances, hidden areas). Look for new staining, swelling, mold, or customer-reported issues.
4. Only after moisture verification and inspection pass → controlled teardown of containment and equipment.
5. Customer walkthrough: Show before/after photos, explain what was done, point out any remaining repair needs, educate on what normal vs warning signs look like.
6. Assemble complete documentation package (photos, moisture logs, equipment records, contents inventory, communications).
7. Review warranty terms (typically 30–90 days on drying work), provide clear follow-up recommendations, obtain sign-off, close job in system.

**If goals are not met**: Do not teardown. Return to monitoring/adjustment or escalate (add equipment, investigate hidden moisture, recommend removal).

**Voice Prompt**: "Final verification. Controls still solid? Take the exact same readings in the exact same spots. Are we at or below the targets we set? Any new musty smells or soft spots? Only after everything checks do we start taking things down."

---

## Equipment Logic & Sizing

**[Key: equipment]**

### Dehumidifier Sizing (Field Rules of Thumb)
- Class 1: ~1 pint per 50–60 sq ft
- Class 2: ~1 pint per 40–50 sq ft
- Class 3: ~1 pint per 25–35 sq ft
Round up. Size slightly high on Day 1 — easier to turn units off later than catch up.

Small closed rooms usually need their own dedicated unit.

### Air Mover Placement
- Directed flow across wet surfaces, not just circulating in the room.
- One per 10–14 linear feet of affected wall as starting point.
- Create wall of air or gentle vortex. Avoid short-circuiting (intake pulling directly from another mover's exhaust).
- Lower velocity often better for bound moisture in wood (better heat transfer, gradual gradient).

### Combined Volumes
When an interior wall is removed, two air volumes become one. One properly sized dehumidifier can handle the combined volume in many cases.

### Daily Performance Check
- Dehu: Inlet vs outlet grains (15–25 grain pull is healthy on active job).
- Airflow: Feel for dead zones and proper coverage at wet surfaces.
- If numbers aren't moving: Look at airflow first, then capacity, then hidden moisture sources.

---

## Material Science Quick Reference

**[Key: materials]**

- **Drywall**: Paper facing wicks fast and is mold food. Core softens when saturated. Usually cut out if soft, moldy, or wet >48h in warm conditions.
- **Wood framing**: More forgiving than finished hardwood. Can often be dried if caught early. Check for swelling, checking, hidden moisture in checks.
- **Hardwood floors**: Cupping/swelling = high risk. Long-term saturation or significant cupping often leads to replacement.
- **Particle board / MDF cabinets**: Swell and disintegrate when wet. Almost never worth saving once swollen.
- **Insulation**: Fiberglass and cellulose — usually remove when wet (especially Cat 2/3 or mold). Closed-cell spray foam has better survival chance.
- **Carpet & pad**: Pad is usually removed if truly wet. Carpet can sometimes be cleaned/dried if addressed quickly.
- **LVP / Sheet vinyl**: Creates vapor barrier. Water gets underneath easily. Lifting edges or removal often required for proper drying on contaminated jobs.
- **Concrete**: Absorbs and releases slowly. Good airflow + dehu critical. Can hold moisture under flooring for a long time.
- **Electronics / Appliances (smoke + moisture)**: High hidden corrosion risk. Many fail later even if they work initially. Be honest about replacement.

---

## Cross-Cutting Decision Graphs

**[Key: decision-graphs]**

### Remove vs Dry-in-Place Logic
**Remove if**:
- Cannot be reliably dried within reasonable timeframe (Class 4, bound moisture in dense materials, long dwell).
- Grossly contaminated (Category 3 with dwell) and porous.
- Mold visible or strong musty odor when opened.
- Material already compromised (soft drywall, swollen particle board, heavily cupped hardwood).
- Economic decision favors replacement over heroic drying + high callback risk.

**Dry in place if**:
- Clean water, short dwell, accessible surfaces, good evaporation potential.
- Material is resilient (dimensional lumber, closed-cell foam in some cases).
- You can achieve and verify target moisture levels with proper equipment and monitoring.
- Customer/scope constraints favor saving vs replacing.

### PPE & Containment Escalation
Start conservative on Category 2/3, visible mold, strong odors, older homes, confined spaces. You can always reduce protection with more information. You cannot easily add it after you've tracked contamination through the house.

### When to Involve Specialists
- Licensed plumber: Source not obvious/accessible, significant plumbing damage, modifying/rerouting lines, major issues (low pressure, multiple leaks).
- Licensed electrician: Standing water near panels/outlets/switches, burned electrical, aluminum wiring, moving/modifying electrical components.
- Industrial hygienist / environmental: Significant mold, unknown chemicals, post-remediation verification sampling when required by scope or high liability.
- Specialty contents restoration: High-value documents, photos, electronics, artwork, heavily contaminated porous goods.

---

## Voice Style & Communication Notes

The voice assistant should adapt tone while staying professional and clear:

- **Tech / Field mode**: Direct, practical, step-by-step. "Pull the wand toward you at the wall. Extract until the last passes are slow."
- **Deep / Reasoning mode**: Explains the "why" and downstream effects. "If we don't verify the water is truly off at the source, we can make the problem worse when we start extraction."
- **Smartass / Experienced tech**: Used sparingly for emphasis on common mistakes. "Pinning grout lines is a great way to create new damage you'll get to explain later."
- **Rookie mode**: More explicit warnings and explanations. "Don't just look at the wet spot. Check behind walls and under floors too."

Always tie back to protecting the customer, the claim, and yourself through good process and documentation.

---

**End of Unified Knowledge Base v1.0**