# La Casa de Data

Landing page for a data-science learning platform. A single `index.html` with the CSS and JS inside it, so there is no build step.

## Run locally
Open `index.html` in a browser, or run `python3 -m http.server` and visit http://localhost:8000.

## Publish on GitHub Pages
1. Create a repo and push these files to the `main` branch.
2. Go to **Settings → Pages**, set **Source** to `Deploy from a branch`, choose `main` and `/ (root)`, then save.
3. Your site goes live at `https://<username>.github.io/<repo>/`.

## Hero artwork
Add your own artwork at `assets/hero.png` (a transparent PNG or a dark-background image of the hooded figures, about 1600×1200). The page fades it in on the right side. Without it, the red moon and gradients still render.
