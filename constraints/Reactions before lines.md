---
type: constraint
status: shipped
source:
  - Tetris/game/index.html
---
# Reactions before lines

In every resolution step, reactions are checked and applied before full rows. A row that only becomes full because a reaction and gravity rearranged the board is still cleared, but a row that is full and also touches opposites is first reduced by the reaction, so it may no longer be full. Changing this order changes which cells survive.

## Structural
- constrains → [[Resolution loop]]
