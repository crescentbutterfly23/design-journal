# Design Journal

A daily study of design done well. Each entry breaks down something worth
learning from and distills one reusable principle.

**Live site:** https://crescentbutterfly23.github.io/design-journal/

## What's inside

Three daily streams (toggle between them on the site) plus reference glossaries:

- **Web Design** — a strong website each day, walked section by section.
- **Digital Ads** — a well-crafted ad, broken down hook → message → visual → CTA.
- **Designers** — an exceptional graphic designer (or, on Mondays, a legendary
  studio), studied for their **process** — how they actually work.
- **Glossaries** — Design Terms, Web Tech Basics, and Digital Ads, each term with
  a live example.

## How it works

A static site — no build step. `index.html` reads three data files at runtime:

- `entries.json` — the daily journal entries (`kind`: `site` / `ad` / `designer`).
- `glossary.json` — the three reference glossaries.
- `images/` — screenshots, ad creatives, and designer portraits.

Because the page fetches `entries.json` over HTTP, view it through a static
server (or the live site above) rather than opening `index.html` from disk.

## Credits

Website screenshots and ad stills are shown for study and commentary. Designer
portraits are sourced from Wikimedia Commons under their respective licenses.
