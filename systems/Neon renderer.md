---
type: system
status: shipped
source:
  - Tetris/game-neon/index.html
---
# Neon renderer

The drawing layer of the neon variant: each cell is a translucent fill with a glowing outline (canvas `shadowBlur`), a bright glyph and a dashed ghost piece, over a synthwave grid background. Element colours are neon (fire red-pink, water cyan, earth green, air violet). Only drawing and styling differ from the classic renderer; rules and scoring are the same code.

## Structural
- is a case of → [[Renderer]]
- depends on → [[Element]]
