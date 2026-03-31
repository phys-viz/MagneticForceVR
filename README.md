# Magnetic Force VR

An interactive VR simulation of the Lorentz force on charged particles for introductory electromagnetism, built with Three.js and WebXR for Meta Quest.

Designed and developed by Anthony Danese, high school physics teacher.

## What It Does

Students fire charged particles into a configurable magnetic field and observe the resulting trajectories in real time. The simulation demonstrates how field direction, field strength, particle speed, and particle mass affect the radius and direction of circular motion. A density-scaled arrow grid visualizes the magnetic field throughout the scene.

## Features

- Gun-style particle launcher held by the right controller
- Density-scaled arrow grid showing the magnetic field in 3D space
- Live control of field strength, launch speed, charge sign, and mass
- Field direction adjustable in real time
- Particle trails showing full trajectory arcs
- Snap guidance for launching parallel or perpendicular to the field
- Desktop preview mode with keyboard controls and orbit camera

## Controls

| Action | Control |
|---|---|
| Fire particle | Trigger on right controller |
| Increase field strength | Thumbstick up |
| Decrease field strength | Thumbstick down |
| Increase particle speed | Thumbstick right |
| Decrease particle speed | Thumbstick left |
| Toggle charge sign | A button on right controller |
| Rotate field axis | B button on right controller |
| Cycle mass | Thumbstick click |
| Show or hide help | Grip button |

## How To Use

1. Open your Meta Quest browser and navigate to the live sim.
2. Select `Enter VR`.
3. Fire particles into the magnetic field.
4. Adjust field strength, speed, charge, and mass to compare the resulting paths.
5. Try launching particles parallel and perpendicular to the field to compare the force.

Live sim: https://phys-viz.github.io/MagneticForceVR/

## Pedagogical Context

This simulation is designed to give students a concrete visual sense of how the Lorentz force produces circular motion and how the radius of curvature depends on speed and field strength before or alongside quantitative problems involving `r = mv / qB`. It is part of a broader suite of VR simulations for introductory electromagnetism.

## Tech Stack

- Three.js r128
- WebXR API
- Vanilla JavaScript with no build tools or frameworks
- Hosted on GitHub Pages

## License

Copyright 2026 Anthony Danese. Licensed under CC BY-NC-SA 4.0.

Free for educational use. Commercial use requires explicit written permission.
