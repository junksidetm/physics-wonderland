# Version History & Project Evolution - Physics Wonderland 3D

## Repository & Project Overview
- **Project:** Physics Wonderland 3D
- **Description:** Interactive 3D physical laws simulation laboratory for students with procedural Three.js cartoon characters, real-time formula calculation HUD, and responsive cross-platform support.
- **Repository Lineage:** Forked from `saltymother/physics-wonderland` to `junksidetm/physics-wonderland`.
- **Live GitHub Pages URL:** `https://junksidetm.github.io/physics-wonderland/`

## Libraries & Tools
- **Three.js:** r128 (WebGL 3D Rendering Engine)
- **OrbitControls:** Three.js r128 companion (Touch & Pointer Orbital Controls)
- **Web Audio API:** Zero-dependency synthetic procedural sound engine
- **GitHub Actions:** GitHub Pages deployment workflow (`.github/workflows/deploy.yml`)

---

## Evolution Log

### [2026-10-04 00:58] Mobile Responsive Transformation & GitHub Pages Live Deployment
- **Status:** Complete (100%)
- **Author:** Antigravity Agent
- **Description:** 
  1. Enabled GitHub Pages on `junksidetm/physics-wonderland` via GitHub API with `build_type=workflow`.
  2. Fixed desktop-only fixed CSS coordinate layout collisions causing all UI elements to overlap and scatter when loaded on mobile browsers.
  3. Transformed the desktop-left floating control panel into an interactive, thumb-friendly Mobile Bottom Sheet Drawer with drag-handle, close button, and glass backdrop.
  4. Implemented a Floating Action Button (`#mobile-controls-fab`) so mobile users can easily access and dismiss controls without blocking the 3D physics scene.
  5. Converted the wide navigation bar into a responsive segmented tab bar displaying concise labels (`Gravity`, `Bernoulli`, `Torricelli`) on mobile.
  6. Added a collapsible Live Math Formula HUD with chevron toggle, minimizing screen footprint on portrait displays.
  7. Added portrait mode aspect-ratio scaling in Three.js camera controller to prevent wide physics apparatuses (e.g. Venturi tube, Torricelli water jet, Keplerian orbits) from getting horizontally cropped on mobile screens.
  8. Hardened fallback orbit controls with native touch gestures (single-finger orbital drag and two-finger pinch-to-zoom).
  9. Added touch/pointer event isolation on all overlay UI cards to prevent camera movement when manipulating sliders.
  10. Added speech bubble auto-dismiss timer on mobile and dismiss button (`✕`).
- **Files Modified:**
  - `index.html` (Responsive meta tags, bottom sheet drawer handles, mobile toggle buttons, formula HUD collapse structure)
  - `style.css` (Mobile media queries, bottom sheet animations, FAB, segmented tabs, touch target sizes)
  - `app.js` (Panel drawer state management, responsive camera distance scaling, touch fallback controls, audio unlocking)
  - `cartoon_renderer.js` (Mobile speech bubble auto-dismiss and reset logic)
  - `Version.md` (Created project evolution tracking)

### [2026-10-04 01:01] Documentation & README Overhaul with Live Pages Verification
- **Status:** Complete (100%)
- **Author:** Antigravity Agent
- **Description:** 
  1. Updated `README.md` with official live deployment badges, GitHub Pages URL, mobile bottom sheet drawer architecture, and touch navigation documentation.
  2. Documented multi-touch gesture controls (single-finger orbit, two-finger pinch-zoom) and portrait camera auto-scaling.
  3. Verified live GitHub Pages HTTP response at `https://junksidetm.github.io/physics-wonderland/`.
  4. Updated parent workspace lineage registry in `GEMINI.md`.
- **Files Modified:**
  - `README.md` (Overhauled documentation, live badges, cross-platform usage)
  - `Version.md` (Appended real-time changelog entry)
