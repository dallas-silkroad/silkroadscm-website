# silkroadscm.com

Static site for Silk Road SCM, served by Cloudflare Pages from this repo.

- Edit any file, commit to `main`, and Cloudflare deploys it in about a minute. No build step.
- `_redirects` holds the www-to-bare-domain rule and legacy article paths.
- `_headers` sets cache lifetimes (pages 5 minutes, images 1 year).
- Favicon set: `favicon.ico`, `favicon-16x16.png`, `favicon-32x32.png`, `apple-touch-icon.png`, `android-chrome-*.png`, `site.webmanifest`. Source logo: transparent 2400px PNG (keep the master outside the repo).
- Pages: `/` (index.html), `/book/`, `/partners/`, `/portal/` (redirect to the partner portal), `/dispatch/` (newsletter archive), `privacy.html`, `terms.html`.
