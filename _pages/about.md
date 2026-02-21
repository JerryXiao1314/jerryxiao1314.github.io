---
permalink: /
layout: archive
title: "基本信息"
lang: zh
author_profile: true
redirect_from:
  - /about/
  - /about.html
  - /cv/
  - /resume
---

{% include base_path %}

* **研究方向**：Embodied Visual-language Navigation；Visual-LiDAR SLAM（LIOSAM、ORBSLAM3、FASTLIVO2）；3D Reconstruction（Colmap、Gaussian Splatting）
* **联系邮箱**：[mr.bangxiao@gmail.com](mailto:mr.bangxiao@gmail.com)

---

教育背景
======
* **硕士**：武汉大学，资源与环境，工学硕士，2018.09 - 2024.06
* **本科**：武汉大学，导航工程 / 工程管理（辅修），工学学士，2014.09 - 2018.06

---

工作经历
======

**地平线机器人**    ｜    具身算法工程师    ｜    2024.07 - 至今

* **基于前馈重建模型的纯视觉语义 SLAM**
  * 项目介绍：探索基于 DepthAnythingV3 等前馈重建模型的纯视觉导航与定位方案。
  * 项目主页：[fsr-vln](https://horizonrobotics.github.io/robot_lab/fsr-vln/)
  * 主导系统架构设计与实现，基于前馈重建模型的几何语义先验实现纯视觉开放词汇语义建图。
  <!-- * 产出：形成基于前馈重建模型的纯视觉语义 SLAM 方案，相关技术成果已投稿 RSS 2026；通过算法重构将语义建图效率较原 fsr-vln 提升约 10 倍。 -->

* **人形机器人 VLN 导航系统**
  * 项目介绍：面向 Unitree-G1 的 VLN 系统，支持语音交互、实时避障与开放词汇语义目标导航。
  * 项目主页：[FSR-VLN](https://horizonrobotics.github.io/robot_lab/fsr-vln/) (100+ star)
  * 工作内容：负责多传感器外参标定、视觉-激光融合建图与定位，重点针对 Nvidia Jetson 平台优化鲁棒性、效率与内存占用；参与 VLN 系统框架设计与全模块搭建及部署测试（语音交互、建图定位、语义场景图、路径规划、动态避障等）。
  <!-- * 产出：交付高鲁棒、低延迟的人形机器人导航框架，完成多场景长距离导航演示并获客户认可；共同一作论文已投稿 IROS 2026。 -->

* **VSLAM 视觉重建与导航**
  * 项目背景：为 Real2Sim 视觉重建提供高精度相机位姿，并为足式机器人提供视觉导航定位方案。
  * 项目主页：[GeoFlowSlam](https://github.com/HorizonRobotics/GeoFlowSlam) (100+ star)
  * 工作内容：负责 VSLAM 方案迭代优化，通过引入足式里程计、光流、NN-feature、多目观测等约束，解决足式机器人在运动模糊、弱纹理及 IMU 高频振动下的视觉建图定位难题；参与搭建并优化 Real2Sim 重建链路，利用 Colmap 对 VSLAM 位姿离线精化，为 Gaussian Splatting 重建提供高精度几何先验。
  <!-- * 产出：形成兼顾高精度重建与实时导航的 RGBD VSLAM 方案；以第一作者完成相关论文 GeoFlowSLAM，已被 IROS 2025 接收。 -->

* **AGV 物流机器人激光导航定位**
  * 项目背景：POC 商业项目，面向工厂货架场景的 AGV 自动搬运与摆放。
  * 工作内容：负责多激光雷达外参标定及激光 SLAM 建图与定位方案的设计与搭建，建立从离线标定、建图到实时在线定位的完整工程链路；参与前期方案调研与传感器选型、布局及安装。
  <!-- * 产出：通过客户演示验收并推动后续商业合作；作为第一发明人获 1 项 AGV 导航定位相关专利授权。 -->

**地平线机器人**  ｜  建图定位算法工程师（实习）  ｜  2024.03 - 2024.07

* **行车 / 泊车定位**
  * 行车方面：开发路侧入侵检测，识别因施工导致的路沿入侵高精地图车道等场景，支撑定位系统降级策略以规避碰撞风险。
  * 泊车方面：负责 Visual Place Recognition（VPR）方案工程评估，在自采室内外车载数据集上对比 SALAD、EigenPlaces 等算法的鲁棒性，为应对车库入口相邻或 GNSS 漂移导致的地图播发错误与定位失败提供决策依据。
<!-- * 产出：路侧入侵检测有效检出率 70%，显著保障行车安全；完成多组 VPR 算法在公开与自采数据集上的评测，为泊车定位播图策略提供决策依据。 -->

**Momenta**   ｜  建图定位算法工程师（实习）  ｜  2023.06 - 2023.10

* **高速行车定位**
  * 针对高速场景下重定位不稳定问题，在地图匹配模块中引入纵线、杆状物等语义特征约束，并使用 MSCKF 滤波对重定位结果进行融合，输出车辆融合定位结果。
<!-- * 产出：重定位模块有效输出率由 34.6% 提升至 70.7%；融合定位纵向精度由 0.72 m 优化至 0.25 m。 -->

---

学术成果（工作期间）
======
* **FSR-VLN: Fast and Slow Reasoning for Vision-Language Navigation with Hierarchical Multi-modal Scene Graph**，[FSR-VLN](https://horizonrobotics.github.io/robot_lab/fsr-vln/) (100+ star)，IROS 2026 在投，共同一作
* **GeoFlow-SLAM: A Robust Tightly-Coupled RGBD-Inertial and Legged Odometry Fusion SLAM for Dynamic Legged Robotics**，[GeoFlowSlam](https://github.com/HorizonRobotics/GeoFlowSlam) (100+ star)，IROS 2025，第一作者
* **IRIS-SLAM: Unified Geo-Instance Representations for Robust Semantic Localization and Mapping**
* AGV 建图定位发明专利授权 1 项
