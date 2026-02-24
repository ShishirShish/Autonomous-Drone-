🚁 Autonomous Drone for Power Grid Inspection, 3D Mapping & Indoor Safe Landing

This repository documents the design and implementation of an AI-enabled autonomous drone system developed for:

Damaged power grid line inspection
High-fidelity 3D mapping
Hotspot detection using thermal imaging
Indoor collision avoidance
Safe landing zone detection
Position estimation in GPS-denied environments
The system integrates multi-modal sensors (LiDAR, stereo vision, thermal imaging, optical flow) with edge AI processing on NVIDIA Jetson Orin Nano, enabling real-time perception, navigation, and decision-making.

📌 Project Objectives

Detect damaged or overheated power grid components
Generate accurate 3D maps of infrastructure and indoor environments
Perform collision-free navigation in cluttered spaces
Identify safe indoor landing spots
Maintain stable position estimation without GPS
Support autonomous and operator-assisted missions


🔍 Sensor Suite & Purpose

🟢 LiDAR Systems
4D L2 LiDAR
Long-range obstacle detection
Power line inspection
Structural awareness
3D Livox 360 LiDAR

Dense point-cloud generation
3D environment reconstruction
SLAM and mapping
Down-facing CS20 LiDAR
Path memory / retrace capability
Altitude stabilization
Indoor navigation assistance

📷 Vision Systems

Sony IMX Stereo Camera
Collision avoidance
Depth perception
Visual navigation
Intel RealSense Stereo Camera
Safe landing zone detection
Surface flatness analysis
Obstacle-free area identification
Thermal Camera
Hotspot detection
Overheated power lines & components
Fault localization

📡 Position & Motion Sensors

MTF01-P Optical Flow Sensor
Indoor position estimation
Velocity estimation
Drift reduction
IMU (Flight Controller)
Attitude estimation
Sensor fusion with optical flow
EKF-based drift minimization

🧠 Edge AI & Compute

NVIDIA Jetson Orin Nano
Real-time AI inference
Multi-sensor fusion
SLAM & mapping
Vision-based navigation
Remote access via RealVNC
Optimized for low latency edge processing

🧭 Navigation & Autonomy Features

Autonomous waypoint navigation
Real-time obstacle detection & avoidance

Indoor flight without GPS
Path memory and retracing
Safe landing zone detection
Manual override via GCS

🗺️ 3D Mapping & Perception

LiDAR-based 3D point cloud generation
Stereo vision depth fusion
Real-time SLAM
Indoor and outdoor mapping support
Infrastructure visualization for inspection analysis

🎯 Power Grid Inspection Capabilities

Thermal hotspot identification
Structural damage assessment
Line clearance verification
Close-range inspection without collision
Mapping of hard-to-reach infrastructure

🧪 Ground Control & Telemetry

Mission Planner / QGroundControl
Live telemetry monitoring
Sensor data visualization
Mission upload & monitoring
Manual and autonomous flight modes

🚀 Applications

Power grid inspection & maintenance
Disaster-damaged infrastructure assessment
Indoor industrial inspection
Search & reconnaissance
Autonomous navigation research
AI-enabled UAV systems

⚠️ Disclaimer

This project is experimental and research-oriented
Not certified for commercial or critical deployment
Field testing and safety validation are mandatory
Use in controlled environments only

👤 Author

Shishir A

Electronics & Communication Engineer

Focus Areas:
Autonomous UAV Systems
Edge AI & Robotics
Multi-Sensor Fusion

SLAM & Perception

Avionics & Embedded Systems
