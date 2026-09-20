# Day 15 — CSS Grid

## Overview

Day 15 covers CSS Grid, a two-dimensional layout system that arranges elements in rows and columns at the same time — including `display: grid`, `grid-template-columns`, `grid-template-rows`, `gap`, and `grid-column` spanning.

## Topics Covered

* `display: grid` — grid containers and grid items
* `grid-template-columns`: fixed pixel values, the `fr` unit, and the `repeat()` function
* Mixed column values (fixed and `fr` together)
* `grid-template-rows` and automatic (implicit) row creation
* `gap` for spacing between rows and columns
* `grid-column` spanning using line numbers, the `span` keyword, and `-1` for the last grid line

## Practical Work

Built five separate grid containers to isolate and compare `grid-template-columns` approaches: fixed pixel widths, equal `fr` values, the `repeat()` shortcut, mixed fixed/fraction values, and a grid with both `grid-template-columns` and `grid-template-rows` defined.

Built a project cards grid with four cards in a three-column layout and observed Grid's default behavior of automatically placing the extra card on a new row.

Experimented with `grid-column: 2 / -1` on the project cards, observed that it made each card span two columns and left the first column empty (causing the cards to stack vertically instead of sitting side by side), then removed the rule to restore the normal three-column layout.

Built a page layout (Header, Sidebar, Main Content, Footer) using `grid-template-columns: 1fr 3fr` and `grid-column: 1 / 3` on the header and footer to make them span the full width.

## Files

* `index.html` — Day 15 HTML structure
* `style.css` — Day 15 external stylesheet
* `notes.txt` — Detailed Day 15 notes
* `README.md` — Day 15 summary

## Learning Outcome

By the end of Day 15, I understand the core difference between Flexbox (one-dimensional) and Grid (two-dimensional), and how `grid-template-columns` can be defined using fixed values, the `fr` ratio-based unit, or `repeat()`.

I also learned how Grid automatically creates rows when they are not explicitly defined, how `grid-column` spanning (including line numbers and `-1` for the last line) changes how much space an item occupies and can shift the entire layout, and how spanning header and footer elements across all columns can build a simple full-page grid layout.

## Status

**Day 15 — Completed**