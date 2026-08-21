# BIA Limited — Business Investment Advisory

Corporate website for BIA Limited (bia.co.ke): transaction-focused infrastructure advisory —
project structuring, credit enhancement and capital mobilization across emerging markets.

## Stack
Plain HTML/CSS/JS (no framework). Contact form uses **Netlify Forms**.

## Netlify settings
- Build command: `npm run build` (from `netlify.toml` — copies pages + assets into `dist/`)
- Publish directory: `dist`
- Leave the Netlify dashboard build fields **blank** so `netlify.toml` wins.

## Pages
`index.html` (home) · `about.html` (about + leadership team) · `services.html` ·
`sectors.html` · `projects.html` · `contact.html` · `success.html` (form thank-you) · `404.html`

## Local preview
```bash
npm run build && python3 -m http.server -d dist 8080
```
