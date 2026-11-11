# Relation vocabulary

This list is closed. It is the guardrail that keeps the graph typed: an open
vocabulary is how a directed graph decays back into "related to".

Adding a relation is a deliberate edit to this file, not something done in passing
while writing a note. If an edge cannot be named from this list, the edge is probably
weak - which is a reason to drop it, not to invent a name.

`_meta/check.py` reads the tables below. A relation that is not here fails the check.

## Line format

    - <relation> → [[Target]]
    - <relation> → [[Target]] because <reason>

The subject is the note itself and is never restated as a wikilink. Each edge is
written once, in the note where it originates. Inbound edges are read from the
backlinks pane - or from `_meta/edges.md` when reading the vault as plain files.

## Structural

Directed and acyclic. This is the layer Claude walks when it has to explain,
diagnose, or defend something.

| Relation | Use when |
| --- | --- |
| `requires` | The target must hold for the subject to be safe or possible. |
| `depends on` | The subject cannot function without the target. |
| `causes` | The subject produces the target. Mechanism to outcome. |
| `enables` | The subject makes the target possible without forcing it. |
| `forbids` | The subject rules the target out. Constraint vs anti-pattern. |
| `mitigates` | The subject reduces the target's likelihood or blast radius. |
| `prevents` | The subject eliminates the target outright. Stronger than `mitigates`. |
| `evidences` | The subject is observed data supporting the target claim. |
| `constrains` | The subject bounds how the target may be designed or operated. |
| `establishes` | A decision creates the target constraint. Decision notes only. |
| `supersedes` | The subject replaces the target. Typical between ADRs. |
| `is part of` | Composition. |
| `is a case of` | Specific instance of the target's general pattern. |

## Associative

May cycle. For discovery and explanation by analogy, never for diagnosis.
Keep it sparse; an associative edge still has to answer "why should these
two ideas talk to each other?"

| Relation | Use when |
| --- | --- |
| `resembles` | Same shape in a different domain. |
| `contrasts with` | Instructive difference, including a rejected alternative. |
| `is a metaphor for` | Useful for explaining the target to someone new. |
| `opens a question about` | The subject raises an unresolved question about the target. |
