# MOCE 2.0
*Center-of-Mass Estimation and Allocation Geometry Adaptation for Fully Actuated Multirotor UAVs*

**Project Period:** Apr. 2025 – Mar. 2026

## 🔹 Overview
MOCE 2.0 is a PX4-based framework that estimates **center-of-mass (CoM) variation online** and adapts the **control-allocation geometry** of a fully actuated multirotor, while a disturbance observer buffers transient and residual disturbances.

<div align="center">
  <img src="https://github.com/user-attachments/assets/eddd60d9-76bd-4b92-bda5-ebd023d18d79"
       alt="MOCE 2.0 Overview"
       width="850">
</div>

- **Online CoM estimation** from disturbance-observer compensation.
- **CoM-aware allocation geometry update** for fully actuated multirotors.
- **DOB-based transient buffering** during adaptation.

## 🎥 Project Demo

https://github.com/user-attachments/assets/3ce91ad8-b30f-407b-aef7-a513a4e25c3f

## 🔹 Methodology

<div align="center">
  <img src="https://github.com/user-attachments/assets/afa47ee2-17ea-46cd-b95c-9d9b29e2364a"
       alt="MOCE 2.0 Methodology"
       width="900">
</div>

## 🔹 Repository Structure

- [`px4_firmware`](./px4_firmware) — Modified PX4 firmware for **fully actuated control allocation, disturbance observation, and online CoM estimation**.
- [`ros2_interface`](./ros2_interface) — PX4–ROS 2 bridge for **experiment logging and servo interfacing**.
- [`MOCE_simulation`](https://github.com/SEOSUK/MOCE_simulation) — **Flight-data-calibrated MuJoCo simulation** for validation and Monte Carlo robustness analysis.

## 🔹 Keywords
- **CoM Estimation**
- **Control Allocation**
- **Fully-Actuated Multirotor**
- **PX4**

## 🔹 Publication
✅ **Accepted in Drones (MDPI), 2026**

**Transient-Buffered Allocation Geometry Adaptation for Fully Actuated Multirotor UAVs under Center-of-Mass Variations**

**Seuk Seo**, Hyungeun Park, Geonwoo Park, Seung Jae Lee  
*First author: Seuk Seo*
