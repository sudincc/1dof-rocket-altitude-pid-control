# 1-DoF Rocket Altitude Control System

This repository contains a 1-Degree-of-Freedom (1-DoF) vertical rocket altitude control simulation modeled in MATLAB & Simulink.

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