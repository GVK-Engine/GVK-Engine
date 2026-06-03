# Vamshikrishna Gadde 

**MS Robotics & Autonomous Systems Engineering**
Arizona State University · Tempe, AZ · Dec 2026

---

I build autonomous perception systems from scratch.
Not tutorials. Not wrappers. The actual math, the actual physics, the actual code.

Currently running a 90-day robotics portfolio - one real engineering project per day,
on real datasets, with real benchmark numbers.
Every project connects to the next. Every finding motivates what comes after.

---

## What I Am Building

**Series 1: Perception** - *Where does autonomous perception break?*

| # | Project | Key Finding | Stack |
|---|---------|-------------|-------|
| P1.1 | [LiDAR Obstacle Detection](https://github.com/GVK-Engine/day-001-lidar-obstacle-detection) | 0.4m voxel creates ghost detections dangerous for braking | Python · Open3D · KITTI |
| P1.2 | [Stereo Camera Depth Safety](https://github.com/GVK-Engine/day-002-stereo-depth-analysis) | Safety threshold crossed at 10m - std dev 2.1m at 50m | OpenCV · NumPy · KITTI |
| P1.3 | [PointPillars 3D Detector](https://github.com/GVK-Engine/day-003-pointpillars-3d-detector) | 98.9% loss reduction - Waymo's production detector built from scratch | PyTorch · KITTI |
| P1.4 | [Multi-Camera BEV Perception](https://github.com/GVK-Engine/day-004-bev-perception) | 178 objects unified from 6 cameras - Tesla FSD architecture | OpenCV · nuScenes |
| P1.5 | [Multi-Object Tracking SORT](https://github.com/GVK-Engine/day-005-multi-object-tracking) | 95.1% MOTP beats published paper - 1158 FPS on real MOT17 | NumPy · SciPy · filterpy |
| P1.6 | [Semantic Segmentation ROS2](https://github.com/GVK-Engine/day-006-semantic-segmentation) | 52.6 FPS on RTX 4050 - 3 topics published per frame | PyTorch · CUDA · ROS2 |
| P1.7 | [Adverse Weather Analysis](https://github.com/GVK-Engine/day-007-adverse-weather-perception) | Fog unsafe below 75m visibility - rain safe at 100mm/hr | NumPy · Marshall-Palmer |

*Series 2 (Sensor Fusion + SLAM) starts Day 13.*
*Series 3 (Navigation) · Series 4 (UAV) · Series 5 (Control) · Series 6 (Manufacturing) · Series 7 (Safety)*

---

## Background

Mechanical engineering degree. Switched to robotics because I wanted to build things that move and think, not just things that hold still.

Before ASU I tested autonomous drone systems at TiHAN IIT-Hyderabad and did FEA work at Sravani Turbo Engineering. The gap between simulation and real hardware is where I learned most of what I know.

At ASU I have worked on:
- Full ROS2 perception stack for TurtleBot4 in Gazebo Harmonic with YOLOWorld, SLAM, Nav2, and OpenMANIPULATOR-X
- Hexacopter 6DOF dynamics simulation in MATLAB/Simulink with minimum-jerk trajectory control
- RGBD point cloud semantic landmark extraction - 16/15 on the benchmark

Now I am building the 90-day series to prove I can work at the full AV stack depth, not just one layer of it.

---

## Technical Stack

```
Languages    Python · C++ (basics) · MATLAB
DL / Vision  PyTorch · OpenCV · torchvision · Open3D
Robotics     ROS2 Humble · Gazebo Harmonic · Nav2 · MoveIt2
Datasets     KITTI · nuScenes · MOT17 · Cityscapes
Hardware     NVIDIA RTX 4050 · Velodyne HDL-64E (KITTI)
Tools        Git · Linux · VMware Ubuntu 22.04
```

---

## What I Am Targeting

Perception Engineer · Sensor Fusion Engineer · Robotics Software Engineer

**Companies:** Waymo · Tesla · AeroVironment · Aurora · Amazon Robotics · Boston Dynamics · Joby Aviation · Shield AI

Open to roles starting **December 2026** (F-1 OPT, 36-month STEM extension eligible)

---

## Numbers From the Portfolio So Far

```
Projects complete    7 of 73 planned
Datasets used        KITTI · nuScenes · MOT17
GPU                  NVIDIA RTX 4050 · 6GB VRAM · CUDA 13
Best result          95.1% MOTP — beats published SORT paper
Most novel finding   LiDAR ODD boundary measured under 13 weather conditions
Frameworks           PyTorch · ROS2 · Open3D · OpenCV
```

---

## Contact

**Email** vamshikrishnagadde9999@gmail.com
**LinkedIn** [linkedin.com/in/vamshikrishna-gadde9999](https://linkedin.com/in/vamshikrishna-gadde9999)
**ASU Email** vgadde5@asu.edu

---

*Building in public. One project per day. Real data. Real findings.*
