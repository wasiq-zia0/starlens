# Starlens Arctic-4 — Landing Page

A single-page, self-contained landing site for the Starlens Arctic-4 deployable
optical ground station. It's built to explain — in plain language, for someone
who has never heard of an optical ground station — what the machine does and why
it matters, then show it off.

The page is a scroll-driven journey from orbit down to the Arctic ice:

- **Hero** — a live starfield with an animated satellite-to-ground *laser
  downlink* (the core idea: satellites send data down as a beam of light).
- **What is it** — a plain-language explainer with a looping beam diagram.
- **Radio vs. light** — an animated bandwidth comparison.
- **How a downlink happens** — the three steps: acquire, lock & downlink, deliver.
- **Meet Arctic-4** — the product render with annotated anatomy callouts.
- **Why the North** — polar-orbit globe animation and the Canada context.
- **Specs / Coming soon** — at-a-glance figures and a notify form.

## Files

- `index.html` — fully self-contained. Fonts (Newsreader / Archivo / IBM Plex
  Mono), the product renders, and all animation (canvas starfield + inline SVG)
  are inlined, so there are no external requests. Open it directly in a browser
  or serve it from any static host (e.g. GitHub Pages).
- `CNAME` — custom domain (`starlens.ca`).

Animations respect `prefers-reduced-motion`.
