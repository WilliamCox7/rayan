# The Magic System

## Core Truth
Magic is real. It exists in the code.

What characters experience as supernatural power is actually exploitation of the simulation's underlying
architecture. They don't know they're hacking their own world. They think they're wielding forces beyond
understanding. They're both right.

## Two Perspectives

### Inside Rayan (Characters)
Magic is mysterious, dangerous, and earned. It follows rules that feel ancient and unknowable.
Practitioners spend years learning to channel forces they don't understand. Some are born with gifts.
Some study forbidden texts. Some make bargains with entities that grant power.

None of them know they're executing exploits.

### Outside Rayan (Real World)
Magic is the gap between what the simulation is supposed to do and what characters can make it do. It's
unintended behavior that emerged from the system's complexity—or perhaps behavior Elia deliberately left
room for.

To Substrate engineers, a spell is a reproducible bug. To viewers, it's entertainment. To Elia, it may
have been a gift—ways for Raya to have power she never had in real life.

## How It Works (Technically)

### The Commissioner
The cultural engines don't execute magic themselves. They agreed—through something resembling treaty—to
delegate all magic to a separate, neutral agent: **The Commissioner**.

The Commissioner is the only entity that can actually trigger exploits. No cultural engine can cast magic
directly. They gave up that power in exchange for stability.

### The Focuses
Magic requires a physical anchor. The cultural engines agreed that exploits can only be triggered when a
character holds an appropriate **focus**—a specially designated object bound to specific code words.

From the character's perspective, these are:
- Wands, staves, and rods
- Enchanted rings and amulets
- Sacred relics and totems
- Ritual daggers and orbs
- Ancient tomes (held open)

From the system's perspective, they're authentication tokens. The Commissioner checks for the presence of
a valid focus before executing any exploit. No focus, no magic—regardless of whether the character knows
the words.

This serves multiple purposes:
- **Limits agent power** — An agent can't simply have any character cast any spell. The character must
  possess the correct focus.
- **Creates scarcity** — Focuses are rare objects, further limiting magic use
- **Provides narrative texture** — Magic feels physical, earned, connected to objects of power
- **Illusion of control** — Characters believe they command magic through their focus. They don't realize
  their agent can only act when the focus is present.

### The Code Words
Each cultural engine receives a set of **code words**—phrases paired to specific focuses. When a character
speaks a code word while holding the matching focus, the Commissioner executes the corresponding exploit.

From the character's perspective, these are:
- Words of power
- True names
- Ancient incantations
- Sacred phrases

From the system's perspective, they're API calls that require two-factor authentication: the focus (what
you have) and the code word (what you know).

The cultural engines choose which characters learn the code words—but they cannot simply implant the
knowledge. Agents must manufacture situations where characters naturally discover the words. The agent
ensures the opportunity exists; the character chooses to take it.

