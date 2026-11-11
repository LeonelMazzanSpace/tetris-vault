---
type: failure
status: shipped
source:
  - Tetris/game/index.html
---
# Spawn blocked

The new piece collides at its spawn position (`spawn` runs `collides` before play resumes), the state becomes `over` and the "Fin del juego" overlay appears. This is the single game-over condition and the endpoint to walk back from when a game ends unexpectedly.
