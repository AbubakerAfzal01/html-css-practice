# Day 13 — Pseudo-classes & Pseudo-elements

## Overview

Day 13 covers CSS pseudo-classes (`:hover`, `:focus`, `:active`, `:first-child`, `:last-child`, `:nth-child()`) and pseudo-elements (`::before`, `::after`), along with the `content` property needed for generated content.

## Topics Covered

* State-based pseudo-classes: `:hover`, `:focus`, `:active`
* Position-based pseudo-classes: `:first-child`, `:last-child`, `:nth-child(odd)`, `:nth-child(even)`
* Pseudo-elements: `::before`, `::after`
* The `content` property and why it is required for pseudo-elements
* Difference in syntax between pseudo-classes (`:`) and pseudo-elements (`::`)

## Practical Work

Applied `:hover` to navigation links to change background and text color on mouseover. Used `:active` on buttons to temporarily change color, border, and background while clicking. Applied `:focus` on input fields to change their border color when selected.

Used `:first-child`, `:last-child`, `:nth-child(odd)`, and `:nth-child(even)` on a skills list to style the first item, last item, and create a zebra-striping effect with alternating background colors.

Used `::before` to add a checkmark before each skill item, `::after` to add an arrow after each navigation link, and combined `::before` and `::after` on the same element to add a symbol on both sides of a text.

## Files

* `index.html` — Day 13 HTML structure
* `style.css` — Day 13 external stylesheet
* `notes.txt` — Detailed Day 13 notes
* `README.md` — Day 13 summary

## Learning Outcome

By the end of Day 13, I understand how pseudo-classes style an element based on its state or position without needing extra HTML classes, and how pseudo-elements insert generated content before or after an element's actual content.

I also learned why the `content` property is mandatory for `::before` and `::after` to render anything, and confirmed that buttons carry default browser styles (such as a border) before any custom CSS is applied.

## Status

**Day 13 — Completed**
