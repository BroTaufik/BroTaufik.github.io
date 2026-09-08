# UPSHIFT Portal · NICTSeD 2026

Navigation dashboard for the UPSHIFT semifinal web deck.
SMK St Bernadette's Convent · Perak Darul Ridzuan · AEB2064.

**Live:** https://brotaufik.github.io/

## What it does
A side panel lists all 42 slides grouped into the deck's 8 acts. Clicking a slide drives the deck
in the embedded frame, so the panel stays on screen and acts as a permanent Home. The panel and the
deck stay in sync in both directions: advancing inside the deck highlights the matching slide in the panel.

- **Home** returns to slide 1 · **‹ ›** step between slides · **/** focuses the search box
- **Search** filters the 42 slides by title or act
- **Expand all** opens every act at once
- **FAQ** shows the Google Form QR code and how the live-response element works
- **Present** opens the deck full screen in a new tab, without portal chrome, for the actual run

## Links it carries
The GitHub repository link is deliberately not in the panel: the portal is shown on stage, so it carries only what an audience needs.

| | |
|---|---|
| Deck live | https://brotaufik.github.io/upshift-deck/ |
| FAQ form (slide 42 QR) | https://forms.gle/kymW1VEAELBHAVYa9 |
| Slide 42 · QR | https://brotaufik.github.io/upshift-deck/#s42.1 |

`?hub=1` on the deck URL adds a small **Portal** button to the deck itself, so a full-tab deck opened
from here can return. The plain deck URL never shows it, keeping the presentation clean.

## Files
Single self-contained `index.html` (inline CSS and JS, QR embedded as SVG), the four Poppins weights
it uses, and `og.jpg` for link previews. No build step and no external requests.
