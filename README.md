# 1-DoF Rocket Altitude Control System

This repository contains a 1-Degree-of-Freedom (1-DoF) vertical rocket altitude control simulation modeled in MATLAB & Simulink.
<img width="1302" height="420" alt="WhatsApp Image 2026-09-18 at 23 52 30" src="https://github.com/user-attachments/assets/c9237c18-bf03-4521-8c67-43c93f98e5fb" />
<img width="774" height="580" alt="WhatsApp Image 2026-09-18 at 23 53 03" src="https://github.com/user-attachments/assets/d6537fbe-7690-49df-aea2-015592beee5d" />


## System Parameters
* **Target Altitude:** 100 m
* **Rocket Mass ($m$):** 10 kg
* **Gravitational Acceleration ($g$):** 9.81 m/s²
* **Gravity Force:** 98.1 N

## Controller Details
* **Controller Type:** Continuous PID (Parallel Form)
* **Proportional ($P$):** 8
* **Integral ($I$):** 0.05
* **Derivative ($D$):** 18 (Filter coefficient $N = 100$)
* **Actuator Saturation:** 0 N to 250 N
* **Anti-Windup Method:** Clamping

## How to Run
1. Open MATLAB.
2. Open and run `roket_irtifa_pid_kontrol.slx`.
3. Double-click the **Scope** block to observe the altitude tracking performance.
