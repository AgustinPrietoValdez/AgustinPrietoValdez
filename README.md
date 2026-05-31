<h1 align="center">Agustín Prieto Valdez</h1>

<p align="center">
  <strong>Mobile Robotics &amp; Autonomous Systems</strong> · ROS 2 · SLAM · Nav2 · Embedded
  <br/>
  Incoming Engineering Student @ Aalborg University · Esbjerg, Denmark
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/agustin-prieto-valdez">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:agusprietovaldez@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email" />
  </a>
</p>

---

### About

I'm an electronics engineering student focused on mobile robotics and autonomous systems.
I build robots end-to-end — from embedded firmware up to the ROS 2 navigation stack — and I
like the messy middle where software meets the physical world. Two years into an electronics
engineering degree (UTN, Argentina), I'm continuing at Aalborg University (Esbjerg, Denmark)
from September 2026.

**Open to internship / student / graduate robotics roles in Denmark &amp; EU** — mobile robots,
navigation, perception, controls, or embedded.

---

## Featured project — cargo_bot

[**cargo_bot_ws**](https://github.com/AgustinPrietoValdez/cargo_bot_ws) · differential-drive autonomous indoor robot · ROS 2 Humble · NVIDIA Isaac Sim 5.1

A differential-drive cargo robot developed **sim-first** in NVIDIA Isaac Sim 5.1 with ROS 2
Humble (WSL2), bridged over a Fast DDS Discovery Server. Built from scratch — URDF model,
simulation scene, sensor integration, and the full ROS 2 software stack — targeting STM32 +
Raspberry Pi hardware.

- **2D SLAM** with `slam_toolbox` — has mapped a ~5 × 5 m indoor room (tag `v0.3-slam`).
- **EKF localization** with `robot_localization`, fusing wheel odometry with IMU yaw; killed ~15°/run heading drift by anchoring the filter with absolute yaw.
- Diagnosed and fixed an Isaac RTX-lidar **off-by-one beam-count bug** (1066 vs 1067) that silently broke `slam_toolbox`, via a custom scan-republisher node.
- Sensing: **RPLIDAR S2E** + **IMU**. Now extending the stack toward **Nav2** autonomous navigation.

<!-- TODO: record a short demo (RViz live map building, or the Isaac Sim scene) and host it,
     then uncomment the line below. Drag a .gif/.mp4 into a GitHub Issue/PR comment to get a
     hosted user-images URL, or commit assets/cargo_bot_demo.gif and use a relative path.
![cargo_bot demo](assets/cargo_bot_demo.gif)
-->

![ROS 2](https://img.shields.io/badge/ROS_2_Humble-22314E?style=flat&logo=ros&logoColor=white)
![Isaac Sim](https://img.shields.io/badge/Isaac_Sim_5.1-76B900?style=flat&logo=nvidia&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat&logo=raspberrypi&logoColor=white)

**Status:** DDS bridge ✓ · URDF model ✓ · Isaac scene + ROS 2 bridge ✓ · SLAM (IMU + EKF, saved map) ✓ · Nav2 in progress

---

## Also building — plan

[**plan**](https://github.com/AgustinPrietoValdez/plan) · offline-first personal organization app (desktop + Android)

Calendar, tasks, habits, budget and anti-waste meal planning, built cross-platform with Tauri 2,
React and TypeScript, syncing via Supabase. MIT licensed.

![Tauri](https://img.shields.io/badge/Tauri_2-24C8DB?style=flat&logo=tauri&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white)

---

## Skills &amp; Tech

**Robotics &amp; ROS 2**

![ROS 2](https://img.shields.io/badge/ROS_2_Humble-22314E?style=flat&logo=ros&logoColor=white)
![SLAM](https://img.shields.io/badge/SLAM_(slam__toolbox)-5C2D91?style=flat)
![Nav2](https://img.shields.io/badge/Nav2-22314E?style=flat&logo=ros&logoColor=white)
![EKF](https://img.shields.io/badge/EKF_/_robot__localization-1F6FEB?style=flat)
![Isaac Sim](https://img.shields.io/badge/NVIDIA_Isaac_Sim-76B900?style=flat&logo=nvidia&logoColor=white)

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Embedded &amp; Hardware**

![STM32](https://img.shields.io/badge/STM32-03234B?style=flat&logo=stmicroelectronics&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=flat&logo=raspberrypi&logoColor=white)
![KiCad](https://img.shields.io/badge/PCB_Design_(KiCad)-314CB6?style=flat&logo=kicad&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion_360-FF6F00?style=flat&logo=autodesk&logoColor=white)

**Tools &amp; Platforms**

![Linux](https://img.shields.io/badge/Linux_/_WSL-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

---

## Currently working on

- Extending **cargo_bot** toward full **Nav2** autonomy (path planning + control).
- Learning Danish; deepening perception &amp; controls for mobile robots.

## Open to

Internship / student / graduate **robotics roles in Denmark &amp; EU** — mobile robots,
navigation, perception, controls, or embedded systems. Full right to work in the EU.

---

## Contact

- **GitHub:** [@AgustinPrietoValdez](https://github.com/AgustinPrietoValdez)
- **LinkedIn:** [agustin-prieto-valdez](https://www.linkedin.com/in/agustin-prieto-valdez)
- **Email:** [agusprietovaldez@gmail.com](mailto:agusprietovaldez@gmail.com)
