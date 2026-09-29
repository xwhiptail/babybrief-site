# Nuzzlebook public site

This is the static marketing, support and privacy site for Nuzzlebook. It keeps the existing GitHub Pages address so published links remain valid:

- https://xwhiptail.github.io/babybrief-site/
- https://xwhiptail.github.io/babybrief-site/support.html
- https://xwhiptail.github.io/babybrief-site/privacy.html

The private app repository and public website repository are separate. Publish only `site/` and `.github/workflows/pages.yml` to `xwhiptail/babybrief-site`. The workflow deploys `site/` on pushes to main. Never include app source, personal records, signing material or private build files.

The September 29, 2026 refresh uses the original Paint bear icon and wordmark, Nuzzlebook Hand heading font, warm cream/cocoa colors and “Little logs. More cuddles.” copy. Screens are native 1284 × 2778 simulator captures with synthetic data, including medicine, reminder configuration and dark mode. Support covers notification taps and the Home Screen widget; privacy explains local reminders and app-group storage.

Preview locally with `python3 -m http.server 8765 --directory site`. Version query strings on images and CSS use content hashes; refresh them whenever those files change.

Verification: static local-link, asset, image-alt and heading checks. App screenshots are checked separately at native resolution. Deployment details are recorded in the release delivery report.
