# Inclined Plane Physics Simulator

A web-based simulation of a block on an inclined plane, developed as a first-year mechanics project.

## Overview

This project demonstrates static and kinetic friction on an inclined surface. Users can adjust:
- Plank angle (degrees)
- Block mass (kg)
- Coefficient of static friction (preset materials or custom values)

The simulation determines whether the block will slide based on the critical angle condition:
tan(theta) > mu_s

When sliding occurs, acceleration is calculated using:
a = g * (sin(theta) - mu_k * cos(theta))

where:
- g = 9.8 m/s^2
- mu_k = 0.85 * mu_s (kinetic friction coefficient)

## How to Run

Open `index.html` in any standard web browser. No server or dependencies required.
