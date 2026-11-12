---
type: concept
status: shipped
source:
  - Tetris/game/index.html
---
# Opposite pair

Elements are paired as opposites: fire with water, earth with air (the `OPPOSITE` table). Two cells touching orthogonally with opposite elements are the trigger condition for a reaction. Plasma is the exception: it has no single opposite and reacts with every other element (`reactsWith`), though never with another plasma cell. Pairs are fixed and symmetric, so the player can always predict what a placement will touch.

## Structural
- depends on → [[Element]]
