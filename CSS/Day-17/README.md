# Day 17 — Transitions, Transforms & Basic Animations

## Overview

Day 17 covers making CSS changes feel smooth and interactive — the `transition` property for animating state changes, the `transform` property (`scale()`, `rotate()`, `translate()`) for visual changes without affecting document flow, and `@keyframes` for multi-stage animations that can run automatically and repeat.

## Topics Covered

* `transition`: property, duration, timing-function, and the choice between `all` and specific properties
* `transform`: `scale()`, `rotate()`, `translate()`, and combining multiple transform functions in one declaration
* `@keyframes`: defining animation stages with `0%`/`50%`/`100%` or `from`/`to`
* The `animation` property: name, duration, timing-function, and `infinite`
* The difference between `transition` (two states, usually triggered by `:hover`) and `@keyframes` (multiple stages, can run automatically)

## Practical Work

Built a transition button that smoothly changes background color and scales on hover. Built three transform boxes (scale, rotate, translate) with base transforms and separate `:hover` transforms, and discovered that a `transform` declaration completely overwrites any earlier one rather than merging with it — multiple transform functions must be combined in a single declaration to apply together.

Built a bounce animation (`0%`/`50%`/`100%` keyframes moving an element up and back down) and a spin animation (`from`/`to` keyframes rotating a full 360 degrees), both running continuously with `infinite`. Built a hover card combining `transition` and `transform` together, lifting and slightly scaling on hover as a real-world interactive effect.

## Files

* `index.html` — Day 17 HTML structure
* `style.css` — Day 17 external stylesheet
* `notes.txt` — Detailed Day 17 notes
* `README.md` — Day 17 summary

## Learning Outcome

By the end of Day 17, I understand how `transition` smooths a change between two CSS states, and how `transform` can scale, rotate, and move elements without disrupting the normal document flow. The key discovery was that `transform` declarations do not merge — writing `transform` more than once in the same rule, or differently between a base state and its `:hover` state, causes only the last declaration to apply, so every needed transform function must be written together in one line.

I also learned how `@keyframes` differs from `transition` by allowing multiple animation stages that can run automatically and repeat with `infinite`, and reinforced the importance of cleaning up duplicate CSS carefully after accidentally deleting a needed `@keyframes` block while removing duplicates.

## Status

**Day 17 — Completed**