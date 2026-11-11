---
type: concept
status: shipped
source:
  - Tetris/game/index.html
---
# Stable board

The invariant that holds whenever a piece is falling: no two opposite elements touch and no row is full. Because the invariant holds at rest, the reaction check after a lock only ever finds contacts created by the piece that just landed (or by gravity afterwards). The next piece never spawns onto an unresolved board.
