---
type: constraint
status: shipped
source:
  - Tetris/game/index.html
---
# Chains terminate

Every removal step deletes at least one cell and nothing adds cells during resolution, so the loop always ends. Any future mechanic that spawns or converts cells during resolution (for example fire spreading) must keep this property or the game can hang between pieces.

## Structural
- constrains → [[Chain]]
