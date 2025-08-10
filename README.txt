# 3D Web Application — Three.js Classic Viewer

This project is a fully client-side 3D web viewer built for the 3D Web Applications module.  
It demonstrates model loading, lighting presets, camera control, material editing, animation playback, and a responsive Bootstrap-based interface.

---

## 📸 Overview

The application allows users to:
- View and interact with 3D models directly in the browser
- Switch between local and remote models
- Edit material properties in real time
- Toggle lighting setups
- Play, pause, and stop animations
- Switch camera positions and reset views
- Enable wireframe view for geometry inspection

---

## 🚀 Features

- Model Selector — choose from multiple 3D models (local-first, with remote fallback for Damaged Helmet).
- Lighting Presets — Studio, Outdoor, Dramatic.
- Orbit Controls — pan, zoom, and rotate camera.
- Material Editing — change color, roughness, and metalness of selected meshes.
- Animation Support — select and control animation clips from loaded models.
- Wireframe Mode — toggle for model geometry inspection.
- Responsive UI — Bootstrap layout with a sidebar for controls and a full-width viewer.
- About Page — describes the application, features, and accessibility considerations.

---

## 📂 Project Structure

public/
│
├── index.html # Main 3D viewer
├── about.html # About page
├── models/ # Local 3D models
│ ├── DamagedHelmet/
│ ├── CesiumMan/
│ ├── WaterBottle/
│ └── Duck/
└── images/ # Any images (e.g., UI screenshots)



---

## 🛠️ Technologies Used

- Three.js (classic build v0.124.0)
  - `OrbitControls` for navigation
  - `GLTFLoader` for model loading
  - `AnimationMixer` for animation playback
- Bootstrap 5 — responsive layout and styling
- JavaScript (ES5/ES6 mix) — DOM events, interaction handling
- WebGL — rendering 3D graphics in the browser

---

## 📥 Installation & Usage

1. Clone or download this repository.
2. Place it in a folder of your choice.
3. Ensure you have Visual Studio Code (or another code editor) installed.
4. Install the Live Server extension in VS Code.
5. Open the project folder in VS Code.
6. Right-click `public/index.html` → Open with Live Server.
7. The app will open in your default browser.

---

## 📦 Models & Assets

- Damaged Helmet — from [Three.js Examples](https://threejs.org/examples/#webgl_loader_gltf).
- CesiumMan, WaterBottle, Duck — sourced from public 3D sample models (GLB format).
