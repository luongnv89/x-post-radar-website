# X Post Radar website

Static marketing site for X Post Radar, a Chrome extension that scores the posts on your X timeline for reply opportunity, in your browser.

Published as a GitHub Pages project site: https://luongnv89.github.io/x-post-radar-website/

![X Post Radar](img/marquee.png)

## Pages

| File | Page |
|------|------|
| `index.html` | Landing page |
| `privacy.html` | Privacy policy |
| `changelog.html` | Release notes |
| `docs.html` | Getting started |

Shared styles live in `css/style.css`; images in `img/`.

## Rules for this site

- No third-party requests: no analytics, cookies, web fonts, CDNs or external scripts. No JavaScript.
- Relative links only, so the site works under the `/x-post-radar-website/` path.
- `.nojekyll` makes GitHub Pages serve the files as they are.
- Each page's body sits inside `<!--email_off-->` … `<!--/email_off-->`, so Cloudflare (in front of luongnv.com) neither rewrites the mailto links nor injects its email-decode script.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000/.
