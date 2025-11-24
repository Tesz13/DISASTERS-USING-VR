
# Project Disasters — Virtual Reality using Houdini

> A fully procedural, VR-ready sandbox built in **Houdini** that simulates natural (and not-so-natural) chaos — terrains, oceans, floods, clouds, mountains, trees, buildings, asteroids, rain, and destruction FX — all in one dynamic environment.

---

## Overview

This project explores **environmental simulations** and **destruction FX** using **SideFX Houdini**.  
Every element — from island terrain to asteroid impacts — is procedurally generated for full control and creative flexibility.  
Designed with **Virtual Reality (VR)** in mind, it demonstrates how procedural workflows can efficiently create large-scale, realistic worlds.

**Presented by:** *Thanvi Sirla*  
**Date:** December 2023  
---

## Features

| Category | Description |
|-----------|-------------|
|  **Terrain System** | Procedural island created with heightfields (remap, noise, erosion, water level) |
|  **Water Simulation** | Still ocean, ocean waves, and flood passes driven by *Ocean Spectrum/Evaluate* |
|  **Atmospherics** | Volumetric cloud setup using *Cloud* & *CloudNoise* nodes |
|  **Environment** | Mountains with *UVQuickShade* textures, procedural tree placement |
|  **Built Assets** | Buildings, helipad, and a dynamic name/title card |
|  **FX & Destruction** | RBD Fracture + Bullet Solver, POP simulations for fire, asteroids, and rain |

---

## Technologies Used

-  **SideFX Houdini**
-  **Procedural Nodes** (HeightField, Ocean, POP, RBD, Cloud, etc.)
-  **Bullet Physics Engine**
-  **VDB Volumes** for cloud systems
-  **UVQuickShade** for texturing
-  **VR-ready Camera Setup**

---


<details>
  <summary>🗂️ View Repository Structure</summary>
```markdown
```text
## 🗂️ Repository Structure

```text
📁 Project-Disasters
│
├── docs/                      # Documentation, reports, presentations, etc.
│   ├── VR-project.pdf
│   ├── VR-Project-Presentation.pptx
│   └── Project-Disasters.zip
│
├── finals/                    # Rendered outputs and final media files
│   └── preview.png
│
├── hip.zip                    # Compressed Houdini project file (HIPNC + assets)
│
├── README.md                  # Main project overview and documentation
│
└── setup.md                   # Houdini setup and beginner installation guide



