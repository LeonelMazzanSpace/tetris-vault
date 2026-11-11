---
type: constraint
status: shipped
source:
  - Tetris/game/index.html
  - Tetris/game-neon/index.html
---
# Variants stay in sync

Everything outside the rendering section and the element colour table is identical in both files, and a rule change (reactions, scoring, gravity, input) must be applied to both. On 2026-11-11 the two files were checked: the logic matched line for line, and only comments and visuals differed.

## Structural
- constrains → [[Resolution engine]]
- mitigates → [[Variant drift]]
