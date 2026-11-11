---
type: decision
status: shipped
source:
  - Tetris/game/index.html
---
# Busy flag over input queue

Resolution is protected by a single boolean that blocks input, instead of buffering keys to replay afterwards. It is the smallest mechanism that guarantees a consistent board. A queue would remove the dropped-input cost but needs rules for stale commands.

## Structural
- establishes → [[Input lock]]
