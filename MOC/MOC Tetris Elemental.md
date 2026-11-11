---
type: moc
status: shipped
source:
  - Tetris/game/index.html
---
# MOC Tetris Elemental

Root map. It holds no knowledge of its own; it points at the two spines.

## Spines
- [[MOC Reaction spine]] - elements, opposites, reactions, gravity, chains
- [[MOC Resolution spine]] - how the board resolves safely, and how a game is lost

## Variants
- [[Neon renderer]] - the neon skin of the same game
- [[Neon as a separate copy]] - why it is a second file
- [[Variants stay in sync]] and [[Variant drift]] - the cost of two copies

## Product orientation
- [[architecture-overview]] - what the product is, system map, what is not live
- [[00-START-HERE]] - vault mechanics and probe questions

## Deliberately not modelled
Controls and key bindings, scoring tables beyond the notes above, visual styling
of the side panel, the piece bag randomiser, wall-kick rules, mobile and touch
play, sound, persistence of high scores. Read `Tetris/game/index.html` for these.
