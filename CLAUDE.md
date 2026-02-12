# Claude Instructions

## Purpose
This is a **quick-reference knowledge base** for writing a fantasy novel—not a full wiki. Entries should
be concise and scannable: bullet points over paragraphs, facts over prose. The goal is fast lookup while
writing, not comprehensive reading.

## Markdown Formatting
Wrap lines at approximately 105 characters. Exceptions: links, code blocks, tables, and bullet points
that would lose clarity from breaking.

## File Structure
Files use VSCode-compatible markdown links: `[Display Text](path/to/file.md)`.

Examples:
- Same folder: `[Raya](raya.md)`
- Parent folder: `[Elia](../characters/elia.md)`
- Relative path: `[The Shattering](../history/the-shattering.md)`

## Tone
Clear and direct. State what things are, how they work, and why they matter to the story. Use the
in-world perspective (what characters experience) and the meta perspective (what's actually happening
in the simulation) but keep both brief.

## DRY Principle (Don't Repeat Yourself)
Each concept should have ONE authoritative source. Other files should cross-reference with a one-line
summary and a link.

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
- If yes: Add a one-line summary with a cross-reference link
- If no: Choose the most appropriate file as the authoritative source
- Never duplicate explanations that exist elsewhere
