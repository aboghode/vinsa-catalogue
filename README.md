# Vinsa Jewels — Digital Catalogue

Static site, no build step. Netlify publishes the repo root.

- `index.html` — English (toggle to Arabic in the header)
- `ar.html` / `/ar` — Arabic edition (RTL, opens in Arabic)
- `data.js` — all pieces (titles EN/AR, prices, metals, image paths)
- `img/t` thumbnails (640px) · `img/f` full size (1200px)

Updating: re-run `_rebuild.py` then `_arabic.py` in the local `Downloads/Vinsa/catalogue` folder,
then copy `index.html`, `ar.html`, `data.js` and `img/` here and push. Netlify redeploys automatically.
