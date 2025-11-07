---
layout: default
title: Monocular Depth Estimation (3D Spatial Localization)
permalink: /monocular-3d/
---

# 👁️ Real-Time Monocular 3D Spatial Reasoning

## Problem Statement & Motivation

Standard 2D object detection is inadequate for robotics and autonomous systems that require metric spatial data (absolute distance and angle). The challenge in monocular depth systems is converting the model's relative depth output into stable **absolute distance** that is robust to ambient lighting fluctuations.

## Technical Approach & Innovation

This project established a real-time pipeline using state-of-the-art models and a custom calibration loop.

* **Depth Backbone:** Utilized **Depth Anything V2** to generate high-fidelity relative depth maps from the monocular camera stream.
* **3D Output:** System simultaneously extracts object position, horizontal angle, and **metric distance** relative to the camera center.
* **Calibration Algorithm:** Integrated a custom **non-linear calibration algorithm** to mitigate ambient lighting effects and stabilize metric output.

## Performance Metrics
* **Throughput:** Sustained **30 FPS** at 1920x1080 resolution.
* **Efficiency:** Achieved high frame rates demonstrating suitability for robotics and autonomous systems running on the edge.

---

## Links
* [GitHub Repository (Object Tracking)](https://github.com/GSumanth109/Monocular-3D-System)
