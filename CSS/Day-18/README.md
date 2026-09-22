# Day 18 — Responsive / Mobile-First Design

## Overview

Day 18 covers making a webpage adapt to different screen sizes using `@media` queries and a mobile-first approach — starting with a simple small-screen layout by default and enhancing it for larger screens with `min-width` breakpoints, instead of designing for desktop first.

## Topics Covered

* `@media` query syntax, `min-width` vs `max-width`
* Breakpoints as decision points where a layout needs to change, not fixed rules
* Mobile-first vs desktop-first approach
* `width` vs `max-width` and why a fixed width causes horizontal scrolling on small screens
* Testing responsive behavior with browser DevTools by resizing the viewport

## Practical Work

Fixed a page that used a rigid `width: 1100px` on `main` by switching it to `max-width: 1100px`, preventing horizontal scrolling on small screens. Built a mobile-first layout container that stacks in a column by default and switches to a row at a `768px` breakpoint, and a card grid that starts at one column per row and expands to two columns at `768px` and four columns at `1024px`.

Applied `clamp()` (from Day 16) to a paragraph's `font-size` so it scales smoothly with the viewport width. Tested the full page at multiple screen widths using browser DevTools to confirm the navigation, layout, cards, and text all responded correctly at each breakpoint.

## Files

* `index.html` — Day 18 HTML structure
* `style.css` — Day 18 external stylesheet
* `notes.txt` — Detailed Day 18 notes
* `README.md` — Day 18 summary

## Learning Outcome

By the end of Day 18, I understand how `@media` queries let a stylesheet apply different rules at different screen widths, and why the mobile-first approach — writing simple default styles for small screens and layering on `min-width` enhancements for larger ones — makes a layout easier to reason about than starting from desktop and overriding downward.

I also learned the practical difference between `width` (a rigid size) and `max-width` (a flexible ceiling), reinforced that `@media` blocks must be written at the top level rather than nested inside a selector, and saw how a concept from an earlier day (`clamp()`) can be reused directly in a new context like responsive typography.

## Status

**Day 18 — Completed**