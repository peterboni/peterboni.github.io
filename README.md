# peterboni.github.io

Static placeholder landing page. No build step, no dependencies.

## Files
- `index.html` - the page
- `styles.css` - all styling, light/dark theme tokens
- `assets/peter-boni.webp` - portrait (760px) + `peter-boni-2x.webp` (1520px retina)
- `assets/peter-boni.jpg` - JPEG social-sharing preview
- `.nojekyll` - skip Jekyll processing on GitHub Pages

## Deploy
Push to the repo, then Settings > Pages > Source: Deploy from branch, `main` / root.

## Notes
- Dark theme is default; the toggle (top right) persists the choice in `localStorage` under `pb-theme`.
- Fonts (Space Grotesk, JetBrains Mono) load from Google Fonts. To self-host, download the woff2 files into `assets/fonts/` and swap the `<link>` for `@font-face` rules.
