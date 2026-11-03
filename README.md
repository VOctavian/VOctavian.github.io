# voctavian.github.io

Personal CV landing page — **[voctavian.github.io](https://voctavian.github.io)**

Octavian Vacarciuc — Senior Backend Engineer (PHP, Laravel), Chisinau, Moldova. EU citizen.

## Stack

None. It's a single `index.html` — no build step, no dependencies, no framework.
Vanilla CSS and JS, one external request for Google Fonts (DM Serif Display, DM Sans, JetBrains Mono).

```
index.html    the whole site (markup, styles, scripts)
cv/           downloadable résumé (PDF + plain text)
```

## Running locally

Open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 5173
```

## Notes

- Light and dark themes: follows the system setting, with a toggle in the header.
- Fully responsive, checked at 1440px and 375px.
- Honours `prefers-reduced-motion` — all animation drops out, content stays readable.
- Includes Open Graph tags and schema.org `Person` data for search engines and link previews.

## Previous version

The pre-2026 design is kept under the tag `v1-before-redesign`.

## Contact

[octavian.vacarciuc@gmail.com](mailto:octavian.vacarciuc@gmail.com) · [@MalckolMD](https://t.me/MalckolMD) · [LinkedIn](https://linkedin.com/in/octavian-vacarciuc)
