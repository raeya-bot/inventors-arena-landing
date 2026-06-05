# The Inventors Arena — Landing Page

A standalone, single-file landing page built in the Inventors Arena brand
(gladiatorial colosseum × modern VC firm). Centerpiece is the founders'
"Meet the Team" intro video.

- **Single file:** `index.html` (CSS + JS embedded, no build step).
- **Separate** from the main Inventors Arena website/Vercel project.

## Run locally
Open `index.html` in a browser, or:
```
npx serve .
```

## Deploy
Static site — drop this folder into a **new** Vercel project (or any static host),
zero config. Keep it separate from the main site project.

## Customize
- **Hero headline / subhead** — in the `<header class="hero">` block.
- **CTA destination** — every "Chat with an Inventor" button uses `href="#contact"`.
  Swap those to your real booking/contact URL if desired.
- **Video** — the one video is the founders' intro (`ed-scott-intro` MP4), served
  from the original site's CloudFront. It's the only video on the page.
