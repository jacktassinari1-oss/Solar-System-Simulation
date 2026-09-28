# Solar-System-Simulation

# 3D Solar System N-Body Simulation

An interactive 3D orbital mechanics simulation of the Solar System built in Python using **VPython**. The project accurately calculates gravitational interactions between celestial bodies while offering smooth UI controls and camera tracking.

## Features
- **N-Body Physics:** Simulates gravitational forces between all celestial bodies ($F = G \frac{m_1 m_2}{r^2}$).
- **Velocity Verlet Integration:** High-precision numerical integration for stable, accurate orbital motion.
- **Interactive Camera Tracking:** Focus the camera on any planet using either the dropdown menu or by directly clicking on 3D objects in the scene.
- **Visual Enhancements:** Includes dynamic lighting, orbital trail paths, Saturn's rings, custom textures, and a generated background starfield.
- **Barycenter Momentum Correction:** Automatically balances system momentum at initialization to prevent scene drift.

## Requirements
- Python 3.x
- `vpython`

Install dependencies via pip:
```bash
pip install vpython
