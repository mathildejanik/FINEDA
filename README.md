# FINEDA website (static snapshot)

Static copy of https://www.fineda.org, mirrored from the published Webflow site on 2026-09-13.
The Webflow project itself lives in Webflow; this repo is a backup of the rendered output.

- `index.html` is the whole site (single page with anchor sections).
- `assets/` holds the CSS, JS, images, PDFs and logos that were served from Webflow's CDN, rewritten to relative paths.
- Fonts still load from Google Fonts at runtime.

Known limitations of a static snapshot:

- The contact form posts to Webflow's form handler and will not submit from this copy without a new backend.
- Webflow interactions/animations are baked into the bundled JS and work as published, but cannot be edited without Webflow.

Serve locally with any static server, for example:

```bash
npx serve .
```
