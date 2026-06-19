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
- Both checkout buttons are wired to Lemon Squeezy ($9.99/yr annual, $29.99 lifetime),
  with `?embed=1` so they open as an overlay. The 14-day trial is handled in the app
  (no card required), not via a Lemon Squeezy subscription trial.
- Review `privacy.html`, `terms.html`, and `refund.html` before going live.
