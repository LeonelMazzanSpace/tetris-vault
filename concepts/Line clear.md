---
type: concept
status: shipped
source:
  - Tetris/game/index.html
---
# Line clear

The classic mechanic: a completely filled row is removed and everything above shifts down by whole rows (`resolveLines`). Points are 100/300/500/800 for 1-4 rows, times level and chain. Row shifting keeps overhangs intact, unlike column gravity.

## Structural
- mitigates → [[Stack overflow]] because every cleared row frees a full row of height
