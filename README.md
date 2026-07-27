# Fir cu Suflet Handmade

A single-page marketing site for a Romanian handmade crafts shop (bracelets, keychains, dolls, macramé), built with plain static HTML and CSS.

## Technologies

- Static HTML5 + CSS (no build step, no framework)

## Structure

- `index.html` — the entire site (hero, about, product catalog, gallery, contact)
- `images/` — place product photos here referenced by the gallery and hero background (see below)

## Running locally

Open `index.html` directly in a browser, or serve the folder with any static file server, e.g.:

```bash
npx serve .
```

## Images

The hero background (`images/1.png`) and gallery photos (`images/bratari.jpg`, `images/set-cuplu.jpg`, `images/breloc.jpg`, `images/breloc-personalizat.jpg`, `images/papusa.jpg`, `images/papusa-personalizata.jpg`, `images/ornament-auto.jpg`, `images/macrame.jpg`) are not included and need to be added to the `images/` folder before the gallery and hero will display images.
