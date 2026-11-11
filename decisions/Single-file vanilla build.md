---
type: decision
status: shipped
source:
  - Tetris/game/index.html
---
# Single-file vanilla build

The game was built as plain HTML, CSS and JavaScript in one file rather than a TypeScript and Vite project. For a proof of concept this removes installation and tooling. A move to the company stack (TypeScript strict, pnpm) is a conscious future step, not an oversight.

## Structural
- establishes → [[No build step]]
