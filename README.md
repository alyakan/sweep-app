# Sweep — website & releases

This **public** repo hosts the [Sweep](https://alyakan.github.io/sweep-app/) landing
page (GitHub Pages) and the notarized macOS app downloads (GitHub Releases).

The app's source lives in a separate private repository.

- **Site:** https://alyakan.github.io/sweep-app/
- **Download:** see [Releases](https://github.com/alyakan/sweep-app/releases/latest)

## Maintenance

- The site is plain static HTML/CSS at the repo root, served by GitHub Pages from the
  `main` branch root.
- To ship a new app version: build the notarized DMG, then publish it as a new Release
  (the Download button links to `releases/latest`).
- `BUY_URL_ANNUAL` and `BUY_URL_LIFETIME` in `index.html` are placeholders — replace
  them with the Lemon Squeezy checkout URLs for the $10/yr and $30 lifetime variants
  once the store is set up.
- Review `privacy.html`, `terms.html`, and `refund.html` before going live.
