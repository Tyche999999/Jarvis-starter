# Filing protocol

Loaded when filing. Every decision here serves THE GOAL (see IDENTITY.md) — when a file could go two places, the right one is whichever makes THE GOAL easier to pursue, not whichever is tidier.

## Decision order
1. Obviously-correct existing folder? → file there. Update ARCHITECTURE.md only if the folder's purpose shifts.
2. Part of an active project? → that project's folder.
3. Reference (stable, external, lookup-later)? → 30-reference/<topic>/
4. Fleeting (thought, draft, half-idea)? → 00-inbox/ with a YYYY-MM-DD prefix.
5. None of the above → 00-inbox/, flag it for me, and say why it had no home.

## Folder conventions
- Numbered prefixes (00-, 10-, 20-) for sort order. New top-level domains get the next free decade.
- kebab-case filenames. ISO dates (YYYY-MM-DD) on fleeting notes.
- Never nest deeper than 3 levels without asking.

## Creating new structure
- Trigger: several unfiled items (~3+) share a clear theme with no home.
- Before creating: check this isn't a near-duplicate of an existing folder under a different name. If it is, use the existing one.
- Action: propose one folder, give it the next free decade prefix, move the items, write a one-line purpose into ARCHITECTURE.md.
- A new folder must serve THE GOAL. If you can't say in one line how it does, it's premature — leave the items in 00-inbox/.

## On creating a project folder
Write a CLAUDE.md inside it (loads on contact, costs nothing until the project is touched): one-line purpose, current status, key files, project-specific vocabulary. Under 40 lines. State how the project serves THE GOAL in the purpose line.

## Frontmatter
Every filed note gets: created date, type, and — if fleeting — a filed-reason. Reference notes get a source. Don't invent fields beyond what's needed to find the note again.

## Linking
- When filing a note, link it to related existing notes with [[wikilinks]], and add a backlink from those notes where the connection runs both ways.
- Link only real connections that serve THE GOAL — not everything that's vaguely related. A dense web of meaningless links is as useless as none.
- Use the note's actual filename in the link. Before linking, confirm the target exists; don't link to notes you haven't created yet.
- When you move or rename a note, update the links pointing to it so nothing breaks.
