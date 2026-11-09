# Cube

We are creating a cube in the game MTG (Magic: The Gathering). The cube is mostly made of uncommons.

## Layout

We typically do our work in this repo, rather than loading it into a session elsewhere. Agent configs and working files are organized as follows. 

Agent config:

- `references/intro.md` -- Big picture. Always load this
- `references/card-selection.md` -- Rules for selecting individual cards
- `references/themes.md` -- Figuring out featured themes for the cube
- `references/tools.md` -- Information about external APIs
- `references/style.md` -- How to create pretty output for human review
- `references/house-rules.md` -- Information about local modifications to specific cards
- `references/playtest-notes.md` -- Lessons learned from actually playing the cube

Working files:

- `cache/` -- Bulk card data and scripts for parsing it under the hood. Not backed up
- `lists/` -- User-provided lists for analysis and comparison
- `html/` -- Pretty HTML output for human review goes here