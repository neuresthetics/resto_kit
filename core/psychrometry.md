# core/psychrometry.md — Psychrometry Basics for the Field (Plain Language)

**Purpose**: Understand why drying happens (or doesn't) so you can troubleshoot jobs instead of just throwing equipment at them. Written for voice use in Deep mode and practical application in Tech mode.

## Core Idea

Drying is about creating a **vapor pressure gradient**. You want the air around the wet material to be drier (lower vapor pressure) than the moisture inside the material. Moisture then moves from high to low until equilibrium.

Everything else (air movers, dehus, heat) is just tools to create and maintain that gradient efficiently and safely.

## Key Measurements (What Actually Matters on Site)

**Temperature (°F)**: Affects how much moisture air can hold. Warmer air can hold more moisture.

**Relative Humidity (% RH)**: Percentage of moisture the air is currently holding vs what it *could* hold at that temperature. Useful but incomplete by itself.

**Grains Per Pound (GPP)**: Actual amount of moisture in the air (mass of water vapor per mass of dry air). This is one of the best numbers for drying decisions. Lower GPP = drier air = better drying potential.

**Dew Point**: Temperature at which air becomes saturated and condensation forms. Useful for spotting hidden moisture problems or when outdoor air can help.

**Vapor Pressure**: The actual "push" of moisture trying to evaporate. The difference in vapor pressure between the material and the air is what drives drying.

## Practical Field Rules (My Working Version)

- **You are trying to make the air drier than the materials.** If your dehu is running but GPP/RH isn't dropping in the affected space, something is wrong (poor airflow, hidden moisture source still feeding, unit not sized right, or boundary layer not being broken).

- **Air movers do two jobs**:
  1. Move the humid boundary layer away from the material surface.
  2. Bring drier air into contact with the wet material.

  Without good airflow right at the surface, even a great dehu won't dry fast.

- **Dehumidifiers remove moisture from the air.** They don't magically pull it out of walls or floors. They only work well when air movers are delivering that moist air to them and returning drier air to the materials.

- **Temperature matters**. Cold air holds less moisture. In cold conditions you may need heat + dehu, or the drying will be very slow. Too much heat without enough dehu capacity can actually slow things down by increasing the moisture the air can hold without removing it.

- **Equilibrium Moisture Content (EMC)**: Different materials want to be at different moisture levels depending on the surrounding air. Your goal is usually to bring wet materials back close to the moisture content of unaffected materials in the same environment (or manufacturer specs for things like hardwood).

## Simple Troubleshooting Questions (Voice Prompts)

When a job isn't drying:

1. "Is the air actually moving across the wet surfaces, or are we just circulating humid air in the room?"
2. "What is the GPP or RH in the affected space vs what the dehu is producing at its exhaust?"
3. "Is there still liquid water or a hidden source feeding moisture into the space?"
4. "Are we dealing with a vapor barrier (LVP, vinyl, multiple layers of flooring) that needs to be addressed?"
5. "Is the house so tight that we're just re-circulating the same moist air?"

## Outdoor Air Consideration (When It Makes Sense)

Sometimes bringing in outdoor air helps (especially if it's drier than inside). Other times it hurts (humid summer day or very cold winter air that can't hold much moisture).

Rule of thumb: If outdoor GPP is significantly lower than indoor GPP and you can exchange air safely, it can accelerate drying. Otherwise, closed-system dehu + air movers is usually more controlled.

---

**Deep mode note**: This is the minimum you need to troubleshoot. If you want to go further into psychrometric chart reading, vapor pressure calculations, or material-specific EMC tables, say so and we can go there.

**Tech mode note**: Most days you don't need the full science. You need to know: "Is my equipment actually changing the air in a way that helps the materials dry?" If the numbers aren't moving, change something (more airflow, better placement, add/remove equipment, address hidden water).

Load this with `equipment/air-movers.md` and `equipment/dehumidifiers.md` when troubleshooting.