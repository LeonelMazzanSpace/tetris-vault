---
type: concept
status: shipped
source:
  - Tetris/game/index.html
---
# Column gravity

After a reaction removes cells, every column is compacted downward (`compactColumns`), so loose blocks fall until they rest on something. This can bring cells of opposite elements next to each other that were never adjacent before. It is applied only after reactions, never after line clears.

## Structural
- causes → [[Chain]] because settled blocks can touch new opposites
