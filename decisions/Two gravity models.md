---
type: decision
status: shipped
source:
  - Tetris/game/index.html
---
# Two gravity models

Reactions use per-column compaction (blocks fall until supported) while line clears use classic row shifting (overhangs survive). Using column gravity for both would erase every hole in the stack and make the game much easier; using row shifting for reactions would leave blocks hanging in the air.

## Structural
- depends on → [[Column gravity]]
- depends on → [[Line clear]]
