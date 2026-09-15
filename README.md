# Vamshikrishna Gadde

**MS Robotics and Autonomous Systems Engineering**
Arizona State University, Tempe, AZ, Dec 2026

---

I build autonomous perception systems from scratch.
Not tutorials. Not wrappers. The actual math, the actual physics, the actual code.

Running a 90-day robotics portfolio. One real engineering project per day, on real datasets, with real benchmark numbers. Every project connects to the next. Every finding motivates what comes after.

---

## Series 1: Perception — Where Does Autonomous Perception Break?

| Project | Key Finding | Stack |
|---------|-------------|-------|
| [P1.1 LiDAR Obstacle Detection](https://github.com/GVK-Engine/day-001-lidar-obstacle-detection) | 28 objects detected in 86ms, 0.4m voxel creates ghost detections dangerous for braking | Python, Open3D, KITTI |
| [P1.2 Stereo Camera Depth Safety](https://github.com/GVK-Engine/day-002-stereo-depth-analysis) | MAE 1.04m at 0-10m, camera becomes unreliable beyond 35m in clear weather | OpenCV, NumPy, KITTI |
| [P1.3 PointPillars 3D Detector](https://github.com/GVK-Engine/day-003-pointpillars-3d-detector) | 98.9% training loss reduction, 2.5M parameter detector built from scratch | PyTorch, KITTI |
| [P1.4 Multi-Camera BEV Perception](https://github.com/GVK-Engine/day-004-bev-perception) | 178 objects unified from 6 cameras into one bird's eye view | OpenCV, nuScenes |
| [P1.5 Multi-Object Tracking SORT](https://github.com/GVK-Engine/day-005-multi-object-tracking) | 95.1% MOTP beats published paper baseline of 77.5%, 1158 FPS | NumPy, SciPy, filterpy |
| [P1.6 Semantic Segmentation ROS2](https://github.com/GVK-Engine/day-006-semantic-segmentation) | 52.6 FPS on RTX 4050, DeepLabV3 deployed in live ROS2 pipeline | PyTorch, CUDA, ROS2 |
| [P1.7 Adverse Weather Perception](https://github.com/GVK-Engine/day-007-adverse-weather-perception) | Fog unsafe below 75m visibility, rain safe at 100mm/hr, 42 conditions tested | NumPy, Marshall-Palmer |
| [P1.8 LiDAR-Camera Depth Completion](https://github.com/GVK-Engine/day-008-depth-completion) | 44x MAE improvement at 0-10m, 100% coverage from 4.1% sparse LiDAR input | OpenCV, NumPy, KITTI |
| [P1.9 Domain Shift Analysis](https://github.com/GVK-Engine/day-009-domain-shift) | 58.4% detection drop KITTI to nuScenes, root cause is sensor density not scene | PyTorch, YOLOv8, KITTI, nuScenes |
| [P1.10 Neural Occupancy Network](https://github.com/GVK-Engine/day-010-occupancy-network) | Unsafe planning boundary at 40m, 4-state uncertainty, 100% accuracy on 400k samples | PyTorch, CUDA, KITTI |
| [P1.11 ASU Campus Perception](https://github.com/GVK-Engine/day-011-asu-perception) | 56.5% detection drop in Arizona sun, larger model performed worse than smaller one | YOLOv8, OpenCV, real footage |
| [P1.12 Series 1 Capstone](https://github.com/GVK-Engine/day-012-series1-capstone) | All 11 projects compiled into one end-to-end perception stack demo video | Python, OpenCV, Matplotlib |

---

## Standalone Research

| Project | Key Finding | Stack |
|---------|-------------|-------|
| [AV Overconfidence Death Zone Mapper](https://github.com/GVK-Engine/av-overconfidence-mapper) | Confidence stays at 82% while accuracy collapses to 41%, death zone entry at 53% degradation, validated on 11,000 Monte Carlo trials and real KITTI footage | PyTorch, YOLOv8, NumPy, SciPy |

---

## Background

Mechanical engineering degree. Switched to robotics because I wanted to build things that move and think, not just things that hold still.

Before ASU I tested autonomous drone systems at TiHAN IIT-Hyderabad and did FEA work at Sravani Turbo Engineering. The gap between simulation and real hardware is where I learned most of what I know.

At ASU I have worked on a full ROS2 perception stack for TurtleBot4 in Gazebo Harmonic with YOLOWorld, SLAM, Nav2, and OpenMANIPULATOR-X, hexacopter 6DOF dynamics simulation in MATLAB/Simulink with minimum-jerk trajectory control, and RGBD point cloud semantic landmark extraction scoring 16 of 15 on the benchmark.

---

## Technical Stack

```
Languages      Python, C++ (basics), MATLAB
Deep Learning  PyTorch, torchvision, Ultralytics YOLOv8
Vision         OpenCV, Open3D, imageio
Robotics       ROS2 Humble, Gazebo Harmonic, Nav2, MoveIt2
Datasets       KITTI, nuScenes, MOT17, Cityscapes
Hardware       NVIDIA RTX 4050 6GB, Velodyne HDL-64E (KITTI)
Tools          Git, Linux, VMware Ubuntu 22.04, CUDA 12.4
```

---

## Portfolio Numbers

```
Projects complete        13 including standalone research
Datasets used            KITTI, nuScenes, MOT17, real ASU campus footage
Best tracking result     95.1% MOTP, beats published SORT paper baseline
Most impactful finding   Larger model performs worse under domain shift
Monte Carlo trials run   11,000 across 5 degradation conditions
Unsafe boundary found    40m on 64-beam LiDAR for occupancy planning
```

---

## What I Am Targeting

Perception Engineer, Sensor Fusion Engineer, Robotics Software Engineer

Open to full-time roles starting December 2026
---

## Contact

vamshikrishnagadde9999@gmail.com
[linkedin.com/in/vamshikrishna-gadde9999](https://linkedin.com/in/vamshikrishna-gadde9999)
vgadde5@asu.edu

---

*Building in public. Real data. Real findings. Real code.*
