---
permalink: /en/
layout: archive
title: "About"
lang: en
author_profile: true
redirect_from:
  - /en/about.html
---

{% include base_path %}

* **Research focus:** Embodied Visual-language Navigation; Visual-LiDAR SLAM (LIOSAM, ORBSLAM3, FASTLIVO2); 3D Reconstruction (Colmap, Gaussian Splatting)
* **Email:** [mr.bangxiao@gmail.com](mailto:mr.bangxiao@gmail.com)

---

Education
======
* **M.Eng.** Wuhan University, Resources and Environment, Sept 2018 – June 2024
* **B.Eng.** Wuhan University, Navigation Engineering / Engineering Management (minor), Sept 2014 – June 2018

---

Work experience
======

**Horizon Robotics**  ｜  Embodied Algorithm Engineer  ｜  July 2024 – Present

* **Pure visual semantic SLAM based on feedforward reconstruction models**
  * Introduction: Pure visual navigation and localization based on feedforward reconstruction models such as DepthAnythingV3.
  * Responsible for system architecture design and implementation. Using geometric-semantic priors from feedforward reconstruction models to achieve robust, high-precision, real-time open-vocabulary semantic mapping.

* **Humanoid robot VLN navigation system**
  * Introduction: VLN system for Unitree-G1 with voice interaction, real-time obstacle avoidance, and open-vocabulary semantic goal navigation.
  * Project: [https://horizonrobotics.github.io/robot_lab/fsr-vln/](https://horizonrobotics.github.io/robot_lab/fsr-vln/) (100+ star)
  * Responsible for multi-sensor extrinsic calibration and visual-LiDAR fusion mapping and localization, with focus on Nvidia Jetson for robustness, efficiency, and memory; participated in VLN framework design, full pipeline implementation, and deployment (voice, mapping & localization, semantic scene graph, path planning, dynamic obstacle avoidance).

* **VSLAM visual reconstruction and navigation**
  * Introduction: High-precision camera poses for Real2Sim visual reconstruction, and visual navigation and localization for legged robots.
  * Project: [https://github.com/HorizonRobotics/GeoFlowSlam](https://github.com/HorizonRobotics/GeoFlowSlam) (100+ star)
  * Responsible for VSLAM iteration and optimization; addressed visual mapping and localization under motion blur, weak texture, and IMU vibration via leg odometry, optical flow, NN-features, and multi-view constraints; participated in building and optimizing the Real2Sim reconstruction pipeline, using Colmap for offline VSLAM pose refinement to provide high-precision geometric priors for Gaussian Splatting reconstruction.

* **AGV logistics robot lidar navigation and localization**
  * Introduction: POC commercialization project for AGV automated handling in factory shelf environments.
  * Responsible for multi-LiDAR extrinsic calibration and laser SLAM mapping and localization design and implementation; established full pipeline from offline calibration and mapping to real-time localization; participated in early solution study and sensor selection, layout, and installation.

**Horizon Robotics**  ｜  Mapping & localization algorithm engineer (intern)  ｜  Mar 2024 – July 2024

* **Driving / parking localization**
  * Driving: Developed roadside intrusion detection to identify scenarios such as curb intrusion into HD map lanes due to construction, supporting localization degradation for collision avoidance.
  * Parking: Responsible for VPR solution evaluation; benchmarked robustness of SALAD, EigenPlaces, etc. on in-house indoor/outdoor vehicle datasets to inform decisions on map broadcast errors and localization failure caused by adjacent garage entrances or GNSS drift.

**Momenta**  ｜  Mapping & localization algorithm engineer (intern)  ｜  June 2023 – Oct 2023

* **High-speed driving localization**
  * Addressed unstable relocalization at high speed by introducing semantic constraints (e.g. longitudinal lines, poles) in map matching; fused relocalization results with MSCKF filter and output fused vehicle pose.

---

Publications (during work)
======
* **FSR-VLN:** Fast and Slow Reasoning for Vision-Language Navigation with Hierarchical Multi-modal Scene Graph, [https://horizonrobotics.github.io/robot_lab/fsr-vln/](https://horizonrobotics.github.io/robot_lab/fsr-vln/), IROS 2026 under review, co-first author
* **GeoFlow-SLAM:** A Robust Tightly-Coupled RGBD-Inertial and Legged Odometry Fusion SLAM for Dynamic Legged Robotics, [https://github.com/HorizonRobotics/GeoFlowSlam](https://github.com/HorizonRobotics/GeoFlowSlam), IROS 2025, first author
* **IRIS-SLAM:** Unified Geo-Instance Representations for Robust Semantic Localization and Mapping
* 1 granted invention patent (AGV mapping and localization)