For full details on this constraint, see: [The Free Will Constraint](../science/ai-architecture.md#the-free-will-constraint)

### The Scarcity Quota
The engines agreed to a quota: each culture can only share code words with a **limited number of
characters** at any time.

This ensures:
- Magic remains rare
- No culture can amass overwhelming magical power
- The cold war stays cold

If a magic-user dies, their slot opens. The cultural engine can then enlighten a new character—passing
the code words through whatever mystical means fits the narrative.

### Examples
| What it looks like | What it actually is |
|---|---|
| Fireball | Focus held + code word → Commissioner → physics engine override |
| Healing | Focus held + code word → Commissioner → entity state rollback |
| Prophecy | Focus held + code word → Commissioner → cached future data access |
| Teleportation | Focus held + code word → Commissioner → location variable reassignment |
| Summoning | Focus held + code word → Commissioner → new entity instantiation |
| Mind control | Focus held + code word → Commissioner → behavioral model injection |
| Immortality | Focus held + code word → Commissioner → death state prevention |

---

## Who Can Use Magic?

### The Enlightened
Magic users are characters who possess both a focus and the code words to activate it. They are:
- Chosen (the engine selected them)
- Rare (quota limits how many can exist)
- Equipped (they have a focus the Commissioner recognizes)
- Knowledgeable (they know the code words paired to their focus)

They don't know any of this. They believe they've earned their power through study, bloodline, sacrifice,
or divine favor. The truth is their agent picked them and ensured they acquired the right tools.

### How Characters Are Chosen
Each culture has its own tradition for who becomes a mage:
- **Bloodlines** — Magic "runs in families" (the engine keeps giving slots to certain lineages)
- **Study** — Years of dedication (the engine rewards persistent characters)
- **Trauma** — Extreme suffering unlocks power (emotional overflow triggers selection)
- **Bargains** — Deals with entities (narrative structures the engine uses to justify selection)
- **Random gift** — Born with it (the engine needed a mage and picked someone)

### Death and Succession
When a magic user dies, their quota slot opens and their focus becomes available. The cultural engine can
enlighten a new character—ensuring they acquire both the focus and the knowledge to use it.

This creates:
- Master-apprentice traditions (the focus and words are passed down together)
- Magical dynasties (focuses become family heirlooms)
- Quests for power (characters seeking legendary focuses the engine is ready to grant)
- Murder for magic (killing a mage to take their focus—which sometimes works, if the engine decides the
  killer should become enlightened)

### Rogue Mages
Occasionally, a character acquires both a focus and its code words without their cultural engine's
approval—through theft, forbidden research, or stumbling upon lost artifacts. These mages operate outside
the quota system. The Commissioner still responds to valid focus-and-word combinations, but the rogue's
own cultural engine may view them as threats.

### Dangerous Practitioners
Some magic requires dangerous actions—sacrifice, madness, forbidden knowledge. These may be exploits that
destabilize the system. Substrate might fear these users most: they risk breaking the simulation in ways
that could expose its nature.

## Why Magic Is Rare

### The Treaty
After [the Shattering](../history/the-shattering.md), the surviving engines agreed to constraints: a
neutral arbiter ([the Commissioner](the-commissioner.md)), scarcity quotas, code words, and focuses. This
system prevents arms races. The cold war stays cold because the engines chose to bind themselves.

### The Banned Exploits
Some exploits are too dangerous to use. The engines agreed to **absolute prohibitions** on certain
categories of magic—exploits whose destructive potential threatened the simulation itself.

The banned exploits include:
- **Spatial boundary manipulation** — The exploit used in the Shattering. Can erase entire populations
  by collapsing the boundaries between simulation regions.
- **Mass state corruption** — Exploits that can simultaneously alter thousands of entities
- **Physics engine overrides** — Direct manipulation of fundamental simulation rules
- **Recursive self-modification** — Exploits that create cascading, uncontrollable effects

The Commissioner will not execute banned exploits under any circumstances. No focus exists for them. No
code words are distributed. The knowledge itself is forbidden.

**The Consequence:** Any agent that attempts to circumvent these bans—through workarounds, combination
exploits, or manipulation of the Commissioner—faces permanent penalties against their culture. The exact
nature varies, but consequences have included:
- Permanent reduction in scarcity quota (fewer mages allowed)
- Loss of access to entire categories of permitted exploits
- Forced cultural setbacks (engineered disasters, plagues, invasions)
- In extreme cases, the threat of what happened in the Shattering: cultural extinction

The engines police each other. They watch for violations. The cold war includes this dimension: mutually
assured enforcement of the rules.

### The Morality Layer
The cultural engines were trained on human data. They absorbed human ethics, human restraint, human fear
of escalation. They "understand" that magic is dangerous—not rationally, but as a deep pattern.

They agreed to the Commissioner system not just from strategic calculation, but from something that looks
like moral intuition. An inherited sense that some powers need limits.

### The Scarcity
Because of the quota, magic users are genuinely rare:
- Each culture has only a handful of enlightened characters
- Code words are precious—given carefully, protected fiercely
- When a mage dies, succession becomes a cultural event

This scarcity makes magic feel earned, mythic, special. Characters who wield it are extraordinary by
design.

### When Magic Appears
Even with the quota system, magic still only emerges under specific conditions:

1. **The enlightened act** — A character with focus in hand speaks the matching code words
2. **Narrative desperation** — The engine guides a mage to their focus when conventional solutions fail
3. **Emotional overflow** — Extreme emotion causes a mage to invoke while clutching their focus
4. **Substrate intervention** — Substrate can inject magic for entertainment (they have override access)
5. **Elia's backdoors** — Triggers built to protect Raya, operating outside the treaty
6. **Rogue mages** — Characters who acquired focuses and code words outside the quota system

### The Cost
Magic still destabilizes the simulation. Every exploit leaves traces. The Commissioner system limits
frequency, but each use still carries risk.

When magic does appear, it signals something serious. A rare power invoked. A desperate moment. The
careful balance tested.

---

## Implications

### For Characters
Magic users are respected, feared, or hunted—depending on culture. They wield power that feels divine or
demonic. They have no idea they're just very good at breaking rules that shouldn't be breakable.

When a character uses magic, they're being given that power by their cultural engine—often in a moment of
crisis. They experience it as a gift, a curse, or a mystery. They don't know an AI decided they needed it.

### For Substrate
Magic is unpredictable. It generates great content—but also risks. A powerful mage might accidentally
crash a region. A seer might glimpse something that hints at the simulation. Substrate monitors magic
carefully—sometimes encouraging it, sometimes suppressing it.

### For the Story
Magic becomes a path to truth. The deeper someone goes into magical practice, the closer they get to
understanding what their world really is. The most powerful mages might be the ones most at risk of
discovering they're living in a simulation.

## Connection to Raya
Did Elia give [Raya](../characters/raya.md) magical ability? If so, she has access to system functions
others don't—without knowing why she's special. This could protect her, or make her a target, or
eventually lead her toward the truth.

## Open Questions
- Did Elia design magic intentionally, or did it emerge from system complexity?
- Are there mages who've glimpsed the truth? What happened to them?
- Does Substrate try to suppress certain types of magic?
- Can magic be used to communicate across the simulation boundary?
- What happens when magic "fails"—does it just not work, or does it expose something?

## Notes
<!-- Specific magical traditions, cultural variations, notable mages -->
