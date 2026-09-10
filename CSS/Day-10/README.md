# Day 10 — Cascade, Specificity & Typography

## Overview
Day 10 goes deeper into how CSS resolves conflicting rules — the cascade, `!important`, and descendant selectors — along with the remaining typography properties.

## Topics Covered
- The Cascade (same specificity → later rule wins)
- `!important` and why it's generally avoided
- Descendant selectors (`nav a` vs `nav, a`)
- `line-height`, `letter-spacing`, `text-decoration`, `text-transform`

## Practical Work
Styled a reused Home page layout with descendant selectors (`nav ul li a`, `section ul li a`), applied `line-height` and `letter-spacing`, and used `text-decoration: none` to remove underlines from specific links. Hit a real bug where styling `nav ul` instead of the `<a>` elements directly didn't work as expected — a useful lesson on targeting the exact element and how directly-targeted default styles override inherited ones.

## Files
- `index.html` — Day 10 HTML structure
- `style.css` — Day 10 external stylesheet
- `notes.txt` — Detailed Day 10 notes
- `README.md` — Day 10 summary

## Learning Outcome
By the end of Day 10, I understand how the cascade resolves same-specificity conflicts, why `!important` should be avoided, and how to use descendant selectors to target elements precisely. I also learned that styling a parent element doesn't guarantee the expected result on its children.

## Status
**Day 10 — Completed**