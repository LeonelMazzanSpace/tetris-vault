---
type: system
status: shipped
source:
  - Tetris/game/index.html
---
# Resolution engine

The group of functions that runs after a lock: `findReactions`, `resolveReactions`, `compactColumns`, `fullRows`, `resolveLines` and `resolveStep`. It is timer-driven (one step every 260 ms) and calls `spawn` when the board is stable.

## Structural
- depends on → [[Resolution loop]]
- depends on → [[Column gravity]]
