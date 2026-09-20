# Day 14 — Flexbox

## Overview

Day 14 covers CSS Flexbox, a layout system used to arrange elements in a row or column and control their alignment, distribution, and spacing — including `display: flex`, `flex-direction`, `justify-content`, `align-items`, `flex-wrap`, and `gap`.

## Topics Covered

* `display: flex` — flex containers and flex items
* `flex-direction`: `row` (default) and `column`
* `justify-content` (main axis alignment): `center`, `space-between`, and related values
* `align-items` (cross axis alignment): `stretch` (default) vs `flex-start`
* `flex-wrap: wrap` for preventing overflow
* `gap` for spacing between flex items

## Practical Work

Applied `display: flex` with `gap` and `justify-content: center` to a navigation list so the links sit side by side and centered.

Built a box container with five fixed-size boxes using `flex-direction: row`, `flex-wrap: wrap`, `gap`, and `justify-content: center`, and confirmed the boxes wrap onto a new line when space runs out.

Built a card layout with `justify-content: center` and `align-items: flex-start`, then intentionally gave one card longer text than the others to observe how `flex-start` keeps items aligned from the top with independent heights, compared to the default `stretch` behavior.

## Files

* `index.html` — Day 14 HTML structure
* `style.css` — Day 14 external stylesheet
* `notes.txt` — Detailed Day 14 notes
* `README.md` — Day 14 summary

## Learning Outcome

By the end of Day 14, I understand how `display: flex` turns a container's direct children into flex items, and how `justify-content` controls alignment along the main axis while `align-items` controls alignment along the cross axis.

I also learned how `flex-wrap` prevents items from overflowing their container, how `gap` simplifies spacing compared to using margins on individual items, and continued reinforcing the difference between `border-color` alone and the `border` shorthand from Day 13.

## Status

**Day 14 — Completed**