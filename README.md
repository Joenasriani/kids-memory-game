# The Memory Challenge

Canonical play URL: https://kids-memory-game-xi.vercel.app/

GitHub Pages mirror: https://joenasriani.github.io/kids-memory-game/

The Memory Challenge is a nine-level visual number-position memory game developed as part of a multi-game interactive children’s edutainment activation in the UAE.

## Game structure

Each level places numbered blocks in random positions on a 3×3 grid. The player first sees the numbers, then the numbers hide. The player must tap the hidden positions in ascending numerical order.

**show numbered positions → hide numbers → recall positions → tap 1, 2, 3… in order → complete sequence → advance level**

The number of active blocks equals the current level:

- Level 1: 1 block
- Level 2: 2 blocks
- …
- Level 9: 9 blocks

The memorization window shortens as the level increases. A wrong tap costs one life and restarts the same level. Each completed level restores the run to three lives.

## Activation context

This game belongs to the same `kids-*` game set developed for the multi-game interactive children’s edutainment activation in the UAE.

## What the repository demonstrates

The implemented mechanic requires short-term recall of spatial positions and numerical order. The repository does not contain a study measuring memory improvement, learning transfer, retention, or cognitive outcomes outside the game.

## Repository scope

The playable implementation is contained in `index.html`.

The game file is preserved as the playable artifact. Documentation and discovery files must not change levels, timing, lives, number placement, answer logic, controls, visuals, reset behavior, or runtime behavior.
