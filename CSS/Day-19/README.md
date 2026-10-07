# Day-19 — CSS Mini Project: The Coffee Nook

## Overview

Day 19 was a CSS mini project where I combined the concepts from Day 12 to Day 18 into one complete responsive landing page for a coffee shop called The Coffee Nook. The page contains a navbar, hero section, about section, feature cards, menu, contact section and footer. The goal was to use Flexbox, Grid, CSS variables, transitions, transforms and media queries together in one webpage instead of practising them separately.

## Topics Covered

- CSS variables in :root and var()
- Universal selector reset and box-sizing: border-box
- Flexbox for the navbar and hero section
- CSS Grid for feature cards, menu and contact layout
- max-width with margin: 0 auto
- clamp() for the hero heading
- object-fit: cover for card images
- :hover and :focus on links and buttons
- transition and transform
- Mobile-first design with @media (min-width: 768px)

## Practical Work

I wrote the HTML structure and the external stylesheet for a seven-part landing page. The navbar uses Flexbox and changes from a column on small screens to a row at 768px. The hero is centered with Flexbox, uses min-height in vh units, and has a CTA button made with inline-block so padding and transform work properly. Feature cards and menu items use Grid with one column by default and more columns at 768px, and card images use a fixed height with object-fit: cover so all three look the same size. Hover and focus effects were added to the navigation links, the CTA button, cards and the form button.

During the project I fixed image filenames that had spaces and capital letters, corrected a spelling mistake in one filename, and changed menu headings from h4 to h3 to keep the heading order correct. The heading in the hero wraps onto two lines with the word "You" alone on the second line, and I decided to keep it that way because I like the look.

I checked the layout in the browser at about 400px, 768px and full width, and I checked the hover effect on the navigation links and the CTA button. I did not test the contact form during this session. The contact section also contains a form and an embedded map. These were added as extras beyond the concepts taught so far, and I have not fully understood them yet. The map still had a label from another project that I identified and need to replace.

## Files

- index.html
- style.css
- notes.txt
- README.md
- images/image-beans.jpg
- images/image-expert-barista.jpg
- images/image-daily-pastries.jpg

## Learning Outcome

I learned how to combine several CSS concepts into one responsive page and how mobile-first CSS works, with the base rules written for small screens and the media query written at the end of the file. I also learned that rewriting a stylesheet can accidentally remove work that was already done. In this project the slideUp hero animation and some colour variables were lost after the CSS was rewritten, and some hardcoded colours came back. These are known gaps, and I need to decide whether to restore them before the final version. I also learned that I should understand every part of my code, and that extras like the form and map are not finished until I understand them.

## Status

**Day 19 — Completed**