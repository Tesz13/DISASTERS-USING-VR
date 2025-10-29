# 🧰 Houdini Setup Guide for Beginners

Welcome to **Houdini**, the procedural powerhouse behind simulations, effects, and 3D environments.  
This guide walks you through **installing**, **licensing**, and **using** Houdini from scratch — perfect if you’re returning after a break or starting fresh.

---

## 🧩 1. What is Houdini?

Houdini (by **SideFX**) is a 3D software for:
- Visual Effects (VFX)
- Simulations (smoke, fire, water, destruction)
- Procedural Modeling
- Rendering and Animation
- Game / VR Environments

It’s built on a **node-based** system — every operation (noise, extrude, simulate, render) is a *node* you can connect and modify.

---

## ⚙️ 2. Download & Install Houdini

### 🎯 Version
Use **Houdini 20.0** (latest stable) or **19.5** if your hardware is older.  
Beginners and students should use the **Apprentice (Free)** version.

**Download Link:**  
👉 [https://www.sidefx.com/download/](https://www.sidefx.com/download/)

### ✅ Installation Options
When the installer opens:
- **Houdini FX** → ✔️ (main program)
- **License Server** → ✔️ (required)
- **Python 3 Build** → ✔️ (recommended)
- **Houdini Indie/Apprentice License** → select if prompted

After installation, launch Houdini once to ensure it runs.

---

## 🔐 3. License Activation

1. Open **Houdini License Administrator (hkey)**.  
2. Click **File → Install Licenses**.  
3. Select **Non-Commercial (Apprentice)**.  
4. Log in using your **SideFX account** (create one if needed).  
5. You’ll see:
Houdini FX 20.0 Non-Commercial
Render (Mantra) Non-Commercial
✅ You now have a free license for personal/non-commercial use.

---

## 📂 4. Folder Structure & Project Setup

Houdini likes structured projects. Set yours up like this:

```text
📁 MyHoudiniProject
│
├── hip/              # Your .hip or .hipnc files
├── assets/           # Textures, models, simulations
├── renders/          # Rendered images or videos
└── geo/              # Cached geometry (.bgeo)
