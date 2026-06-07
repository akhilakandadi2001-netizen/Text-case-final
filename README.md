# TextShift — Free Online Text Case Converter

A lightweight, privacy-first text utility tool built as a single HTML file. No frameworks, no build step, no backend.

🔗 **Live demo:** https://textshift.tools/ *(replace with your GitHub Pages URL)*

---

## Features

- **10 case conversions:** UPPER, lower, Sentence, Title, camelCase, PascalCase, snake_case, kebab-case, iNVERSE, aLtErNaTe
- **Real-time stats:** word count, character count, sentences, lines, paragraphs
- **One-click copy** to clipboard with toast notification
- **Zero data sent** — all processing happens in the browser (pure JavaScript)
- **AdSense-ready** — 3 ad slots pre-commented, just swap in your Publisher ID
- **SEO-optimised** — meta tags, canonical URL, FAQ schema-friendly content
- **Mobile responsive** — works on all screen sizes

---

## File Structure

```
textshift/
├── index.html      ← entire app (HTML + CSS + JS in one file)
└── README.md
```

No dependencies. No npm. No build tools.

---

## How to Deploy

### Option 1 — GitHub Pages (Free)

1. Fork or clone this repo
2. Go to **Settings → Pages**
3. Set source to `main` branch, root folder
4. Your site will be live at `https://yourusername.github.io/textshift/`

### Option 2 — Any Static Host

Upload `index.html` to Netlify, Vercel, Cloudflare Pages, or any web host. Done.

---

## Enabling Google AdSense

1. Apply at [adsense.google.com](https://adsense.google.com) with your live site URL
2. After approval, uncomment the `<script>` tag in `<head>` and replace `ca-pub-XXXXXXXXXXXXXXXX` with your Publisher ID
3. Uncomment each `<ins>` ad slot block and replace `data-ad-slot="XXXXXXXXXX"` with your Ad Unit IDs
4. There are **3 slots** ready: Top Leaderboard, Mid-Page Rectangle, Bottom Leaderboard

> ⚠️ Do NOT activate AdSense before your site is approved. Keep ad slots commented until then.

---

## Customisation

| What to change | Where |
|---|---|
| Site URL | `<link rel="canonical">` and OG tags in `<head>` |
| Contact email | "About" and "Privacy" sections |
| Brand name | `.logo` in header and footer |
| Privacy policy date | `<em>Last updated: ...</em>` in privacy section |
| More Tools links | `.tools-grid` section (currently placeholder `#` links) |

---

## Tech Stack

- Pure HTML5, CSS3, Vanilla JavaScript
- Google Fonts: Syne, Instrument Sans, DM Mono (loaded via CDN)
- No external JS libraries

---

## License

MIT License — free to use, modify, and deploy for personal or commercial projects.

---

## Contributing

Pull requests welcome! Ideas for new tools: word frequency counter, remove duplicate lines, lorem ipsum generator, Base64 encode/decode.
