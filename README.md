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
- Both checkout buttons link to Lemon Squeezy's hosted checkout ($9.99/yr annual,
  $29.99 lifetime), opening in a new tab. We deliberately do NOT use the embedded
  overlay (`?embed=1` + lemon.js): the embed runs Stripe in an iframe, and browsers
  blocking third-party storage break the payment step ("a processing error occurred").
  The 14-day trial is handled in the app (no card required), not via a Lemon Squeezy trial.
- Review `privacy.html`, `terms.html`, and `refund.html` before going live.
