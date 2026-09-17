# DJAQ™ User Manual — GitHub Pages edition

A self-contained, static HTML manual, ready to publish with GitHub Pages.

## Publishing

1. Push the contents of this folder to the root of a GitHub repository (any branch, e.g. `main`).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Pick the branch (e.g. `main`) and folder `/ (root)`, then **Save**.
5. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

The included `.nojekyll` file tells GitHub Pages to serve the files as-is, skipping Jekyll processing.

## Files

- `index.html` — the manual itself (GitHub Pages serves this automatically at the site root).
- `DJAQ-User-Manual.html` — an identical copy, conveniently named for opening locally without a server.
- `favicon.svg` — browser tab icon (now wired up via a `<link rel="icon">` tag).
- `og.png` — social/link-preview image (now wired up via Open Graph and Twitter Card meta tags).
- `.nojekyll` — disables Jekyll processing on GitHub Pages.

## Notes

The manual is entirely self-contained (inline CSS/JS, no external requests, no build step). Chapter links use anchors such as `#chapter-05`. A search box in the header filters chapters client-side.
