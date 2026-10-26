# fewerlabs.dev

The Fewer Labs homepage: one static HTML page, no build step.

- `index.html`: the page (styles and scripts inline)
- `art/`: game artwork for the cards
- `fonts/`: Geist and Geist Mono, self-hosted (SIL Open Font License, see `fonts/LICENSE-OFL.txt`)
- `og.png`: the 1200×630 link-preview image
- `robots.txt`, `sitemap.xml`, `site.webmanifest`: crawler and install files
- `vercel.json`: cache headers and the `www` → apex redirect

## Run locally

```bash
python3 -m http.server 5196
```

## Deploy

Import this repo into Vercel (no framework, no build command) and add `fewerlabs.dev` and `www.fewerlabs.dev` as domains.
