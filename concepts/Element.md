---
type: concept
status: shipped
source:
  - Tetris/game/index.html
---
# Element

Every cell on the board carries exactly one of four elements: fire, water, earth or air. A piece gets one element at creation (`makePiece`) and every cell of it keeps that element for life. The element is the only attribute a cell has besides its position, so everything elemental in the game is built on it.
