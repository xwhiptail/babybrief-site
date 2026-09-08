# BabyBrief marketing site

This directory contains the static marketing site, privacy policy, and support page for BabyBrief.

The app repository stays private. GitHub rejected Pages activation on that repository because the current account plan does not support Pages from private repositories. The website is published separately from the public website-only repository [`xwhiptail/babybrief-site`](https://github.com/xwhiptail/babybrief-site).

Copy `site/` and [`.github/workflows/pages.yml`](../.github/workflows/pages.yml) to the public website repository's `main` branch. The workflow deploys `site/` and is gated to run only in `xwhiptail/babybrief-site`. The same canonical files remain in this private app repository, where the publishing job is skipped. Do not copy app source, family data, or other private repository files into the public repository. The public URLs are:

- Marketing: <https://xwhiptail.github.io/babybrief-site/>
- Privacy: <https://xwhiptail.github.io/babybrief-site/privacy.html>
- Support: <https://xwhiptail.github.io/babybrief-site/support.html>

Deployment succeeded and all three URLs returned HTTP 200 on September 8, 2026. Support and privacy requests use [support@tillnext.app](mailto:support@tillnext.app).
