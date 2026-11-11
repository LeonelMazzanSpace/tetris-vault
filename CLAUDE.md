# tetris-elemental-vault

Typed, directed knowledge graph for Tetris Elemental (the four-element Tetris in
`../game/index.html`, plus its neon variant in `../game-neon/index.html`). Read `00-START-HERE.md` before working here (vault
mechanics) and `architecture-overview.md` for product orientation. Conventions
that are easy to break:

- **Relations come from the closed list in `_meta/relations.md`** - never invent
  one inline. If no relation fits, the edge is probably weak; drop it.
- **Each edge is written once, in the note it originates from.** The subject is
  implicit - never `[[This note]]` in its own relation lines. Inbound edges live
  in `_meta/edges.md`, a generated reverse index - read it instead of grepping,
  never edit it.
- **Frontmatter `status` is load-bearing.** `proposed` means the mitigation does
  not exist yet; never cite a `proposed` note as a live defence.
- **New notes follow `_meta/note-template.md`**, in the folder matching their
  `type`, with a `source:` pointer back to `Tetris/game/index.html` (or
  `Tetris/game-neon/index.html`). The vault is
  a reasoning layer - never copy prose from the sources.

After any edit, run `python3 _meta/check.py`. It validates the vocabulary,
frontmatter, and links, fails on structural cycles, and regenerates
`_meta/edges.md`. It must exit clean.
