# joybarua93.github.io

Developer site for Games by Joy Barua. Plain HTML and CSS, served by GitHub Pages from the `main` branch root. No build step.

- `index.html`: home page
- `privacy/index.html`: privacy policy
- `style.css`: shared styles

## Adding app-ads.txt later

Once you have your AdMob publisher ID, create `app-ads.txt` at the repo root with this one line (replace the X's with your ID), then commit and push:

```
google.com, pub-XXXXXXXXXXXXXXXX, DIRECT, f08c47fec0942fa0
```

It will be served at https://joybarua93.github.io/app-ads.txt.

## Fonts

Fraunces (900) and Nunito (400, 700, 800) are self-hosted in `fonts/` as Latin-subset woff2 files, loaded in `style.css` with `@font-face`. Both are licensed under the SIL Open Font License 1.1. The page makes no requests to Google.
