# 3D Product Manual Project

A multi-product interactive 3D product manual built for GitHub Pages.

## What changed in this version

This is no longer a single-camera demo. The site is structured as an **Industrial Product Lab** with a deliberately different visual identity from the previous glass/cyan interfaces.

### Product library

1. Canon EOS RP camera
2. iPhone device
3. MacBook laptop
4. Ferrari F40
5. Automotive engine
6. Medical stethoscope
7. Adaptive power wheelchair
8. Smartphone Li-ion Battery — official Sketchfab viewer
9. Laptop Battery Pack — Graphitage, CC Attribution via Sketchfab

## Interaction

- Real Three.js GLB loading
- Orbit, zoom and rotate
- Product switching
- Product-specific component maps
- Raycast selection on the actual 3D model
- Distinct camera focus per component
- Nearest-mesh highlight per selected component
- Component hotspots attached to the corresponding mesh
- Animated exploded / assembled view using the real meshes
- Auto rotate
- English / Persian UI
- RTL Persian layout
- Mobile product and information drawers
- Searchable component list
- Actual loading progress and model-source fallback where available

## Interaction update

- Mesh-aware component focus and highlighting
- Animated real-mesh exploded / assembled transitions
- Polygonal industrial controls across product cards, tool buttons, component buttons and header controls
- Realistic multi-part V8 engine asset with Draco decoding

## Visual direction

The current UI intentionally avoids the repeated dark blue glassmorphism language used in earlier projects. It uses an **industrial editorial / product-design-lab** direction:

- warm paper background
- charcoal 3D stage
- safety-orange accent
- acid-lime status accent
- technical grid
- hard borders
- numbered product catalog
- editorial typography

## 3D asset sources

The project loads web-ready GLB assets from traceable public sources.

- **Canon EOS RP** — fahadratul / SceneView, CC BY 4.0
- **Camera fallback** — Khronos glTF Sample Assets
- **iPhone device + MacBook** — HyperFrames repository device assets
- **Smartphone fallback** — ToonStudio original smartphone, CC0 1.0
- **Ferrari F40** — Black Snow / SceneView, CC BY 4.0
- **Car fallback** — Khronos ToyCar, CC BY 4.0
- **V8 Engine** — “Animated Engine V8” by meeww, CC BY 4.0; vendored by johnnyhuy/vibes via Objaverse
- **Medical stethoscope** — ToonStudio original asset, CC0 1.0
- **Adaptive power wheelchair** — ToonStudio original asset, CC0 1.0

External model assets remain subject to their respective source licenses and attribution requirements.

## Deployment

GitHub Pages deploys automatically from `main` through:

`.github/workflows/pages.yml`

Live site:

https://saaeiddev.github.io/3D-Product-Manual-Project/

## Tech

- HTML
- CSS
- JavaScript
- Three.js
- GLTFLoader
- OrbitControls
- CSS2DRenderer
- GitHub Pages

## Repository

https://github.com/saaeiddev/3D-Product-Manual-Project
