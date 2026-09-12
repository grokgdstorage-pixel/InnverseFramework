---
id: characters-campaign-readme
type: guide
kit: Innverse
path: characters/campaign/README.md
status: draft
---

# characters/campaign/

Empty in the framework repo. After a clone, this is where living people go.

Blanks stay in `characters/templates/`. Do not fill those templates with a real person.

## After clone

One folder per named person.

- Player or Important: copy `characters/templates/_person/` to `characters/campaign/<slug>/`
- Background: copy `characters/templates/_background/` to `characters/campaign/<slug>/`

Rename the slug. Fix frontmatter `path:` to this folder.

Required on `_person`: `profile.md` `mind.md` `relationships.md` `record.md`  
Optional: `magic.md` `history.md` `history-system.md` — delete if unused.

System hold lives on `record.md`. Play text is opened with `reference/operations/play-packet.md`.

Do not put ten background people in one file.
Do not put living people in `characters/templates/`.
