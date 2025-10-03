# MATLAB Simulation: Mechanics of a Self-Balancing Toy

This repository contains a MATLAB script that simulates the nonlinear dynamics of a self-balancing toy, modeled as an inverted pendulum. This project was completed as an assignment for a first-semester Engineering Mechanics course.

## 📝 Description

The simulation solves the full nonlinear equation of motion for a simple pendulum using MATLAB's `ode45` solver. It's designed to analyze the system's behavior, particularly for large initial angles where linear approximations would be inaccurate.

## ✨ Features

The script automatically generates three outputs upon running:

1.  **Phase Space Plot:** Visualizes the relationship between the toy's angular displacement ($\theta$) and angular velocity ($\dot{\theta}$).

    ![Phase Space Plot](https://github.com/shredfwd/Self-Balancing-Toy/blob/main/figures/phase%20space%20plot.png)

2.  **Energy Analysis:** Plots the Kinetic Energy, Potential Energy, and Total Mechanical Energy of the system over time.

    ![Energy Analysis Plot](https://github.com/shredfwd/Self-Balancing-Toy/blob/main/figures/Energy.png)

3.  **Live Animation:** A simple animation shows the toy swinging from its pivot point.

    ![Live Animation of the Simulation](https://github.com/shredfwd/Self-Balancing-Toy/blob/main/figures/balancing%20animation.gif)

## 🚀 How to Run

1.  Make sure you have MATLAB installed.
2.  Open the `code/main_simulation.m` file in MATLAB.
3.  Click the **"Run"** button. The plots and animation will be generated automatically.
