---
layout: page
title: Core Technical Case Studies
permalink: /projects/
---

# 🚀 Research & Applied Systems Portfolio

This portfolio showcases projects focused on three core areas relevant to Sony R&D: **Real-Time System Optimization**, **3D/4D Perception & Generation**, and **Full-Stack Hardware Integration**.

---

## 🔬 Ongoing Research: 3D/4D Generation

### Semantic Segmentation in Gaussian Splatting

A novel approach integrating **semantic knowledge** directly into **3D representation (GS) parameters** for creating editable digital twins.
* **Focus:** Enhancing 3D models with semantic context for scene manipulation.
* **Technologies:** **PyTorch**, **Gaussian Splatting**, 3D/4D Perception.

---

## ⚡ Real-Time & Low Latency Systems

### [DLC-Live-Pytorch: Real-Time Pose Estimation](/dlc-live-pytorch/)

Developed an optimized pipeline for high-throughput, markerless pose estimation.
* **🎯 Core Metric:** Achieved **60 FPS** at **16ms latency** (4x faster than state-of-the-art baselines).
* **🛠️ Technical Highlight:** Implemented a custom **Hotswap Memory Manager** for closed-loop stability in production.
* **[Read the Full Case Study →](/dlc-live-pytorch/)**

---

## 🤖 Robotics & Hardware Integration

### [3D mapping using Kinect V1 with ROS2 humble](/kinect-slam/)

Successfully integrated a legacy RGB-D sensor into a modern robotics operating system for SLAM applications.
* **🎯 Core Metric:** Enabled stable **RGB-D streaming and SLAM** functionalities.
* **🛠️ Technical Highlight:** Solved complex driver incompatibility and performed custom hardware modification for sensor longevity.
* **[Read the Full Case Study →](/kinect-slam/)**

### [Monocular Depth Estimation using Depth Anything V2](/monocular-3d/)

Created a highly accurate, real-time depth estimation system using a single camera input.
* **🎯 Core Metric:** Achieved **30 FPS** at 1080p with stable absolute metric distance readings.
* **🛠️ Technical Highlight:** Developed a custom **non-linear calibration algorithm** to mitigate ambient lighting effects on depth accuracy.
* **[Read the Full Case Study →](/monocular-3d/)**

---

## 💡 Embedded & Multi-Modal Systems

### [Blackbox-for-LMV: Automotive Blackbox System](/blackbox-lmv/)

Designed a reliable, multi-modal embedded system for synchronous vehicle data logging.
* **🎯 Core Metric:** Synchronous logging of telemetry and computer vision data (drowsiness detection).
* **🛠️ Technical Highlight:** Designed a custom **Python/UART logging stack** using a Raspberry Pi Pico for low-power operation.
* **[Read the Full Case Study →](/blackbox-lmv/)**

***

