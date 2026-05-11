# The Atrium Mission

Social media owned by its users. No algorithmic manipulation. No data brokering. End-to-end encryption where it matters. Community-governed rules. Open source. Resistant by architecture, not by promise.

**Live site:** [theatriummission.com](https://theatriummission.com)
**Status:** Phase 0 — Founding Circle open

---

## About this repository

This repo contains the source for the public-facing Atrium Mission website. The site is a single-page static HTML application deployed via Cloudflare Pages.

## Stack

- Single `index.html` — all CSS and JS inline
- Google Fonts (Fraunces, Manrope, JetBrains Mono)
- No build step, no dependencies
- Hosted on Cloudflare Pages with auto-deploy from `main`

## Branches

- **`main`** — stable, production. Auto-deploys to [theatriummission.com](https://theatriummission.com).
- **`dev`** — in-progress changes. Auto-deploys to a Cloudflare preview URL for testing before merging.

## Files

| File | Purpose |
|---|---|
| `index.html` | The website itself |
| `atrium-mark.svg` | Logo mark (square + A) |
| `atrium-logo-compact.svg` | Mark + ATRIUM wordmark |
| `atrium-logo-full.svg` | Full lockup with subtitle |

## License

All rights reserved. The Atrium Mission, 2026.