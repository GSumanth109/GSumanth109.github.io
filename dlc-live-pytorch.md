layout: page title: DLC-Live-PyTorch (Real-Time Pose Estimation) permalink: https://www.google.com/search?q=/dlc-live-pytorch/

Real-Time, Low-Latency Pose Estimation (DLC-Live-PyTorch)

Problem Statement & Motivation

The widely used markerless pose estimation tool, DeepLabCut (DLC), typically operates at only $\approx$15 FPS in its TensorFlow deployment due to computational intensity. This is insufficient for capturing high-speed biological or robotic motion, restricting its utility for real-time applications and closed-loop control systems.

Technical Approach & Innovation

This project delivers a custom PyTorch-based DLC inference pipeline optimized for minimal latency and maximum throughput, achieving performance 4$\times$ faster than the baseline.

Low-Latency Inference: Achieved a sustained \textbf{16ms latency} by enforcing a \textbf{batch size of 1} and leveraging \textbf{FP16 precision} on NVIDIA CUDA architecture.

High-Throughput Stability: Developed a custom Hotswap Memory Manager that actively monitors RAM usage and automatically clears redundant objects/swaps model weights. This ensured system stability and sustained performance at high frame rates, overcoming a major challenge in continuous real-time execution.

Performance Metric: Sustained \textbf{60 FPS} at 640x480 resolution (ResNet-50 backbone).

System Integration

The system was architected using multi-process threads to isolate CPU-bound tasks (e.g., frame acquisition, visualization) from the dedicated GPU inference process, preventing bottlenecks and maximizing GPU utilization.

Links

GitHub Repository (DLC-Live-Pytorch)
