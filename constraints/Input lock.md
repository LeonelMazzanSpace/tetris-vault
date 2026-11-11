---
type: constraint
status: shipped
source:
  - Tetris/game/index.html
---
# Input lock

While the board is resolving (the `busy` flag), keyboard input for movement, rotation and drops is ignored; only pause and restart still work. No piece exists during resolution, and the board is mid-edit, so acting on it would corrupt the result. The cost is that keys pressed during the animation are lost.

## Structural
- prevents → [[Mid-resolution corruption]]
- causes → [[Dropped inputs]]
- constrains → [[Game loop]]
