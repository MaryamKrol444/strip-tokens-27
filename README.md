# strip-tokens-27

Hindi-language landing page: **मुफ़्त StripChat टोकन – सर्वश्रेष्ठ कानूनी तरीके**

Educational, 18+ SEO landing page (~8,300 words, Devanagari-first) covering seven
legal ways to obtain free StripChat tokens, with a detailed scam-warning section
targeted at Indian users.

## Live

Once GitHub Pages is enabled for this repository, the page is served at:

- https://maryamkrol444.github.io/strip-tokens-27/

## Files

| Path | Purpose |
| --- | --- |
| `index.html` | Self-contained page (embedded CSS, JSON-LD schema, OG tags) |
| `images/` | 7 illustrations, each as WebP + JPG fallback via `<picture>` |
| `.nojekyll` | Disables Jekyll so the site is served as plain static files |

## Local preview

```bash
python3 -m http.server 8000 --bind 0.0.0.0
# open http://localhost:8000/
```

## Publishing (GitHub Pages)

Settings → Pages → Build and deployment → Source: **Deploy from a branch**
→ Branch: **main**, folder: **/ (root)** → Save. First build takes ~1 minute.

## Note on canonical URLs

`<link rel="canonical">`, the `hreflang` alternates and the Open Graph URLs in
`index.html` currently point at `https://striptokens.live/`. If this page is
served from `github.io` instead of that custom domain, update those tags — or
attach `striptokens.live` as a custom domain in Settings → Pages.
