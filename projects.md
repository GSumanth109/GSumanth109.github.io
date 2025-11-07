---
layout: page
title: Core Technical Case Studies
permalink: /projects/
---

# 🚀 Research & Applied Systems Portfolio

This portfolio showcases projects focused on three core areas relevant to Sony R&D: **Real-Time System Optimization**, **3D/4D Perception & Generation**, and **Full-Stack Hardware Integration**.

---

## 🔬 Ongoing Research (3D/4D Generation)

### Semantic Segmentation in Gaussian Splatting

Focus: Integrating semantic knowledge into 3D representation (GS) parameters for editable digital twins.
Technologies: PyTorch, Gaussian Splatting, 3D/4D Perception.

---

## ⚡ Real-Time & Low Latency Systems

### [DLC-Live-Pytorch (Real-Time Pose Estimation)](/dlc-live-pytorch/)

Core Metric: Achieved **60 FPS** at **16ms latency** (4x faster than baselines).
Technical Highlight: Custom **Hotswap Memory Manager** for closed-loop stability.
* **[Read the Full Case Study](/dlc-live-pytorch/)**

---

## 🤖 Robotics & Hardware Integration

### [3D mapping using Kinect V1 with ROS2 humble](/kinect-slam/)

Core Metric: Enabled stable **RGB-D streaming and SLAM** for a legacy sensor on a modern robotics OS.
Technical Highlight: Solved complex driver incompatibility and performed custom hardware modification.
* **[Read the Full Case Study](/kinect-slam/)**

### [Monocular Depth Estimation using Depth Anything V2](/monocular-3d/)

Core Metric: Achieved **30 FPS** at 1080p with stable absolute metric distance.
Technical Highlight: Custom **non-linear calibration algorithm** to mitigate ambient lighting effects.
* **[Read the Full Case Study](/monocular-3d/)**

---

## 💡 Embedded & Multi-Modal Systems

### [Blackbox-for-LMV (Automotive Blackbox System)](/blackbox-lmv/)

Core Metric: Synchronous logging of telemetry and computer vision (drowsiness detection).
Technical Highlight: Designed a custom **Python/UART logging stack** using Raspberry Pi Pico.
* **[Read the Full Case Study](/blackbox-lmv/)**
