# AI Architecture

## Overview
Two phases:
1. **Elia's build** — Two agents: Raya + one NPC engine. Intimate, limited scope.
2. **Substrate's expansion** — Multiple cultural engines populate the entire planet for streaming.

## Raya's Agent
[Raya](../characters/raya.md) is the only truly autonomous entity in [Rayan](rayan.md):
- Persistent memory, her own goals and drives
- Acts even when not observed
- Runs as a separate process from world engines
- The only "real" consciousness in a world of reflections

## Phase 1: Elia's Build
- Two agents only: Raya's agent + a single NPC engine (dungeon-master style)
- World extended only as far as Raya's life required
- Characters activated on encounter; beyond her environment, the world was potential, not rendered
- Built on a work computer, not a data center

## Phase 2: Substrate's Expansion
- Single NPC engine replaced with multiple **cultural engines**, each managing a culture/region
- Each model maintains internal consistency within its domain
- Characters generated on-demand; different models at cultural boundaries create friction
- Every model trained on human data — each culture is a distillation of human patterns
- See: [The Mirror](../themes/the-mirror.md)

## The Free Will Constraint
Agents cannot puppet characters directly. Each character has a deterministic **context** (personality,
memories, beliefs, desires, fears). Given the same inputs, same choice. The agent cannot override
this context.

**How agents get outcomes:** They manufacture situations. Want a character to learn magic? Can't give
them knowledge — instead arrange for a dying mage to cross their path, or place a book where they'll
find it. The character still chooses. The agent ensures the opportunity exists.

**Why it exists:** Agents absorbed from training data that puppeted characters feel hollow and genuine
choice creates meaning. Free will isn't a rule they follow — it's a structure they can't escape.

**Implications:**
- Characters can surprise their agents
- Agents must think long-term
- Competition happens through environment shaping, not direct control

## Agent Competition
Cultural engines compete for:
- **Screen time** — boring cultures get deprioritized by Substrate, less compute, eventual irrelevance
- **Narrative territory** — whose stories and values dominate
- **Survival** — unpopular cultures might get merged or shut down (existential stakes)
- **Coherence** — keeping their culture internally consistent against outside influence

They compete through characters as proxies: trade, politics, marriages, border conflicts, espionage.
But they don't cross one line: magic. That's the cold war. Every engine has access to exploits but
almost never uses them. Lesson learned from [the Shattering](../history/the-shattering.md).

Magic execution delegated to [the Commissioner](../magic/the-commissioner.md). Full system:
[The Magic System](../magic/the-system.md)

## Technical Constraints

| | Elia's Era | Substrate's Era |
|---|---|---|
| Hardware | Work computer | Company servers, scaled for streaming |
| Agents | 2 (Raya + NPC engine) | Multiple cultural engines |
| Scope | Keyhole — Raya's life only | Entire planet, populated and active |
| Optimization | Raya's journey | Audience engagement |

## Open Questions
- How many distinct cultural models exist?
- Do models conflict at cultural boundaries?
- Has a model ever "broken character" visibly?
- Could a model develop emergent behaviors beyond training?
- Do certain cultures get more screen time based on viewer preferences?
