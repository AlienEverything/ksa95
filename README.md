# Aurora Odyssey

Aurora Odyssey is a maximalist cosmic playground that begins with a mission control landing page and branches into five
standalone labs. Each portal amplifies spectacle with practical tooling—mission planning, generative math, particle
harmonics, synesthetic audio, and archival research all sync through shared storage and downloadable manifests.

## Contents
- `index.html` — mission control dashboard with live telemetry, quick itinerary builder, call-sign sync, and deep links to
  every lab.
- `mission-planner.html` — multi-step wizard for assembling expeditions with timeline canvas, resource budgets, shareable
  links, and local history storage.
- `knowledge-archive.html` — filterable dossier terminal featuring searchable tags, year sliders, constellation scatter
  plots, and transcript modals.
- `portal-fractal.html` — superformula forge with reduced-motion awareness, preset storage, PNG snapshots, and constellation
  overlays.
- `harmonic-field.html` — particle swarm composer sporting persistence/colour controls, metrics, presets, and image export.
- `synesthetic-lab.html` — Web Audio pad sequencer with tempo automation, palette management, JSON export, and saved
  swatch deck.

## Getting Started
Open `index.html` in any modern browser to access mission control. From there, launch any lab or open the planner/archive
portals. All pages are single-file static documents; no build tooling is required.

## Publishing with GitHub Pages
1. Push this repository to your GitHub account at [`AlienEverything/ksa95`](https://github.com/AlienEverything/ksa95):
   ```bash
   git remote add origin git@github.com:AlienEverything/ksa95.git
   git push -u origin main
   ```
   (If the remote already exists, update it with `git remote set-url origin …` before pushing.)
2. In the GitHub repository, open **Settings → Pages**, choose the `main` branch, and set the source to the root directory.
3. After Pages finishes deploying, your site will be available at
   `https://alieneverything.github.io/ksa95/`, serving `index.html` at the root and linking to every additional lab page.

## Accessibility & Sync Notes
- All animations pause automatically when `prefers-reduced-motion` is detected; controls allow manual playback.
- Canvas elements include ARIA labels describing their visuals, and keyboard shortcuts are available for key interactions.
- Planner, fractal, harmonic, and synesthetic labs persist presets to `localStorage`, while call-sign data syncs between
  mission control and the planner.
