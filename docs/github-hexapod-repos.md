# GitHub Hexapod / Spider Robot References

Curated list of open-source hexapod and spider-like walking robot repositories on GitHub.
Sorted by relevance to HESAR project.

## Simulators & Kinematics

- [mithi/hexapod-robot-simulator](https://github.com/mithi/hexapod-robot-simulator) — Python first-principles hexapod simulator. Great for kinematics and gait prototyping. Stars: 869.
- [mithi/hexapod](https://github.com/mithi/hexapod) — Fast web-based hexapod simulator (JavaScript). Useful for visualizing gaits. Stars: 753.
- [neuroprod/InsectRobotSimulation](https://github.com/neuroprod/InsectRobotSimulation) — C++ insect/hexapod gait simulation. Stars: 313.
- [Indystrycc/SpdrBot](https://github.com/Indystrycc/SpdrBot) — 4-legged spider robot simulation with NVIDIA IsaacSim + AI. Stars: 137.

## ROS Workflows

- [tuuzdu/crab_project](https://github.com/tuuzdu/crab_project) — ROS hexapod on BeagleBone Black. Good reference for ROS node structure and launch files. Stars: 101.
- [antdroid-hexapod/antdroid](https://github.com/antdroid-hexapod/antdroid) — C++ ROS hexapod stack. Stars: 72.
- [dmweis/Hopper_ROS](https://github.com/dmweis/Hopper_ROS) — Python ROS stack for hexapod navigation and control. Stars: 60.

## Hardware & 3D Models

- [CoretechR/ZeroBug](https://github.com/CoretechR/ZeroBug) — DIY hexapod robot kit. Good BOM and mechanical design reference. Stars: 293.
- [rookidroid/hexapod](https://github.com/rookidroid/hexapod) — 3D printed hexapod project. Stars: 105.
- [robs-tech-workbench/hexapod_spiderbot_model](https://github.com/robs-tech-workbench/hexapod_spiderbot_model) — STL files, printing instructions, build docs.
- [robs-tech-workbench/hexapod_spiderbot_tutorials](https://github.com/robs-tech-workbench/hexapod_spiderbot_tutorials) — Jupyter notebooks with kinematics, IK and assembly tutorial. Stars: 93.

## Embedded Control

- [myyerrol/hexapod-bionic-robot](https://github.com/myyerrol/hexapod-bodyc-robot) — 18 DOF Arduino hexapod firmware. Stars: 22.
- [Freenove/Freenove_Big_Hexapod_Robot_Kit_for_Raspberry_Pi](https://github.com/Freenove/Freenove_Big_Hexapod_Robot_Kit_for_Raspberry_Pi) — Python + Raspberry Pi kit. Stars: 163.

## Notes

- Prefer Python/C++ repos for faster integration into ROS2 + HESAR.
- JS simulators (mithi/hexapod) are useful for quick gait visualization, not for onboard control.
- Hardware repos are references only; HESAR mechanical design will be custom.
