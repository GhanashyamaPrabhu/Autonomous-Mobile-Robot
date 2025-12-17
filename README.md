# Autonomous-Mobile-Robot
Autonomous Mobile Robot (AMR) project featuring Kinematics , Dynamics, mapping, path planning, and control for autonomous navigation

**Autonomous Mobile Robot (Ackermann Steering)**
**Overview**
This project focuses on the modeling, control, and motion planning of an Autonomous Mobile Robot (AMR) using Ackermann steering geometry. Ackermann steering is widely used in the automotive industry and AMR platforms due to its directional stability, simplicity, and improved control fidelity, particularly during high-speed maneuvers.

**Why Ackermann Steering?**

Ackermann steering geometry was selected for the following reasons:
Widely adopted in automotive and autonomous vehicle applications
Excellent lateral stability during high-speed turns
Simple, robust, and low-cost mechanical design
Reduced wheel slip, leading to better odometry and control accuracy

**Project Scope**

**1. System Modeling**
Kinematic modeling incorporating Ackermann steering constraints
Dynamic modeling of vehicle motion
Mathematical formulation of position, velocity, and heading evolution
Physical working principles and implementation considerations

**2. Control Methodology**
The project implements both robust and adaptive control strategies to ensure accurate trajectory tracking and stability under uncertainties.

Robust Control Method – Linear Quadratic Regulator (LQR):
Designed an LQR controller for optimal state feedback control
Minimized a quadratic cost function balancing tracking error and control effort
Ensured robustness against modeling inaccuracies and disturbances
Achieved stable steering and velocity control for trajectory tracking

Adaptive Control Method – Model Reference Adaptive Controller (MRAC):
Implemented a Model Reference Adaptive Control (MRAC) framework
Adaptively adjusted control parameters to match the behavior of a reference model
Handled system parameter variations and external disturbances
Improved tracking performance under uncertain or changing dynamics

Stability Analysis and Validation:
Stability analysis performed for both LQR and MRAC controllers
Controllers validated through simulation-based testing
Performance evaluated using trajectory tracking accuracy and robustness metrics

**3. Motion Planning**

Path and motion planning algorithms tailored for non-holonomic Ackermann vehicles
Obstacle avoidance strategies respecting steering and curvature constraints
Emphasis on smooth, feasible, and dynamically consistent trajectories

**Key Outcomes**

Accurate Ackermann vehicle modeling
Robust and adaptive control with stable trajectory tracking
Constraint-aware motion planning and obstacle avoidance

**Applications**

Autonomous ground vehicles
Self-driving vehicle research
Robotics and control system simulations

**Requirements**

Matlab 
