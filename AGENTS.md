# AGENTS.md

## Architecture

Single static HTML file (`index.html`) with inline `<style>` and minimal inline `<script>` — no build tooling, no backend. This is intentional: the site is a static marketing/landing page for a handmade goods shop with no dynamic data or persistence needs.

## Key directories

- `index.html` — all markup, styles, and minimal JavaScript for the page (nav, hero, about, product catalog, gallery, contact, footer)
- `images/` — static image assets referenced by the hero background and gallery `<img>` tags; currently empty and needs real product photos added

## Conventions

- Keep styles inline in the single `<style>` block in `index.html`; do not introduce a build step or CSS framework unless the site's scope grows significantly.
- Keep JavaScript minimal and inline in the single `<script>` block for enhancements like smooth scrolling, fade-in animations, and hover effects.
- Product listing in `.products` and photos in `.gallery` are plain markup — add new cards/images by copying the existing `.card` / `<img>` pattern.
- Content is in Romanian; keep new copy consistent with that language.

## Non-obvious decisions

- Minimal JavaScript is used for UX enhancements (smooth scroll navigation, product card animations, gallery hover effects) without needing a framework or backend.
- The "Comandă pe WhatsApp" button is a plain `wa.me` link, which is sufficient for a WhatsApp-based ordering flow without needing a form or backend.
