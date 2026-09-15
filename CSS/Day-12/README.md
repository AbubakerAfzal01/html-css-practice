Day 12 — Display & Positioning
Overview
Day 12 covers how CSS controls the layout behavior and positioning of elements — the `display` property (block, inline, inline-block, none) and the `position` property (static, relative, absolute, fixed, sticky), along with offsets (top/right/bottom/left) and `z-index`.
Topics Covered

* `display`: `block`, `inline`, `inline-block`, `none`
* `position`: `static`, `relative`, `absolute`, `fixed`, `sticky`
* `top`, `right`, `bottom`, `left` offsets
* The concept of a positioned ancestor
* `z-index` for controlling stacking order

Practical Work
Applied `display: inline-block` to navigation items so they sit side by side with working width, height, padding, and border. Tested `display: inline` on a heading to see that width/height do not apply as expected. Used `position: relative` on a section to shift it while keeping its original space reserved. Built a copyright badge using a relative footer as the positioned ancestor and an absolute child placed in its top-right corner. Created a fixed back-to-top button and confirmed it stays in place while scrolling. Tested `position: sticky` on the page header and observed its behavior is limited by its parent container's height.
Files

* `index.html` — Day 12 HTML structure
* `style.css` — Day 12 external stylesheet
* `notes.txt` — Detailed Day 12 notes
* `README.md` — Day 12 summary

Learning Outcome
By the end of Day 12, I understand how `display` controls whether an element takes a new line and whether width/height apply, and how `position` controls how an element is placed relative to its normal flow, a positioned ancestor, or the viewport. I also learned the key difference between `relative` (keeps its original space) and `absolute` (removed from flow), and between `fixed` (always relative to the viewport) and `sticky` (limited by its container's boundaries).
Status
Day 12 — Completed