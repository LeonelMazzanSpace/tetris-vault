---
type: decision
status: shipped
source:
  - Tetris/game-neon/index.html
---
# Neon as a separate copy

The neon version lives in its own file (`game-neon/index.html`) instead of a theme switch inside the original. It keeps each variant openable by double-click and the classic game untouched. The price is that the game rules now exist twice and must be edited twice.

## Structural
- establishes → [[Variants stay in sync]]
- enables → [[Variant drift]]
