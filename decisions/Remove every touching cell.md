---
type: decision
status: shipped
source:
  - Tetris/game/index.html
---
# Remove every touching cell

A reaction removes all cells that touch any opposite, not just one matched pair. It keeps the rule simple to predict and guarantees no opposite contact survives a pass. The price is generous clears, which is why difficulty is a watched risk.

## Structural
- establishes → [[Stable board]]
- enables → [[Cascade trivializes difficulty]]
