# Vamshikrishna Gadde

**MS Robotics and Autonomous Systems Engineering**
Arizona State University, Tempe, AZ, Dec 2026

---

I build autonomous perception systems from scratch.
Not tutorials. Not wrappers. The actual math, the actual physics, the actual code.

Every project in this portfolio is on real sensor data, produces a specific measurable finding, and connects to the next project. The series reads as a single engineering argument, not a list of exercises.

---

## The Numbers That Matter

```
Detection drop measured across two continents:   58.4%
MAE improvement from sensor fusion:              44x at 0-10m
Tracker throughput beating the published paper:  95.1% MOTP vs 77.5%
Unsafe LiDAR planning boundary found at:         40m
Glare collapse on Arizona sun:                   56.5% drop
Model size that made glare worse:                68M parameters (vs 3.2M)
Monte Carlo trials for overconfidence analysis:  11,000
Death zone entry under exposure loss + glare:    53% degradation
```

---

## Series 1: Perception - Where Does Autonomous Perception Break?

| Project | Key Finding | Stack |
|---------|-------------|-------|
| [P1.1 LiDAR Obstacle Detection](https://github.com/GVK-Engine/day-001-lidar-obstacle-detection) | 28 objects in 86ms. Voxel size is a safety decision. 0.4m creates ghost detections that trigger phantom braking. | Python, Open3D, KITTI |
| [P1.2 Stereo Camera Depth Safety](https://github.com/GVK-Engine/day-002-stereo-depth-analysis) | MAE 1.04m at 0-10m. MAE 8.81m at 50m+. Standard deviation at 50m is 2.14m. The error is not just large. It is unpredictable. | OpenCV, NumPy, KITTI |
| [P1.3 PointPillars 3D Detector](https://github.com/GVK-Engine/day-003-pointpillars-3d-detector) | 2.5M parameter detector built from scratch. 98.9% loss reduction in 10 epochs. No pretrained weights. | PyTorch, KITTI |
| [P1.4 Multi-Camera BEV Perception](https://github.com/GVK-Engine/day-004-bev-perception) | 178 objects from 6 cameras in one unified top-down view. IPM ground plane assumption breaks for tall objects. | OpenCV, nuScenes |
| [P1.5 Multi-Object Tracking SORT](https://github.com/GVK-Engine/day-005-multi-object-tracking) | 95.1% MOTP beats paper 77.5%. 1158 FPS on CPU. The bottleneck is always the detector. | NumPy, SciPy, filterpy |
| [P1.6 Semantic Segmentation ROS2](https://github.com/GVK-Engine/day-006-semantic-segmentation) | 52.6 FPS steady state. Frame 1 runs at 4.5 FPS. GPU warmup cost is real and most benchmarks hide it. | PyTorch, CUDA, ROS2 |
| [P1.7 Adverse Weather Perception](https://github.com/GVK-Engine/day-007-adverse-weather-perception) | Rain at 100mm/hr is survivable. Fog below 75m is not. They fail in completely different ways and need different safety responses. | NumPy, Marshall-Palmer |
| [P1.8 LiDAR-Camera Depth Completion](https://github.com/GVK-Engine/day-008-depth-completion) | 44x MAE improvement at 0-10m. 100% coverage from 4.1% sparse LiDAR. 80/20 holdout evaluation. | OpenCV, NumPy, KITTI |
| [P1.9 Domain Shift Analysis](https://github.com/GVK-Engine/day-009-domain-shift) | 58.4% detection drop KITTI to nuScenes. Root cause: sensor density, not scene. HDL-64E 121k pts vs HDL-32E 34k pts. | PyTorch, YOLOv8, KITTI, nuScenes |
| [P1.10 Neural Occupancy Network](https://github.com/GVK-Engine/day-010-occupancy-network) | Unsafe planning boundary at 40m. FREE-CONFIRMED and FREE-ASSUMED equalize at that distance. 4-state uncertainty. 100% CNN accuracy on 400k samples. | PyTorch, CUDA, KITTI |
| [P1.11 ASU Campus Perception](https://github.com/GVK-Engine/day-011-asu-perception) | 56.5% detection drop in Arizona sun. YOLOv8x (68M params) performed worse than nano (3.2M) in glare. You cannot scale out of a distribution mismatch. | YOLOv8, OpenCV, real footage |
| [P1.12 Series 1 Capstone](https://github.com/GVK-Engine/day-012-series1-capstone) | All 11 projects compiled into one video. Every visual output. Every finding. | Python, OpenCV, Matplotlib |

---

## Standalone Research

| Project | Key Finding | Stack |
|---------|-------------|-------|
| [AV Overconfidence Death Zone Mapper](https://github.com/GVK-Engine/av-overconfidence-mapper) | Confidence stays at 82% while accuracy collapses to 41% under glare. Death zone entry at 53% degradation. Divergence starts 20 points earlier. Validated on 11,000 Monte Carlo trials and real KITTI footage with YOLOv8. | PyTorch, YOLOv8, NumPy, SciPy |

---

## Background

Mechanical engineering degree. Switched to robotics because I wanted to build things that move and think, not just things that hold still.

Before ASU I tested autonomous drone systems at TiHAN IIT-Hyderabad and did FEA work at Sravani Turbo Engineering. The gap between simulation and real hardware is where I learned most of what I know.

At ASU: full ROS2 perception stack for TurtleBot4 in Gazebo Harmonic with YOLOWorld, SLAM, Nav2, and OpenMANIPULATOR-X. Hexacopter 6DOF dynamics simulation in MATLAB/Simulink with minimum-jerk trajectory control. RGBD point cloud semantic landmark extraction scoring 16 of 15 on the benchmark.

---

## Technical Stack

```
Languages        Python, C++ (basics), MATLAB
Deep Learning    PyTorch, torchvision, Ultralytics YOLOv8
Vision           OpenCV, Open3D, imageio
Robotics         ROS2 Humble, Gazebo Harmonic, Nav2, MoveIt2
Datasets         KITTI, nuScenes, MOT17, Cityscapes, real campus footage
Hardware         NVIDIA RTX 4050 6GB, Velodyne HDL-64E (KITTI)
Tools            Git, Linux, VMware Ubuntu 22.04, CUDA 12.4
```

---

## What I Am Targeting

Perception Engineer, Sensor Fusion Engineer, Robotics Software Engineer

Available full-time from December 2026. F-1 OPT eligible, 36-month STEM extension.

---

## Contact

vamshikrishnagadde9999@gmail.com
[linkedin.com/in/vamshikrishna-gadde9999](https://linkedin.com/in/vamshikrishna-gadde9999)

---

*Real data. Real findings. Real code.*
