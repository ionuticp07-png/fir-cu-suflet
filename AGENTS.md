# AGENTS.md

## Architecture

Single static HTML file (`index.html`) with inline `<style>` — no build tooling, no JavaScript, no backend. This is intentional: the site is a static marketing/landing page for a handmade goods shop with no dynamic data or persistence needs.

## Key directories

- `index.html` — all markup and styles for the page (nav, hero, about, product catalog, gallery, contact, footer)
- `images/` — static image assets referenced by the hero background and gallery `<img>` tags; currently empty and needs real product photos added

## Conventions

- Keep styles inline in the single `<style>` block in `index.html`; do not introduce a build step or CSS framework unless the site's scope grows significantly.
- Product listing in `.products` and photos in `.gallery` are plain markup — add new cards/images by copying the existing `.card` / `<img>` pattern.
- Content is in Romanian; keep new copy consistent with that language.

## Non-obvious decisions

- No JavaScript is used; the "Comandă pe WhatsApp" button is a plain `wa.me` link, which is sufficient for a WhatsApp-based ordering flow without needing a form or backend.
