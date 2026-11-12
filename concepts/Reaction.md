---
type: concept
status: shipped
source:
  - Tetris/game/index.html
---
# Reaction

When opposite elements touch, or plasma touches any other element (named "Descarga de plasma"), both cells vanish (`findReactions` marks them, `resolveReactions` removes them) and score 10 points per cell times the chain number. It is the game's signature mechanic: it clears space without needing a full row, and it leaves unsupported blocks behind.

## Structural
- depends on → [[Opposite pair]]
- causes → [[Column gravity]] because removed cells leave blocks floating above them
- mitigates → [[Stack overflow]] because it clears cells without needing a full row

## Associative
- contrasts with → [[Line clear]] because one clears by contact between elements, the other by row geometry
