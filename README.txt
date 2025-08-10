# 3D Web Application — Three.js Classic Viewer

# Overview

The application allows users to:
- View and interact with 3D models directly in the browser
- Switch between local and remote models
- Edit material properties in real time
- Toggle lighting setups
- Play, pause, and stop animations
- Switch camera positions and reset views
- Enable wireframe view for geometry inspection
- Change between 2 background environments
- Take a screenshot



# Features

- Model Selector — choose from multiple 3D models (local-first, with remote fallback for Damaged Helmet).
- Lighting Presets — Studio, Outdoor, Dramatic.
- Orbit Controls — pan, zoom, and rotate camera.
- Material Editing — change color, roughness, and metalness of selected meshes.
- Animation Support — select and control animation clips from loaded models.
- Wireframe Mode — toggle for model geometry inspection.
- Responsive UI — Bootstrap layout with a sidebar for controls and a full-width viewer.
- About Page — describes the application, features, and accessibility considerations.



# Project Structure

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





# Technologies Used

- Three.js (classic build v0.124.0)
  - `OrbitControls` for navigation
  - `GLTFLoader` for model loading
  - `AnimationMixer` for animation playback
- Bootstrap 5 — responsive layout and styling
- JavaScript (ES5/ES6 mix) — DOM events, interaction handling
- WebGL — rendering 3D graphics in the browser



# Installation & Usage

1. Clone or download this repository.
2. Place it in a folder of your choice.
3. Ensure you have Visual Studio Code (or another code editor) installed.
4. Install the Live Server extension in VS Code.
5. Open the project folder in VS Code.
6. Right-click `public/index.html` → Open with Live Server.
7. The app will open in your default browser.



# Models & Assets

- Damaged Helmet — from (https://github.com/KhronosGroup/glTF-Sample-Models/tree/main/2.0/DamagedHelmet/glTF).
- CesiumMan - from (https://github.com/KhronosGroup/glTF-Sample-Models/tree/main/2.0/CesiumMan/glTF-Binary)
- WaterBottle - from (https://github.com/KhronosGroup/glTF-Sample-Models/tree/main/2.0/WaterBottle/glTF-Binary)
- Duck — from (https://github.com/KhronosGroup/glTF-Sample-Models/tree/main/2.0/Duck/glTF-Binary)
