---
type: moc
status: shipped
source:
  - Tetris/game/index.html
---
# MOC Resolution spine

What happens between a piece locking and the next one spawning, what protects
that window, and the failures that end or degrade a game.

## Walk in this order
- [[Resolution loop]]
- [[Reactions before lines]]
- [[Stable board]]
- [[Input lock]]
- [[Busy flag over input queue]]
- [[Resolution engine]]
- [[Game loop]]
- [[Renderer]]
- [[No build step]]
- [[Single-file vanilla build]]
- [[Element independent of shape]]

## Failures (chain endpoints)
- [[Line clear]] and [[Stack overflow]]
- [[Spawn blocked]]
- [[Mid-resolution corruption]]
- [[Dropped inputs]]
