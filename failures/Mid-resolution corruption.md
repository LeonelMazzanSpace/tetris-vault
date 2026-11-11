---
type: failure
status: shipped
source:
  - Tetris/game/index.html
---
# Mid-resolution corruption

If the player could act while reactions or line clears are pending, a hard drop or lock could write cells into a board whose removal is scheduled by timer, leaving the result dependent on timing. The input lock exists to make this impossible.
