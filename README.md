# NanoTraffic
NanoTraffic is an edge-optimized computer vision system built to detect and categorize traffic violations. This project serves as a hands-on journey into deep learning, focusing on real-time detection of motorcycles and bicycles in prohibited zones.
🎯 Project Scope
The goal of this project is to distinguish between standard vehicle presence and specific traffic infractions (e.g., driving on pedestrian paths or stopping past the line) using the state-of-the-art YOLO26n architecture.
🧠 Model & Dataset
Architecture: YOLO26n (Nano) — Chosen for its 43% faster CPU inference and NMS-free design.
Dataset: Hosted on Roboflow Universe, featuring 9 distinct classes:
Standard: Motorcycles, Bicycles.
Violations: Pedestrian road incursions, crosswalk violations, and stop-line infractions.
Environment: Trained using Google Colab with T4 GPU acceleration.
🛠 Features
Behavioral Detection: Identifies not just the object, but the context of its location (e.g., "Motorcycle - Jaywalk").
Real-Time Ready: Optimized for high FPS on CPU/Edge hardware.
Precise Tracking: Designed to follow vehicle movement across frames.
