---
type: concept
status: shipped
source:
  - Tetris/game/index.html
---
# Resolution loop

After a piece locks, the board is resolved by `resolveStep`: reactions first, then full rows, and the check repeats with a higher chain number until neither applies. Only then does the next piece spawn. Each removal step waits 260 ms so the player can see what vanished.

## Structural
- depends on → [[Reaction]]
- depends on → [[Line clear]]
- causes → [[Stable board]]
