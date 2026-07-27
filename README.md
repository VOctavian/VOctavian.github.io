# voctavian.github.io

Personal CV landing page — **[voctavian.github.io](https://voctavian.github.io)**

Octavian Vacarciuc — Senior PHP Engineer & Team Lead, Chisinau, Moldova.

## Stack

None. It's a single `index.html` — no build step, no dependencies, no framework.
Vanilla CSS and JS, one external request for Google Fonts (Inter + JetBrains Mono).

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

- Fully responsive, verified at 1440px and 375px.
- Honours `prefers-reduced-motion` — all animation drops out, content stays readable.
- Animations are CSS/SMIL plus a small canvas particle field; no libraries.

## Contact

[octavian.vacarciuc@gmail.com](mailto:octavian.vacarciuc@gmail.com) · [@MalckolMD](https://t.me/MalckolMD) · [LinkedIn](https://linkedin.com/in/octavian-vacarciuc)
