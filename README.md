# Magnetic Force VR

An interactive VR simulation of the Lorentz force on charged particles for introductory electromagnetism, built with Three.js and WebXR for Meta Quest.

Designed and developed by Anthony Danese, high school physics teacher.

## What it does

Students fire charged particles into a configurable magnetic field and observe the resulting trajectories in real time. The simulation demonstrates how field direction, field strength, and particle speed and mass affect the radius and direction of circular motion. A density-scaled arrow grid visualizes the magnetic field throughout the scene.

## Features

- Gun-style particle launcher held by the right controller
- Density-scaled arrow grid showing the magnetic field in 3D space
- Joystick control of field strength and particle speed
- Field direction adjustable in real time
- Particle trails showing full trajectory arc
- Multiple charge signs (positive / negative)

## Controls

| Action | Control |
|---|---|
| Fire particle | Trigger (right controller) |
| Increase field strength | Thumbstick up |
| Decrease field strength | Thumbstick down |
| Increase particle speed | Thumbstick right |
| Decrease particle speed | Thumbstick left |
| Toggle charge sign | A button (right controller) | |

## How to use

1. Open your Meta Quest browser and navigate to the live sim
2. Tap **Enter VR**
3. Use the trigger to fire particles into the field
4. Adjust field strength and particle speed with the thumbstick
5. Observe how trajectory radius changes with each parameter

**Live sim:** https://phys-viz.github.io/MagneticForceVR/

## Pedagogical context

This simulation is designed to give students a concrete visual sense of how the Lorentz force produces circular motion and how the radius of curvature depends on speed and field strength — before or alongside quantitative problems involving r = mv/qB. It is part of a suite of VR simulations for introductory electromagnetism.

## Tech stack

- **Three.js** r128
- WebXR API
- Vanilla JavaScript — no build tools, no frameworks
- Hosted on GitHub Pages

## License

© 2026 Anthony Danese. Licensed under **CC BY-NC-SA 4.0**.  
Free for educational use. Commercial use requires explicit written permission.
