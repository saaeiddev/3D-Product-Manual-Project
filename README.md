# 3D Product Manual Project

A premium bilingual (English / Persian) interactive 3D product manual built with Three.js and deployed on GitHub Pages.

## Live experience

The site is designed around a high-quality 3D mirrorless camera viewer with a futuristic glass interface. Users can rotate, zoom, pan, select parts, inspect hotspots, search components in English or Persian, switch RTL/LTR, use exploded view, read maintenance and troubleshooting information, and follow interactive guides.

## Core features

- Real interactive GLB/GLTF rendering with Three.js
- Canon EOS RP demo model with automatic fallback model
- 360° orbit, zoom, pan, smooth focus, reset and auto-rotate
- Interactive hotspots and component highlighting
- Exploded / assemble view
- Bilingual English + Persian interface
- Correct Persian RTL layout and language persistence
- Searchable component tree
- Technical specs, usage, warnings and maintenance details
- Troubleshooting workflows linked to 3D parts
- Step-by-step battery replacement guide
- Fullscreen and responsive mobile/tablet experience
- Premium cinematic glassmorphism UI
- GitHub Pages automatic deployment workflow

## 3D asset credits

- **Canon EOS RP Mirrorless Camera** — `fahadratul` — CC BY 4.0 — Sketchfab
- **Antique Camera fallback** — UX3D / Maximillan Kamps — CC0 1.0 — Khronos glTF Sample Assets
- **Three.js** — MIT License

Third-party 3D assets remain governed by their own licenses.

## Development

The production website is intentionally self-contained in `index.html` for reliable GitHub Pages deployment. Three.js is loaded as version-pinned browser ES modules from jsDelivr.

To test locally, serve the repository over HTTP instead of opening the file with `file://`:

```bash
python3 -m http.server 4173
```

Then open `http://localhost:4173`.

## Deployment

Every push to `main` triggers `.github/workflows/pages.yml`, which configures and deploys the repository to GitHub Pages.

---

Created as **3D Product Manual Project**.