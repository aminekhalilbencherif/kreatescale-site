# kreatescale.com

Static site for KreateScale. No build step: Netlify serves this folder as is.

- `index.html` — the whole page (styles and script inline)
- `assets/logos/` — client logos, black on transparent
- `assets/ads/NN-loop.mp4` — 8-second silent loops shown on the work wall
- `assets/ads/NN.mp4` — full ads opened when a tile is clicked
- `assets/ads/NN-poster.jpg` — still frames shown before a loop loads

To add or swap an ad, replace the three `NN` files and keep the numbering.

## Pages

- `/` — `index.html`, the main landing page (full service)
- `/work` — `work/index.html`, the production-only page: ads wall, production process, booking.
  It is not linked from the main page and carries a `noindex` tag. To add ads to the wall,
  drop the three `NN` files into `assets/ads/` and raise `ADS` at the top of the page's script.
