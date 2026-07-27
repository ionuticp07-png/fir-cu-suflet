# Fir cu Suflet Handmade

A single-page marketing site for a Romanian handmade crafts shop (bracelets, keychains, dolls, macramé), built with static HTML, CSS, and minimal inline JavaScript.

## Technologies

- Static HTML5 + CSS + minimal inline JavaScript (no build step, no framework)

## Structure

- `index.html` — the entire site (hero, about, product catalog, gallery, contact)
- `images/` — place product photos here referenced by the gallery and hero background (see below)

## Running locally

Open `index.html` directly in a browser, or serve the folder with any static file server, e.g.:

```bash
npx serve .
```

## Images

The hero background (`images/1.png`) and gallery photos need to be added to the `images/` folder before the gallery and hero will display images.

## Features

- **Smooth scroll navigation** — click nav links for smooth animated scroll to sections
- **Product card animations** — cards fade in and slide up as they come into view
- **Gallery hover effects** — images scale up on hover for better interactivity
- **WhatsApp integration** — direct ordering via WhatsApp links
