# prostoponchik.com

Static personal page: one `index.html`, self-hosted fonts, no build step, no trackers.

- Languages: UA/EN via `lang` spans; default follows the browser, choice stored in `localStorage`.
- Theme: system by default, toggle cycles auto → light → dark.
- Hosting: Cloudflare Pages, production branch `main`, build command empty, output directory `/`.
- `_headers`: CSP and security headers for Cloudflare Pages.
- Optional live status: set `STATUS_URL` in `index.html` to a public endpoint returning
  `{"overall": "...", "uptime_seconds": N}`; the footer badge stays hidden otherwise.

Fonts: Unbounded and JetBrains Mono, SIL Open Font License 1.1 (see `fonts/OFL.txt`).
