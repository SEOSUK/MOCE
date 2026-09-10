# MOCE 2.0
*Center-of-Mass Estimation and Allocation Geometry Adaptation for Fully Actuated Multirotor UAVs*

**Project Period:** Apr. 2025 – Mar. 2026

<em>Accepted in Drones (MDPI), 2026 — “Transient-Buffered Allocation Geometry Adaptation for Fully Actuated Multirotor UAVs under Center-of-Mass Variations” — Seuk Seo, Hyungeun Park, Geonwoo Park, Seung Jae Lee*</em>

## 🔹 Overview

<table>
  <tr>
    <td width="46%" align="center">
      <img src="https://github.com/user-attachments/assets/eddd60d9-76bd-4b92-bda5-ebd023d18d79"
           alt="MOCE 2.0 Overview"
           width="380">
    </td>
    <td width="54%" valign="middle">
      <ul>
        <li><b>Online CoM estimation</b> from disturbance-observer compensation.</li>
        <li><b>CoM-aware allocation geometry update</b> for fully actuated multirotors.</li>
        <li><b>DOB-based transient buffering</b> during adaptation.</li>
      </ul>
    </td>
  </tr>
</table>

## 🔹 Methodology

<div align="center">
  <img src="https://github.com/user-attachments/assets/afa47ee2-17ea-46cd-b95c-9d9b29e2364a"
       alt="MOCE 2.0 Methodology"
       width="900">
</div>

## 🎥 Project Demo

https://github.com/user-attachments/assets/3ce91ad8-b30f-407b-aef7-a513a4e25c3f

## 🔹 Repository Structure

- [`px4_firmware`](./px4_firmware) — Modified PX4 firmware for **fully actuated control allocation, disturbance observation, and online CoM estimation**.
- [`ros2_interface`](./ros2_interface) — PX4–ROS 2 bridge for **experiment logging and servo interfacing**.
- [`MOCE_simulation`](https://github.com/SEOSUK/MOCE_simulation) — **Flight-data-calibrated MuJoCo simulation** for validation and Monte Carlo robustness analysis.
