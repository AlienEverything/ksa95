# Aurora Odyssey

Aurora Odyssey is a multi-page cosmic showcase that starts with a grounded product-style landing page before exploding
into three standalone HTML labs. Each portal focuses on a different type of maximal spectacle: math-driven fractals,
kinetic particle harmonics, and an audio-reactive synesthetic instrument.

## Contents
- `index.html` — mission control with a classic navigation flow, hero story, itinerary, and quick links into every portal.
- `portal-fractal.html` — renders a Johan Gielis superformula on Canvas with symmetry sliders, play/pause control, and
  randomisation.
- `harmonic-field.html` — animates hundreds of coupled oscillators with pointer/touch attractors, keyboard shortcuts, and
  reduced-motion aware playback.
- `synesthetic-lab.html` — turns Web Audio pads into chromatic chords, feeding an audio spectrum visualiser and palette
  generator.

## Getting Started
Open `index.html` in any modern browser to begin the experience. Each portal link opens in the same tab, and you can use
`← Mission Control` from any lab to return to the entry page. All pages run without external build tooling.

## Publishing with GitHub Pages
1. Push this repository to your GitHub account at [`AlienEverything/ksa95`](https://github.com/AlienEverything/ksa95):
   ```bash
   git remote add origin git@github.com:AlienEverything/ksa95.git
   git push -u origin main
   ```
   (If the remote already exists, update it with `git remote set-url origin …` before pushing.)
2. In the GitHub repository, open **Settings → Pages**, choose the `main` branch, and set the source to the root directory.
3. After Pages finishes deploying, your site will be available at
   `https://alieneverything.github.io/ksa95/`, serving `index.html` at the root and linking to the additional lab pages.

## Accessibility
- Animations respect `prefers-reduced-motion`: each lab starts paused when motion is reduced.
- Canvas visuals include ARIA labels describing their content.
- Keyboard shortcuts and button focus states allow navigation without a mouse.
