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
- `BUY_URL` in `index.html` is a placeholder — replace it with the Lemon Squeezy
  checkout URL once the store is set up.
- Review `privacy.html`, `terms.html`, and `refund.html` before going live.
