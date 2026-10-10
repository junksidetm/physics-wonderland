<div align="center">

<img src="assests\atom-symbol-svgrepo-com.svg" height="120">

# Physics Wonderland 3D
[![GitHub Main](https://img.shields.io/badge/GitHub-Main-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/junksidetm/physics-wonderland)
[![Codeberg Mirror](https://img.shields.io/badge/Codeberg-Mirror-2185d0?style=flat-square&logo=codeberg&logoColor=white)](https://codeberg.org/mrdarksidetm/physics-wonderland)
[![GitLab Mirror](https://img.shields.io/badge/GitLab-Mirror-fc6d26?style=flat-square&logo=gitlab&logoColor=white)](https://gitlab.com/mrdarksidetm/physics-wonderland)
[![Deploy to GitHub Pages](https://github.com/junksidetm/physics-wonderland/actions/workflows/deploy.yml/badge.svg)](https://github.com/junksidetm/physics-wonderland/actions/workflows/deploy.yml)
[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-success?style=flat&logo=github)](https://junksidetm.github.io/physics-wonderland/)
[![Platforms](https://img.shields.io/badge/Platform-Desktop%20%7C%20Mobile%20%7C%20Tablet-blue)](#-responsive-mobile--desktop-experience)



An interactive, animated 3D physics laboratory application built for modern browsers (desktop, mobile, and tablets) to teach students fundamental physical laws using vibrant motion, procedural 3D cartoon characters, and live mathematical calculations.

  <a href="https://junksidetm.github.io/physics-wonderland/" target="_blank" rel="noopener noreferrer">
    <img src="https://raw.githubusercontent.com/junksidetm/assests/2059cd31ecfc7cd57fab1d30a4baa11810783b48/Images/badges/SVG%20-%20Version/Website%20Badge.svg" alt="Visit the Physics Wonderland website" width="190">
  </a><br>
<sub><i>Click on the button above to learn Physics visually</i></sub>
</div>

---
<div align="center"><sub>XXX</sub></div>

---

## 🌟 Interactive Physics Modules

### 🪐 1. Universal Gravitation & Orbital Mechanics
* **Key Concept**: Newton's Law of Universal Gravitation and Newton's Cannonball thought experiment.
* **Master Formula**:
  $$F_g = G \frac{M \cdot m}{r^2}$$
* **Orbital & Escape Velocity**:
  $$v_{circ} = \sqrt{\frac{G \cdot M}{r}}, \quad v_{esc} = \sqrt{\frac{2 \cdot G \cdot M}{r}}$$
* **Features & Cartoons**:
  - **Sir Isaac Newton 3D Character**: Animated 17th-century scholar with powdered wig, gold-buttoned jacket, and cartoon blinking eyes that track projectile flight.
  - **Spacetime Curvature Grid**: Dynamic 3D rubber-sheet spacetime well warping under the planet's mass in real time.
  - **Newton's Cannon**: Fire cannonballs at varying speeds. Watch them fall to Earth, enter stable elliptical/circular orbit, or escape to deep space!
  - **Apple Drop Experiment**: Drop apples to observe constant gravitational acceleration ($g$) with optional air drag.
  - **Celestial Bodies**: Switch between Earth ($1.0 M_\oplus$), Moon ($0.2 M_\oplus$), and Jupiter ($2.5 M_\oplus$).

---

### 💨 2. Bernoulli's Theorem & Fluid Mechanics
* **Key Concept**: Conservation of energy in flowing fluids and the relationship between velocity and static pressure.
* **Master Formula**:
  $$P_1 + \frac{1}{2}\rho v_1^2 + \rho g y_1 = P_2 + \frac{1}{2}\rho v_2^2 + \rho g y_2 = \text{constant}$$
* **Continuity Equation**:
  $$A_1 v_1 = A_2 v_2 \implies v_2 = v_1 \left(\frac{A_1}{A_2}\right)$$
* **Venturi Tube Simulation**:
  - Transparent glass constriction pipe with color-coded fluid particles:
    - **Deep Blue**: Slow velocity, high internal pressure.
    - **Amber / Red**: High velocity in the narrow constriction throat, low internal pressure!
  - Three vertical **Manometer tubes** where liquid column heights visually reflect the pressure drop ($\Delta P$).
* **Dynamic Airplane Wing Lift Demonstration**:
  - Airfoil section with smoke streamlines curving over the cambered top surface.
  - **Captain Bernoulli 3D Airplane**: Cartoon monoplane with spinning propeller and fluttering pilot scarf that generates upward lift ($L = \frac{1}{2} C_L \rho v^2 S$) and takes off into the sky!

---

### 💧 3. Torricelli's Law & Liquid Efflux
* **Key Concept**: The speed of efflux of liquid from an open container under gravity.
* **Master Formula**:
  $$v = \sqrt{2gh} \quad (\text{where } h = H - y)$$
* **Horizontal Jet Range & The Halfway Theorem**:
  $$R = 2\sqrt{y(H - y)}$$
  - **Maximum Range Theorem**: Farthest water jet distance occurs when the hole is drilled at exactly the halfway point:
    $$y = \frac{H}{2} \implies R_{max} = H$$
* **Features & Cartoons**:
  - **Graduated 3D Water Tank**: Real-time water surface rendering, movable orifice valve, and selectable fluids (Water, Honey, Mercury).
  - **Dynamic Parabolic Jet**: Real-time calculated 3D jet curve with splashing droplet particle emitter.
  - **Pippy the Penguin Mascot**: 3D cartoon penguin with an engineer hard hat and wooden bucket that waddles along the ground ruler to catch the water stream with celebration fanfare!

---

## 📱 Responsive Mobile & Desktop Experience

Physics Wonderland 3D is fully responsive across all screen sizes and orientations:

* **Mobile Bottom Sheet Drawer**: On mobile portrait screens, the simulation controls smoothly slide up from the bottom as an accessible bottom sheet drawer with a drag handle and glass backdrop, keeping the 3D physics scene fully visible.
* **Floating Controls FAB**: An intuitive floating action button (`🎛️ Controls`) lets mobile students open and close simulation sliders with one thumb.
* **Segmented Touch Navigation**: Header modules automatically collapse into a compact, thumb-friendly tab bar (`🪐 Gravity`, `💨 Bernoulli`, `💧 Torricelli`).
* **Collapsible Live Math HUD**: The real-time formula calculation card collapses into a compact floating pill on small screens, expandable on demand.
* **Touch-Optimized Orbit Controls**: Full multi-touch support for phones and tablets:
  - Single-finger drag: Orbit / rotate camera angle.
  - Two-finger pinch: Zoom in and out.
* **Portrait Aspect-Ratio Scaling**: Three.js cameras automatically scale distance on narrow vertical screens so wide physics apparatuses (e.g., Venturi pipes and projectile trajectories) are never clipped.
* **Touch Event Isolation**: Sliders and toggle buttons isolate touch events to prevent accidental camera rotation while fine-tuning experiment parameters.

---

## 🎓 Student Learning Features

* **Live Mathematical HUD**: Real-time arithmetic display showing variables plugged into formulas at 60 FPS.
* **Student Masterclass Modal**: Step-by-step cartoon lessons explaining the "Why?" behind each law.
* **Interactive Challenges**:
  1. *Achieve Stable Orbit*: Find the precise velocity to circle the globe without crashing.
  2. *Takeoff Lift*: Generate sufficient aerodynamic lift to achieve airborne flight.
  3. *Max Range Bullseye*: Position the orifice to maximize the horizontal trajectory and fill Pippy's bucket.
* **Procedural Sound Synthesizer**: Zero-dependency Web Audio API audio (cannon booms, water splashes, flight whooshes, and celebratory fanfares) with mobile audio unlocking.
* **Multi-Angle Camera Presets**:
  - 🎥 3D Cinematic Angle (Free Orbit / Pan / Zoom)
  - 📐 Front Profile / Cross-Section
  - 🛸 Top-Down View



## 🚀 Quick Launch & Local Development

Clone the repository and serve with any static web server:
```bash
git clone https://github.com/junksidetm/physics-wonderland.git
cd physics-wonderland

# Using Node.js npx
npx serve .

# Or using Python
python3 -m http.server 8080
```
Then navigate to `http://localhost:8080` in your web browser.


## 🛠️ Technology Stack
- **Rendering Engine:** [Three.js](https://threejs.org/) (r128 WebGL)
- **Camera Navigation:** Three.js OrbitControls with fallback multi-touch gesture engine
- **Audio:** Web Audio API (procedural synthesis, 0 audio assets required)
- **Styling:** Modern Glassmorphism CSS with Material & Apple SF Pro aesthetics
- **CI/CD Deployment:** GitHub Actions (`.github/workflows/deploy.yml`) to GitHub Pages


## 🌐 Source Mirrors

- **Main (GitHub)**: [github.com/junksidetm/physics-wonderland](https://github.com/junksidetm/physics-wonderland)
- **Mirror (Codeberg)**: [codeberg.org/mrdarksidetm/physics-wonderland](https://codeberg.org/mrdarksidetm/physics-wonderland)
- **Mirror (GitLab)**: [gitlab.com/mrdarksidetm/physics-wonderland](https://gitlab.com/mrdarksidetm/physics-wonderland)
- **Upstream Source**: [github.com/saltymother/physics-wonderland](https://github.com/saltymother/physics-wonderland)

---

<div align="center">
<a href="https://github.com/junksidetm/junksidetm.github.io">
  <img src="https://raw.githubusercontent.com/junksidetm/assests/981a029b9f59b8ed581bbee9be318c86da52dcca/Images/Codium/Codium%20Banner/SVG/Codium%20-%20Banner%20Black.svg" width="360"></a>
<br><br>
<sub>
<p>This repository is a part of `"Codeium"`. A part of Darkside Studio.
</p>
</sub>
<p><b><sub>© 2026 Abhijeet Yadav.  All rights reserved. All logos are Copyright Law </sub></b></p>
