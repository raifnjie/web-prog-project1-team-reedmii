# Quest Explorer - Project 1 - Team reed-mii

## Project 1. Track B: Quest Explorer, Adventure Pack.
Team: Raif Njie, Michael Tewabe

## Live links
- CODD: YOUR-CODD-URL
- GitHub Pages: YOUR-PAGES-URL
- YouTube walkthrough: YOUR-YOUTUBE-URL

## Overview
A static, HTML and CSS-only site where visitors explore a fantasy world:
Home -> World Map -> Mission Detail (checkpoint route) -> Team/About.

## Structure
- `index.html`, `map.html`, `mission.html`, `about.html`
- `css/tokens.css`: colors, type, spacing, timing variables
- `css/base.css`: reset, typography, focus, skip link
- `css/components.css`: nav, buttons, cards, badges, status, timeline, footer
- `css/layout.css`: Grid/Flexbox layouts and breakpoints (480, 700, 1024)
- `css/motion.css`: transitions, transforms, 3 keyframes, reduced motion
- `docs/`: QA notes, dev journal, usability test

CSS load order is the same on every page (tokens, base, components, layout, motion), so variables are defined before they are used.

## Run locally
Open `index.html` in a browser, or use the VS Code Live Server extension.

## Design decisions and trade-offs
- Mobile-first CSS with min-width breakpoints.
- Transforms over top/margin to avoid layout shift.
- Ordered list for the timeline, since order carries meaning.
- No JavaScript, per the project scope, so all interaction is CSS (hover, focus, anchors).

## Accessibility and motion
- Landmarks, one h1 per page, skip link, aria-current on the active nav link.
- 3px gold focus outline with offset on all interactive elements.
- Status uses icon plus text, never color alone.
- Animations only run under `prefers-reduced-motion: no-preference`.

## Testing and QA
See `docs/QA-notes.md` and `docs/usability-test.md`.

## Asset credits
- Cinzel and Inter via Google Fonts (SIL Open Font License)
- Compass emblem: team-made inline SVG

## AI assistance disclosure
We used Claude (Anthropic) to generate starter code and a build plan, then reviewed, edited, and tested it ourselves. (Edit this to describe exactly what you used AI for and what you changed.)

## Team contributions
- Raif Njie: ...
- Michael Tewabe: ...
