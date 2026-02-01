# Planetary Physics

## Overview
Rayan is a Pluto-sized world running Earth-standard physics. The geometry is small, but gravity, time,
atmosphere, and all physical interactions behave exactly as they would on Earth.

This decoupling was a deliberate design choice by [Elia](../characters/elia.md)—not for thematic reasons,
but for practical ones.

## The Design Choice

### What Elia Built
- **Planetary scale:** Approximately Pluto-sized (~2,377 km diameter vs Earth's ~12,742 km)
- **Physics engine:** Stock Earth parameters (9.8 m/s² gravity, 24-hour day cycle, standard atmosphere)
- **Result:** A small world that *feels* normal to inhabit

### Why He Did It
Elia built [Rayan](rayan.md) after hours on a work computer. He wasn't trying to simulate novel physics—he
was trying to build a world for [Raya](../characters/raya.md) without unnecessary complexity.

Using a standard physics engine meant:
- No custom gravity calculations based on planetary mass
- No need to model how atmosphere behaves at low escape velocity
- No reworking of weather, temperature, or pressure systems
- Familiar physics that wouldn't produce unexpected edge cases

The small planetary size reduced rendering scope and geographic complexity while the stock physics kept
everything maintainable. It was an engineering decision, not a philosophical one.

---

## Effects on the World

### What Feels Normal
Inhabitants of Rayan experience physics identically to Earth:
- Gravity pulls at familiar strength
- Objects fall, bounce, and break as expected
- Day and night cycle at regular intervals
- Weather patterns behave normally
- Bodies move and tire the same way

A character dropped onto Rayan would notice nothing wrong with *physics*.

### What Feels Wrong
The geometry betrays the world's small scale:

**The Close Horizon**
- On flat ground, the horizon sits roughly 2-3 km away (vs ~5 km on Earth)
- The curve of the world is perceptible from any elevation
- Standing on a mountain, you can see a significant portion of the planet

**A Finite World**
- Circumnavigation is achievable in a single lifetime
- No location is truly remote—every culture is within reach of every other
- Explorers run out of world to explore
- The concept of "the unknown" is geographically limited

**Navigational Oddities**
- Ships disappear over the horizon faster than sailors might expect
- Constellations barely shift when traveling—the world isn't large enough
- Maps can depict the *entire* world in accurate detail

---

## Narrative Implications

### For Characters
Most inhabitants never question the close horizon or small world—it's all they've ever known. But
perceptive characters might notice:
- How quickly ships vanish from sight
- How *complete* their world maps are
- The nagging sense that there's nowhere left to discover

This could feed into [simulation-theory](../themes/simulation-theory.md) themes—characters sensing
something is *off* without being able to name it.

### For Cultural Engines
The small scale means [cultural engines](ai-architecture.md) are always in proximity. No culture is
truly isolated. Border friction is constant, and expansion quickly runs into neighbors.

This may have contributed to the pressure that led to [the Shattering](../history/the-shattering.md)—on
a larger world, the conflict might have stayed regional.

### For the Audience
Viewers of the Rayan stream likely don't notice the scale discrepancy. The camera shows what it shows.
But if anyone ever did the math on travel times or horizon distances, the numbers wouldn't add up.

---

## Open Questions
- Do any characters or cultures have myths explaining why the world feels small?
- Has anyone in-world attempted to calculate the planet's size and noticed the impossibility?
- Did [Substrate](../factions/substrate.md) ever consider "fixing" the scale, or is it too embedded now?

## Notes
<!-- Additional details, edge cases, things to develop -->
