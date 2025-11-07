layout: page title: Blackbox-for-LMV (Automotive Event Recorder) permalink: /https://www.google.com/search?q=blackbox-lmv/

Multi-Modal Vehicular Blackbox System

Problem Statement & Motivation

Accident analysis and emergency response require more than just video; they need fused, synchronous vehicle telemetry and driver state data. The project aimed to create a cost-effective Blackbox fusing this multi-modal data for robust accident reconstruction and safety flagging.

Technical Approach & Innovation

This was a successful proof-of-concept integrating embedded hardware with Computer Vision.

Multi-Modal Fusion: Designed a system to fuse simulated vehicle telemetry data (e.g., brake pressure, acceleration) from a Raspberry Pi Pico with Computer Vision-derived data (OpenCV-based drowsiness detection).

Custom Data Logger: Developed a custom Python script that handled serial port communication (UART), data parsing, temporal synchronization, and robust, timestamped CSV logging. This ensured data integrity necessary for forensic analysis.

Academic Achievement: Project received a top grade of \textbf{10/10} by the course evaluation panel.

Links

GitHub Repository (Blackbox-for-LMV)
