---
type: system
status: shipped
source:
  - Tetris/game/index.html
---
# Renderer

Canvas drawing of the board, ghost piece and next-piece preview (`renderBoard`, `renderNext`, `drawCell`). Each element has its own colour pair and glyph (▲ ≈ ■ ~) so it stays readable without colour. Cells about to be removed flash white for the duration of a resolution step.

## Structural
- depends on → [[Element]]
