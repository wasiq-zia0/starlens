# Starlens Arctic-4 — Landing Page

A single-page, self-contained landing site for the Starlens Arctic-4 deployable
optical ground station. It's built to explain — in plain language, for someone
who has never heard of an optical ground station — what the machine does and why
it matters, then show it off.

The page is a scroll-driven journey from orbit down to the Arctic ice:

- **Hero** — a realistic, observatory-style night scene (canvas): starfield,
  a satellite glint, and a volumetric *laser downlink* to a ground station.
- **What is it** — a plain-language explainer with a looping beam diagram.
- **Radio vs. light** — an animated bandwidth comparison.
- **How a downlink happens** — the three steps: acquire, lock & downlink, deliver.
- **Meet Arctic-4** — the product render with annotated anatomy callouts.
- **Why the North** — polar-orbit globe animation and the Canada context.
- **Specs / Coming soon** — at-a-glance figures and a notify form.

## Files

- `index.html` — fully self-contained. Fonts (Space Grotesk / Manrope), the
  product renders, and all animation (canvas + inline SVG) are inlined, so there
  are no external requests. Open it directly in a browser or serve it from any
  static host (e.g. GitHub Pages).
- `CNAME` — custom domain (`starlens.ca`).

Animations respect `prefers-reduced-motion`.
