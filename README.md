# Mavis’s Costume Chaos

Self-contained Atelier 35 release adapted for Genially. All artwork is embedded. The outer page scales a fixed 1440 × 1000 stage to the available iframe, preserving all positions and proportions. No external libraries or asset hosting required.

Published URL: https://natalifilonovets.github.io/show/

Paste `genially-embed.html` into Genially’s external-content iframe field. Use the 1440 × 1000 aspect ratio (36:25); the whole stage stays visible at other ratios with dark margins. Enable autoplay/fullscreen permissions. Browser policy may still require a click for Mavis’s voice. Mouse/touch puzzle dragging runs inside the scaled frame.

GitHub Pages source: **GitHub Actions**. `.github/workflows/pages.yml` deploys on pushes to `main`.

`game.html` contains the complete game; `index.html` is the scaling wrapper. Update the game by rebuilding with `tools/build-genially.py` from the source project and copying the resulting files here.
