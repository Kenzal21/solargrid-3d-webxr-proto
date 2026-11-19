# 🌱 SolarGrid 3D

A browser-based 3D microgrid builder powered by **Three.js** and **WebGL**. Plan, budget, and construct renewable energy infrastructure to power a sustainable community.

👉 **[Play the Live Demo](https://YOUR-USERNAME.github.io/solargrid-3d/)** *(Update with your GitHub Pages link)*

---

## 🎯 Project Overview
**SolarGrid 3D** explores clean energy planning through interactive 3D spatial design. Built with WebGL—the core graphics technology behind WebXR and browser-based VR—this prototype demonstrates 3D object placement, raycasting, and real-time animation in a lightweight, zero-dependency web app.

## ⚡ Gameplay & Rules
Your goal is to generate **100 MW** of clean energy on a 5×5 land grid without exceeding your **$500** starting budget.

| Structure | Cost | Power Output | Best For |
| :--- | :---: | :---: | :--- |
| **☀️ Solar Panel** | $50 | +10 MW | Low-cost, steady grid expansion |
| **🌀 Wind Turbine** | $100 | +25 MW | High-efficiency power generation |

### Controls
* **Select Structure:** Click the **Solar** or **Turbine** button in the top-left HUD.
* **Build:** Click any open green tile on the 3D grid to place your selected structure.
* **Restart:** Refresh the browser page to reset your budget and grid.

## 🛠️ Built With
* **HTML5 & CSS3** — Minimalist HUD overlay and responsive viewport layout.
* **JavaScript (ES6)** — Game state management, budget validation, and animation loop.
* **Three.js (r128)** — 3D scene rendering, lighting, procedural meshes, and mouse-to-world raycasting.

## 💻 Run Locally
1. Download or clone this repository:
   ```bash
   git clone [https://github.com/YOUR-USERNAME/solargrid-3d.git](https://github.com/YOUR-USERNAME/solargrid-3d.git)
