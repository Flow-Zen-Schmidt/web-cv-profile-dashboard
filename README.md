# web-cv-profile-dashboard

Interactive single-page CV / portfolio for **Florian Schmidt — Senior AWS Cloud Engineer**, based in Munich, Germany.

A self-contained, framework-free HTML/CSS/JS page with a dark, animated layout (aurora background, custom cursor, scroll progress, i18n EN/DE toggle).

## Live

Once GitHub Pages is enabled, the site is available at:

```
https://flow-zen-schmidt.github.io/web-cv-profile-dashboard/
```

## Contents

- `index.html` — entry point (redirects to the CV)
- `florian-schmidt-cv.html` — the actual CV / portfolio page

Sections inside the CV:

- About
- Experience
- Building
- Skills
- AWS Certified
- Education & Languages

## Run locally

No build step. Just open the file in a browser:

```bash
open florian-schmidt-cv.html
```

Or serve the folder with any static server, e.g.:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Tech

- Plain HTML / CSS / vanilla JS — no framework, no bundler
- Google Fonts: Fraunces, Schibsted Grotesk, JetBrains Mono
- Lightweight i18n via `data-i18n` attributes (English / Deutsch)

## License

Personal CV content — all rights reserved.
Code/layout may be reused for inspiration; please don't republish the personal content as your own.
