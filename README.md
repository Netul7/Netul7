# Hi, I'm Ernesto 👋  
### Mechanical & Electrical Engineer | M.Sc. in Electrical Engineering (Control)

M.Sc. in Electrical Engineering (Control) from UNAM, with a thesis on online load
parameter estimation for robot manipulators. I implemented the algorithm in C++ and
validated it experimentally on the Geomagic Touch (3-DOF) and Franka Research 3
(7-DOF) during a research stay in France.

I'm interested in applying model-based and advanced control techniques to real
robotic systems.

---

## 🔬 About Me

- 🎯 Target roles: **Control Systems Engineer**, **Robotics Engineer**, **Advanced Control Engineer**
- 🧠 Focus areas: nonlinear control, adaptive control, estimation, robot dynamics
- 🤖 Platforms/tools: **Franka Research 3 (FR3)**, **Geomagic Touch**, **Webots**, **ROS 2** (basic)
- 📫 Contact: **ernesto.aa4@proton.me**

---

## 🛠️ Technical Skills

- **Programming:** Python, C++, MATLAB
- **Modeling & Simulation:** Simulink, dynamic system modeling
- **Control:**  
  - Linear and nonlinear systems analysis  
  - Passivity-based control  
  - Generalized predictive control  
  - Adaptive control  
  - Control of robot manipulators
- **Estimation & Identification:**  
  - Online parameter estimation  
  - Parameter identification for robot payloads  
  - Kalman filtering
- **Robotics:** ROS 2 (basic), Webots

---

## 📌 Featured Projects

### 1) Online Payload Parameter Estimation for Robotic Manipulators
**Master's thesis project (UNAM)** · MDREM · C++ · ROS 2 · MATLAB/Simulink

Implementation and experimental validation of an online parameter estimation
algorithm based on **Modified Dynamic Regressor Extension and Mixing (MDREM)**
for identifying payload parameters in robot manipulators. The method was tested
on two platforms: one developed in Mexico and one during a research stay in France.

#### 🇲🇽 Part 1: Geomagic Touch (3-DOF) · Mexico
- Estimated the full set of robot and payload parameters (10 parameters) online
- Built a MATLAB/Simulink simulation in which all parameters converged in under 0.5 s
- Ran experiments on the real robot in C++ (Visual Studio) and validated the
  gravity-related parameters through a gravity compensation test

#### 🇫🇷 Part 2: Franka Research 3 (7-DOF) · France
- Implemented the estimator in C++ with ROS 2 on Ubuntu
- Estimated the payload's inertial parameters (mass, center of mass, inertia tensor)
  using a Newton–Euler formulation
- Obtained estimates close to the true values with a 1.4 s trajectory, despite the
  uncertainty in the robot's link parameters

> 🔗 [View repository](https://github.com/Netul7/payload-online-estimation-manipulators-)
> · [Geomagic Touch](https://github.com/Netul7/payload-online-estimation-manipulators-/tree/main/1_geomagic_touch)
> · [Franka Research 3](https://github.com/Netul7/payload-online-estimation-manipulators-/tree/main/2_franka_research_3)

---

## 🤝 Open to

- Robotics/control engineering opportunities
- Research collaborations in advanced control and estimation
- Projects involving manipulation, dynamic modeling, and adaptive control
