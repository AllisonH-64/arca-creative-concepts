# Changelog

Notable changes to the ARCA Creative Concepts site. See the [README](README.md) for what the site is and how to run/deploy it.

## 2026-09-19

- Added a new Wall Hangings piece: **God Bless This Home Wall Hanging** (filet crochet on a pink board).
- Fixed a bug where the "more on the way" placeholder note kept showing under the Jewelry and Wall Hangings filters even once those categories had real products in them.

## 2026-09-18

- Fixed a missing `<meta name="viewport">` tag that made phones render the page at desktop width and shrink it down, which also silently disabled the site's mobile CSS.
- Fixed the mobile header so the nav drops to its own horizontally-scrollable row instead of overlapping the logo and "Commission a Piece" button.
- Restored the full site content after an earlier commit accidentally replaced `index.html` with a GSAP test snippet, wiping out the real page.
- Replaced that leftover GSAP test code with an actual scroll-reveal effect (category tiles, product/feature/class cards, the About timeline, and the contact card fade in on scroll), respecting `prefers-reduced-motion`.
- Fixed category tile counts overlapping their labels on the Home page.
- Added a missing `<meta charset="UTF-8">`, which fixed mangled curly quotes/apostrophes (e.g. "Kayla's Creations").
- Added the live GitHub Pages link to the README.
- Minor wording tweaks to the About section.

## 2026-09-16

- Added Wall Hangings and Jewelry pieces; updated About page photos.

## 2026-09-14

- Initial site: landing page and README.
