# ⚠️ DO NOT DELETE THIS REPOSITORY

## Purpose
This repository exists **solely** to forward the domain `pratyoosh.site` to `https://pratyoo.sh` using GitHub Pages.

It is **not** a project, app, or website. It contains no meaningful code.

---

## How It Works
- `pratyoosh.site` DNS A records point to GitHub Pages servers (`185.199.x.x`)
- GitHub Pages serves this repo on `pratyoosh.site` (via the `CNAME` file)
- `index.html` immediately 301-redirects all visitors to `https://pratyoo.sh`
- `robots.txt` tells search engines not to index this site

## Domain Forwarding Map
```
pratyoosh.site  ──→  https://pratyoo.sh
```

## ⚠️ Warning
- **Do not delete** this repo — deleting it will break `pratyoosh.site` entirely
- **Do not make private** — GitHub Pages requires a public repo on free accounts
- **Do not edit `CNAME`** — it must contain exactly `pratyoosh.site`
- **Do not remove `index.html`** — it is the actual redirect mechanism

## Files
| File | Purpose |
|------|---------|
| `index.html` | Redirects visitors to `https://pratyoo.sh` |
| `CNAME` | Tells GitHub Pages to serve this on `pratyoosh.site` |
| `robots.txt` | Blocks all search engine crawlers from indexing |
| `README.md` | This file — documentation only |

## SEO / Indexing
This site is intentionally blocked from search engines via:
- `robots.txt` with `Disallow: /`
- `<meta name="robots" content="noindex, nofollow">` in `index.html`
- `X-Robots-Tag` is not set (GitHub Pages limitation) but the above two are sufficient

---
*Last updated: May 2026 | Owner: @pratyooshbhatia*
