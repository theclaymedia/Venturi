# Venturi — Website Redesign Mockup

A single-page homepage redesign concept for [Venturi](https://www.venturi.cc), a deep tech
company at Utah Tech University (St. George, Utah) working on advanced clean energy
(Venturi Omega, Megawatt Platform, motor generator assembly & testing) and nuclear-powered
robotic vertical farming.

The design adapts the editorial, luxury aesthetic of [lucidmotors.com](https://lucidmotors.com)
— serif display type, full-bleed video heroes, alternating dark/light sections, and a large
structured footer — applied to Venturi's own content and imagery.

## Viewing

It's a static, self-contained page. Either:

- Open `index.html` directly in a browser, **or**
- Serve the folder: `python3 -m http.server 4599` then visit http://localhost:4599

## Structure

- `index.html` — the entire mockup (HTML + CSS + a little JS; Google Fonts loaded via CDN)
- `assets/venturi/` — real Venturi brand assets, product renders, photos, and the
  compressed hero background videos (`energy-hero.mp4`, `farm-hero.mp4`)

All imagery is pulled from Venturi's existing site and inner pages. Hero videos were
compressed to 720p (H.264, no audio) for web delivery.

> Note: this is a static design mockup, not a production build.
