# Start here

This vault holds Tetris Elemental's cross-cutting knowledge as a **typed,
directed graph**. It is a reasoning layer, not a second copy of the code:
`Tetris/game/index.html` (classic) and `Tetris/game-neon/index.html` (neon) stay
the source of truth, and every note points back at the part it came from.

Begin at [[MOC Tetris Elemental]].

## How to read a note

Each note states one claim in a few sentences, then lists its edges under
`## Structural` (the layer you walk to diagnose) and `## Associative` (the
layer you walk to explain or explore).

Three conventions worth knowing before you add anything:

1. **Relations come from `_meta/relations.md` and nowhere else.**
2. **Each edge is written once, in the note it originates from.** Inbound
   edges: backlinks pane, or `_meta/edges.md` as plain files.
3. **`status` in the frontmatter is load-bearing.** `proposed` means the
   mitigation does not exist yet.

Run `python3 _meta/check.py` after editing.

## Try it

Ask these with the vault as the only context - each should come back as a
causal chain ending in an ordered set of actions, not a list of related topics.

1. *A player stacks a fire piece against a water pile and the board suddenly
   looks half empty. Walk the chain from the lock to the final score, in order.*
2. *The game ends with "Fin del juego" although the stack looked low. Walk back
   from Spawn blocked: what chain of events leads there, and which mechanisms
   normally prevent it?*
3. *We want to let the player rotate during the reaction animation. What does
   that constraint protect, and what must change first?*

A vague answer is a signal about the graph, not the model: the spine is
under-typed, and the fix is better edges rather than more notes.

## What is here

Two spines, modelled in depth: [[MOC Reaction spine]] (how elements annihilate
and chain) and [[MOC Resolution spine]] (how the board resolves safely and what
can go wrong). Much of the product is deliberately not modelled yet - see the
scope note at the end of [[MOC Tetris Elemental]].
