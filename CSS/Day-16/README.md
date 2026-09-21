# Day 16 — CSS Variables & Modern Functions

## Overview

Day 16 covers CSS Custom Properties (variables) for storing and reusing values across a stylesheet, along with modern CSS functions — `calc()`, `min()`, `max()`, and `clamp()` — for calculations and responsive sizing without relying only on media queries.

## Topics Covered

* CSS Custom Properties: `--variable-name` syntax and the `:root` selector
* `var()` for reusing variable values throughout a stylesheet
* `calc()` for mathematical expressions, including combining variables with calculations
* `min()` — using the smaller of two or more values
* `max()` — using the larger of two or more values
* `clamp()` — keeping a value between a minimum and maximum while staying flexible in between

## Practical Work

Defined a set of variables in `:root` for colors, spacing, and fonts, then reused them across cards, buttons, a navigation bar, and headings. Tested the "change once, update everywhere" behavior by changing `--primary-color` and observing it update on both an always-visible button and a `:hover` state that only became visible once triggered.

Built a `calc()`-based box that subtracts a variable-based spacing value (multiplied by two) from 100% width. Built a `min()`-based responsive box that never grows past 400px, and a `clamp()`-based heading whose font size scales with viewport width while staying within a fixed minimum and maximum.

## Files

* `index.html` — Day 16 HTML structure
* `style.css` — Day 16 external stylesheet
* `notes.txt` — Detailed Day 16 notes
* `README.md` — Day 16 summary

## Learning Outcome

By the end of Day 16, I understand how CSS Custom Properties let me store a value once and reuse it everywhere, so changing a single variable updates every element that references it — including states like `:hover` that only reveal the updated value once triggered.

I also learned how `calc()` combines percentages, fixed values, and variables into a single calculated value, and how `min()`, `max()`, and `clamp()` can handle many simple responsive sizing needs directly in CSS, reducing (though not eliminating) the need for media queries. Along the way, I reinforced why writing HTML myself rather than using AI-generated code matters for actually understanding what I build, and learned to properly test responsive behavior in a full browser window rather than a small preview panel.

## Status

**Day 16 — Completed**