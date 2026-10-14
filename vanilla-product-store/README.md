# FORMA — Vanilla JavaScript Product Store

A responsive storefront using only HTML, CSS, and vanilla JavaScript. Product data loads from the public DummyJSON Products API.

## Run it
1. Extract the ZIP.
2. Open `index.html` in a browser. If your browser blocks requests from `file://`, run a local static server:
   - VS Code: install/use Live Server, then click **Go Live**.
   - Or run `python -m http.server 8000` in this folder and visit `http://localhost:8000`.

## Features
- Responsive product cards: 4 columns on desktop, 2 on tablet, 1 on mobile.
- Live API fetch with loading and error states.
- Search, category filtering, sorting, and load-more.
- Demo bag counter and favourites.
- No frameworks, libraries, or API key.

API docs: https://dummyjson.com/docs/products
Note: this is a front-end demo; bag/favourites are not persisted and product prices/stock are sample data.
