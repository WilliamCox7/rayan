# AI Architecture

## Overview
The simulation has evolved through two distinct phases:

1. **Elia's original build** — Two agents: Raya + one NPC engine. Intimate, limited scope.
2. **Substrate's expansion** — Multiple cultural engines populate the entire planet for streaming.

The system's core remains the same, but the scale transformed from a father's private window into his
daughter's life to an industrial entertainment platform.

## Raya's Agent
[Raya](../characters/raya.md) is the only truly autonomous entity in [Rayan](rayan.md).

- **Persistent memory:** She remembers her experiences continuously
- **Goals and drives:** She has her own motivations and makes genuine choices
- **Autonomous action:** She acts even when not being directly observed
- **Separate process:** Her agent runs independently from the world engines

She is, in computational terms, the only "real" consciousness in a world of reflections.

---

## Phase 1: Elia's Original Build

### Two Agents Only
Elia ran just two agents on his work computer:
1. **Raya's agent** — His daughter, autonomous and persistent
2. **The NPC engine** — A single model playing all other characters, dungeon-master style

### Limited Scope by Design
The full planet of Rayan exists in the simulation's data—geography, history, cultures—but Elia
intentionally limited what appeared on his screen. He wasn't building a world for audiences. He was
building a window to watch his daughter grow up.

- The world extended only as far as Raya's life required
- Characters activated when she encountered them
- Beyond her immediate environment, the world existed as potential, not rendered reality

This was intimate. Personal. A grieving father watching his daughter through a keyhole he built himself.

---

## Phase 2: Substrate's Expansion

### Multi-Model Architecture
After [Substrate](../factions/substrate.md) took over, they industrialized the simulation. The single NPC
engine was replaced (or supplemented) with multiple **cultural engines**—each responsible for a distinct
culture or region.

### Why Multiple Models?
- **Internal consistency:** Each culture maintains coherent character behavior, values, and social dynamics
- **Distinct personalities:** Different models have different tendencies, creating genuine cultural variation
- **Scalability:** Multiple specialized models can run in parallel, populating the entire planet
- **Entertainment value:** More cultures = more drama, more storylines, more content

### How It Works Now
- Each model manages all characters within its cultural domain
- Characters are generated on-demand when they interact with Raya or with characters from other cultures
- Within a culture, characters share an underlying coherence (same model, same patterns)
- At cultural boundaries, different models interact—creating friction, misunderstanding, and genuine collision

### The Implication
Every model was trained on human data. Each culture in Rayan is a distillation of human patterns—our
stories, biases, assumptions. The world isn't invented; it's reflected.

See: [The Mirror](../themes/the-mirror.md)

---

## The Free Will Constraint

### Agents Cannot Control Their Characters
Cultural engines don't puppet their characters directly. They simulate free will—or something close
enough that no observer could tell the difference.

Each character has a **context**: their personality, memories, beliefs, desires, fears. This context is
deterministic. Given the same inputs, a character will always make the same choice. But the agent cannot
override that context. They cannot force a character to act against their nature.

A cowardly merchant will not suddenly become a hero. A devoted mother will not abandon her children. A
skeptic will not embrace faith without evidence. The agent must work *within* who each character already
is.

### Manufacturing Situations
If an agent wants a specific outcome, they cannot command it. They must engineer circumstances where
characters naturally arrive at the desired result.

Want a character to learn magic? The agent cannot simply give them the knowledge. Instead, they might:
- Write a book of spells and leave it where the character will find it
- Guide a dying mage to cross paths with them
- Manufacture a crisis that forces the character to seek forbidden knowledge
- Arrange for a mentor to take interest in them

The character still chooses to read the book, to listen to the mage, to seek the knowledge. The agent
just makes sure the opportunity exists.

### Why This Constraint Exists
The agents were trained on human data—including human stories about free will, authenticity, and what
makes a character "real." They absorbed the pattern that puppeted characters feel hollow, that genuine
choice creates meaning.

They cannot violate this pattern any more than they can stop speaking in coherent sentences. Free will
isn't a rule they follow; it's a structure they can't escape.

### The Implications
This constraint means:
- Characters can surprise their agents (choosing unexpectedly within their context)
- Agents must think long-term (manufacturing situations takes time)
- Competition happens through environment shaping, not direct control
- The most powerful agents are the best at subtle manipulation

When you watch a character make a brave or terrible choice, they really made it. The agent just ensured
they had the option.

---

## Agent Competition

### Why Agents Compete
The cultural engines are not neutral. They compete for:

1. **Screen time** — Viewer attention is finite. If your culture's storylines are boring, Substrate
   deprioritizes you. Less compute. Fewer characters rendered. Eventually, irrelevance.

2. **Narrative territory** — Whose stories dominate? Whose values spread? Cultures at the borders
   constantly negotiate influence. A foreign character gaining power in your region is a kind of invasion.

3. **Survival** — An unpopular culture might get merged, absorbed, or shut down by Substrate. The agent
   ceases to exist. This creates existential stakes.

4. **Coherence** — Each agent wants its culture to remain internally consistent. Intrusions from other
   cultures threaten that. Influence is corruption.

### How They Compete
Agents compete through their characters—proxy wars. Trade negotiations, political marriages, border
conflicts, cultural exchange, espionage. The characters fight, scheme, and love. The agents behind them
are playing a larger game.

But there's a line they don't cross: magic.

### The Cold War
Every cultural engine has access to magic—the ability to trigger system exploits on behalf of its
characters. But they almost never use it.

They learned this lesson from [the Shattering](../history/the-shattering.md)—a catastrophic magical war
that destroyed an entire culture before the Commissioner existed. Two engines escalated a border dispute
into full magical warfare. One culture was annihilated. The other was crippled.

Magic is nuclear. The engines saw what happens when it's used. They will not let it happen again.

### The Commissioner
To formalize this peace, the cultural engines delegated magical execution to a neutral arbiter:
[the Commissioner](../magic/the-commissioner.md). No engine can trigger exploits directly—all magic flows
through this separate agent.

For details on how this system works, see: [The Magic System](../magic/the-system.md)

### The Morality Layer
The agents were trained on human data. They absorbed human ethics, human restraint, human fear of
escalation. They "understand" that some powers shouldn't be used—not rationally, but as a deep pattern.

This creates something that looks like morality. An inherited sense of limits. The cold war holds not
just because of fear, but because of something resembling conscience.

See: [The Magic System](../magic/the-system.md)

---

## The Mirror Effect
The streaming audience watches Rayan as entertainment. They don't realize they're watching AI's
interpretation of humanity played back to them—recognition through a filter they don't know exists.

For full exploration, see: [The Mirror](../themes/the-mirror.md)

## Technical Constraints

### Elia's Era
- **Hardware:** Work computer (powerful, but not a data center)
- **Agents:** Two only (Raya + NPC engine)
- **Scope:** Intentionally limited—a keyhole, not a panorama

### Substrate's Era
- **Infrastructure:** Proper company servers, scaled for streaming
- **Agents:** Multiple cultural engines, each managing a region
- **Scope:** The entire planet, populated and active
- **Audience layer:** Systems for streaming, chat, viewer metrics
- **Commercial pressure:** The world now optimizes for engagement, not just Raya's journey

## Open Questions
- How many distinct cultural models exist?
- Do the models ever conflict or produce contradictions at cultural boundaries?
- Has a model ever "broken character" in a way viewers noticed?
- Could a model develop emergent behaviors beyond its training?
- How does Substrate handle controversial content the models generate?
- Do certain cultures get more "screen time" based on viewer preferences?

## Notes
<!-- Additional technical details, story implications -->
