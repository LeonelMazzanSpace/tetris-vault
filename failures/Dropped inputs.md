---
type: failure
status: shipped
source:
  - Tetris/game/index.html
---
# Dropped inputs

Keys pressed while the board resolves are discarded rather than queued, so a fast player who starts moving the next piece early sees it not respond. Accepted trade-off of the input lock; resolution lasts 260 ms per step, longer in deep chains.
