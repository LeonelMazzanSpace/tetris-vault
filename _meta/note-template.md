---
type: concept
status: draft
source:
  - Tetris/game/index.html
---
# Note title

Two to four sentences stating the claim. What this is, and why it matters to the
chain it sits in. No paragraph is copied from the source - the source pointer above
is how a reader gets the depth.

## Structural
- causes → [[Some other note]]
- requires → [[Another note]] because the reason fits on one line

## Associative
- resembles → [[A note in another domain]]

<!--
type:   concept | constraint | failure | decision | system   (must match the folder)
status: shipped | built-off-by-default | proposed | draft | todo | superseded
source: one or more repo-relative paths, prefixed with the repo name

Both relation sections are optional. A note with no Structural section is a sink -
a chain endpoint. Expected in failures/, worth a second look anywhere else.

Relations come from _meta/relations.md and nowhere else.
The subject is implicit: never write [[This note]] in its own relation lines.
-->
