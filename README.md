# HESAR

**HE**xapod **S**earch **A**nd **R**escue

Post-disaster SAR robotics platform for landslide and flood terrain.

## Mission
Autonomous hexapod designed for search and rescue in disaster zones where wheeled/drone access is limited.

## Structure
- `heron_description/` — URDF + Xacro
- `heron_simulation/` — Gazebo + MuJoCo
- `heron_firmware/` — STM32/ESP32 embedded control
- `heron_navigation/` — SLAM + path planning
- `heron_control/` — PID/LQR/MPC + gaits
- `heron_bringup/` — ROS2 launch files
- `docs/` — specs and architecture
- `raw/papers/` — references and papers
