# Aurora Odyssey

Aurora Odyssey is a speculative exploration experience that invites visitors to chart luminous futures across immersive,
responsive storyworlds. The experience is rendered as a single-page showcase located in `index.html`, combining
multi-layered gradients, glassmorphic surfaces, animated canvases, and interactive controls to simulate a cosmic voyage.

## Contents
- `index.html` — the primary interface for the Aurora Odyssey expedition, featuring:
  - A responsive navigation bar with constellation toggles
  - Hero briefing with animated statistics and glass panels
  - Mission, atlas, experience, and lounge sections populated with interactive elements
  - A custom canvas-based orbital map and dynamically updating footer
  - Persistent constellation controls with reduced-motion friendly behavior

## Getting Started
Open `index.html` in any modern browser to explore the full experience. For best results, use a device capable of
rendering CSS backdrop filters and canvas animations.

## Publishing with GitHub Pages
1. Push this repository to your GitHub account at [`AlienEverything/ksa95`](https://github.com/AlienEverything/ksa95):
   ```bash
   git remote add origin git@github.com:AlienEverything/ksa95.git
   git push -u origin main
   ```
   (If the remote already exists, update it with `git remote set-url origin …` before pushing.)
2. In the GitHub repository, open **Settings → Pages**, choose the `main` branch, and set the source to the root directory.
3. After Pages finishes deploying, your site will be available at
   `https://alieneverything.github.io/ksa95/`, serving the content directly from `index.html`.

## Accessibility
- Constellation visuals can be toggled on or off, and the chosen preference is remembered for future visits.
- Motion-intensive orbital map effects pause automatically for visitors who prefer reduced motion.
