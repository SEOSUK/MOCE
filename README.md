# MOCE 2.0
*Center-of-Mass Estimation and Allocation Geometry Adaptation for Fully Actuated Multirotor UAVs*

**Project Period:** Apr. 2025 – Mar. 2026

<em>Accepted in <a href="https://www.mdpi.com/2504-446X/10/9/673">Drones (MDPI)</a>, 2026 — “Transient-Buffered Allocation Geometry Adaptation for Fully Actuated Multirotor UAVs under Center-of-Mass Variations” — Seuk Seo, Hyungeun Park, Geonwoo Park, Seung Jae Lee*</em>

## 🔹 Methodology

<div align="center">
  <img src="https://github.com/user-attachments/assets/afa47ee2-17ea-46cd-b95c-9d9b29e2364a"
       alt="MOCE 2.0 Methodology"
       width="900">
</div>

- **Online CoM estimation** from disturbance-observer compensation.
- **CoM-aware allocation geometry update** for fully actuated multirotors.
- **DOB-based transient buffering** during adaptation.

## 🎥 Project Demo

<div align="center">
  <img src="https://github.com/user-attachments/assets/2bd8a3b7-dce3-4054-8232-4bc61926ae98"
       alt="MOCE 2.0 Real-World Validation"
       width="900">
</div>

🔗 [Full Video Version](https://www.youtube.com/watch?v=IqTcnkQkOss&t=1s)

## 🔹 Simulation-Based Validation

https://github.com/user-attachments/assets/69440d7c-72fa-48b6-b2dc-c435f4277e90

- **Real-flight-data-calibrated MuJoCo model** including actuator dynamics, measurement uncertainty, and stochastic residual force/torque.
- **Real-world vs. simulation comparison** for MOCE 2.0 and the DOB baseline under matched CoM-biased conditions.

🔗 [MOCE Simulation Repository](https://github.com/SEOSUK/MOCE_simulation)

## 🔹 Repository Structure

- [`px4_firmware`](./px4_firmware) — Modified PX4 firmware for **fully actuated control allocation, disturbance observation, and online CoM estimation**.
- [`ros2_interface`](./ros2_interface) — PX4–ROS 2 bridge for **experiment logging and servo interfacing**.
- [`MOCE_simulation`](https://github.com/SEOSUK/MOCE_simulation) — **Flight-data-calibrated MuJoCo simulation** for validation and Monte Carlo robustness analysis.
