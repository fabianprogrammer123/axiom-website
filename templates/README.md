# Website Templates

Reusable, responsive templates for small‑business sites. Write directly to /home/node/website/ and changes are live at http://136.117.149.33/.

## Templates

- basic/ — Minimal, modern dark UI with responsive grid, hero, features, about, and contact inline form. Includes:
  - index.html example structure
  - style.css (mobile‑first, accessible contrast)

## How to Use

1) Copy the template into a new directory for a client/demo:

   - Example: /home/node/website/<slug>/
   - Example: /home/node/website/salon-bloom/

2) Reference the shared CSS to avoid duplication:

   <link rel="stylesheet" href="/templates/basic/style.css">

3) Customize copy, logo text, and CTAs in your new index.html.

4) Visit: http://136.117.149.33/<slug>/ to verify.

## Conventions

- Keep assets lightweight; prefer emojis or simple SVGs over large images.
- Use clear, conversion‑focused CTAs (WhatsApp, booking, quote request).
- Commit after each change:

  cd /home/node/website && git add -A && git commit -m "Describe change" && git push

## Roadmap

- Add light theme variant
- Add service list/price table partial
- Add testimonial cards component
- Add navbar logo + brand color variables
