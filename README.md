# Lakshadweep, 12-18 December 2026

A single-file 3D travel site (Three.js, no build step). Everything is in `index.html`.

## Host it on GitHub Pages
1. Create a new public repository, for example `lakshadweep-trip`.
2. Upload `index.html` (and this README) to the repository root.
3. Go to Settings > Pages. Under "Build and deployment", choose "Deploy from a branch", pick `main` and `/ (root)`, then Save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/lakshadweep-trip/`.

## Editing later
Trip content (days, budget, island notes) sits near the top of the `<script>` in `index.html`, in the `DAYS`, `BUDGET` and `INFO` objects. Photos live in the `PHOTOS` object as embedded images, keyed by the tile caption.
