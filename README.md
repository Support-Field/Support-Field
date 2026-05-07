# SupportField — Anonymous Project Page

Static project page for the NeurIPS 2026 anonymous submission *Denoising as
Support-Manifold Repair: What 3D Scene Diffusion Exposes and What It Does
Not* (project alias: SupportField).

## Files

- `index.html` — single-page site (Bulma CSS via CDN, no build step).
- `static/css/style.css` — page-specific styles on top of Bulma.
- `static/images/` — paper figures used on the page.
- `.nojekyll` — disables Jekyll on GitHub Pages so paths under `static/`
  work without underscores being rewritten.

## Local preview

```bash
cd webpage
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

Push the contents of this directory to the `gh-pages` (or root) branch of
the anonymous GitHub Pages repository. The page assumes serving from
either the repo root or a project subpath.

## Anonymity

- No author names or affiliations.
- Single external link points to the anonymous code repo on
  `anonymous.4open.science`.
- No analytics, no fonts beyond Google Fonts, Bulma, and FontAwesome
  CDN-hosted assets.
