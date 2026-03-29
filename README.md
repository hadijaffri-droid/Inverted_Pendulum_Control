# Inverted_Pendulum_Control

This repository presents the modelling and control of an inverted pendulum system using MATLAB and Simulink.

The mathematical model was derived using Newtonian mechanics and expressed in state-space form. The state equations were implemented in MATLAB, and the resulting system matrices were imported into a Simulink state-space block for closed-loop simulation and analysis.

An LQR controller augmented with integral action (LQI) was designed to stabilize the pendulum in the upright position while controlling the cart displacement with improved tracking performance and reduced steady-state error.

In addition to the control design, the code also includes an animation of the inverted pendulum motion generated from the logged state variables obtained during simulation.

## Repository Contents
- MATLAB scripts for system modelling and controller design
- Simulink model for closed-loop simulation
- State-space representation of the inverted pendulum dynamics
- Animation script based on logged simulation state variables

## Control Approach
The control objective is to balance the pendulum in the upright position while ensuring accurate cart position tracking. For this purpose, a Linear Quadratic Regulator (LQR) with integral action was used to improve reference tracking and reduce steady-state error.

## Results
The designed LQI controller was able to stabilize the inverted pendulum around the upright equilibrium and regulate the cart position effectively in simulation. The closed-loop response showed improved tracking performance with minimal steady-state error due to the inclusion of integral action.

The logged state variables were also used to generate an animation of the system motion, providing a visual representation of the pendulum stabilization and cart movement over time.
<img width="959" height="484" alt="image" src="https://github.com/user-attachments/assets/4d0b92ec-a9d6-4cd1-a978-97b8c8e4246d" />


## Objective
The main objectives of this project are to:
- derive the mathematical model of the inverted pendulum system,
- formulate the system in state-space form,
- design an LQI controller for stabilization and tracking,
- simulate the closed-loop response in Simulink,
- and visualize the system behaviour through animation.
