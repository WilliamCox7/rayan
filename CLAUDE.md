# Claude Instructions

## Markdown Formatting
When creating or editing markdown files in this wiki, wrap lines at approximately 105 characters for
readability. This prevents horizontal scrolling while keeping paragraphs readable.

Exceptions:
- Links should not be broken mid-link
- Code blocks and tables can exceed the limit if necessary
- Bullet points and list items can exceed slightly if breaking would hurt readability

## Wiki Structure
This is a world-building wiki for a fantasy novel. Files use VSCode-compatible markdown links with the
syntax `[Display Text](path/to/file.md)`.

Examples:
- Same folder: `[Raya](raya.md)`
- Parent folder: `[Elia](../characters/elia.md)`
- Relative path: `[The Shattering](../history/the-shattering.md)`

## Tone
The wiki documents should be written in a clear, analytical style—explaining both the in-world perspective
(what characters experience) and the meta perspective (what's actually happening in the simulation).

## DRY Principle (Don't Repeat Yourself)
Each concept, event, or piece of lore should have ONE authoritative source. Other files should reference
that source rather than duplicating the content.

**Authoritative sources by topic:**
- **The Shattering** (history, what happened): `history/the-shattering.md`
- **The Discovery** (Substrate finding Rayan, Elia's firing): `history/the-discovery.md`
- **Magic mechanics** (code words, quotas, how it works): `magic/the-system.md`
- **The Commissioner** (what it is, how it functions): `magic/the-commissioner.md`
- **AI architecture** (technical details, free will constraint): `science/ai-architecture.md`
- **Streaming/editing** (produced episodes vs live, manipulation): `themes/the-edit.md`
- **The Mirror** (AI reflecting humanity to viewers): `themes/the-mirror.md`
- **Character backgrounds**: Their respective files in `characters/`
- **Faction details**: Their respective files in `factions/`

**When adding content:**
- Check if the topic already has an authoritative source
- If yes: Add a brief summary (1-3 sentences) with a cross-reference link
- If no: Choose the most appropriate file to be the authoritative source
- Never copy multiple paragraphs of explanation that exist elsewhere
