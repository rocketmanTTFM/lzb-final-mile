# La-Z-Boy Final Mile — Carrier Overview

This folder is the **carrier-facing website** — self-contained, ready to deploy to GitHub Pages.

Contents:

```
site/
├── index.html       ← the map + rate structure + DFS calculator, all inlined
├── .nojekyll        ← tells GH Pages to skip Jekyll processing
└── README.md        ← you are here
```

That's it. One HTML file with everything a carrier needs to understand the program:
- 36-market Z-Dock network map with live/planned distinction
- Flat truck rate + 150-driving-mile explainer
- Live interactive DFS calculator
- Confidentiality banner
- No backend, no build step, no dependencies beyond a web browser

See `../GITHUB_PAGES_SETUP.md` in the project root for step-by-step deployment instructions.
