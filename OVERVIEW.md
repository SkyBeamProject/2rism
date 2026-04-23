# Overview

A static front-end website built with plain HTML, CSS, and JavaScript.

Structure:

- `Index.html` — entry point and page layout.
- `css/` — stylesheets.
- `JS/` — client-side scripts.
- `Imgs/` — image assets.

The page uses absolute paths for its CSS/JS assets, so opening `Index.html` via `file://` will not load them. Serve the directory with a local web server instead — for example, `python -m http.server` — and visit the printed URL.
