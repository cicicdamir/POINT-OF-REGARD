# 👁️ POINT-OF-REGARD (POR)

A hardware-agnostic, real-time eye-tracking engine built with Vanilla JavaScript and MediaPipe. 

## 🔬 System Overview
The engine calculates the **Point of Regard** by mapping 3D iris displacement vectors against a calibrated 2D screen plane.

### Key Engineering Components:
- **Vector Math:** Implementation of ray-ray intersection algorithms to find the focus point in 3D space.
- **Dynamic Calibration:** A 5-point calibration system that utilizes **Linear Interpolation (LERP)** to map raw physiological data to pixel coordinates.
- **Temporal Smoothing:** Alpha-beta filter implementation to reduce saccadic jitter in gaze tracking.

## 🚀 Live Engineering Demo
[cicicdamir.github.io/POINT-OF-REGARD/](https://cicicdamir.github.io/POINT-OF-REGARD/)
*(Requires Camera Access)*

## 🛠 Tech Stack
- **Vision:** MediaPipe Face Mesh
- **Logic:** Vanilla JavaScript (ES6+)
- **Render:** HTML5 Canvas API
