---
type: system
status: shipped
source:
  - Tetris/game/index.html
---
# Game loop

A `requestAnimationFrame` loop (`frame`) that drops the active piece on a level-dependent timer and redraws every frame. Gravity stops while the board is resolving or the game is paused. Level speeds the drop from 800 ms down to a floor of 90 ms.

## Structural
- depends on → [[Resolution engine]]
- depends on → [[Renderer]]
