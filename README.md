# Hi, I'm Pablo Nieto Pareja 👋

### Robotics Engineer | Industrial Robotics · Autonomous Systems · Robot Simulation · PLC · Python

I am a Robotics and Industrial Engineer focused on **industrial robotics, autonomous systems, robot simulation and intelligent automation**.

My work combines robotics, software and industrial automation to develop and evaluate real-world engineering solutions, from **ABB RobotStudio and PLC-integrated automation cells** to **autonomous mobile robot navigation, deep reinforcement learning and intelligent robot scheduling**.

---

## 🤖 Selected Projects

### ABB RobotStudio + CODESYS Pick-and-Place Cell

**ABB RobotStudio · RAPID · CODESYS · Ladder Diagram · OPC UA · Industrial Automation**

Industrial robotic pick-and-place cell integrating an **ABB robot simulation with CODESYS PLC control** through an OPC UA-based virtual automation architecture.

The project includes:

- PLC-controlled automatic and manual robot operation
- Deterministic **PLC ↔ robot job handshaking**
- ABB RAPID job dispatch and motion execution
- Dynamic pick-position selection from conveyor sensors
- Magnetic end-effector control
- Reusable CODESYS Ladder Diagram function blocks
- PLCopenXML source export for long-term inspection and portability
- Custom RobotStudio simulation assets and I/O engineering

🔗 **[Explore the project](https://github.com/pablonietopareja/abb-robotstudio-codesys-pick-and-place)**

---

### Autonomous Mobile Robot Navigation

**A\* Path Planning · Particle Filter Localization · Simulated LiDAR · PyBullet · Python**

Autonomous mobile robot simulation combining global path planning, probabilistic localization, waypoint tracking and dynamic obstacle handling.

The robot:

- Plans multi-goal missions using **A\***
- Estimates its pose using a **Particle Filter**
- Combines odometry with simulated **LiDAR**
- Navigates using the estimated pose rather than ground truth
- Detects dynamic workers and stops when safety distances are violated
- Generates navigation logs and quantitative performance metrics

🔗 **[Explore the project](https://github.com/pablonietopareja/amr-navigation-pybullet)**

---

### Deep Reinforcement Learning — Super Mario Bros PPO

**Proximal Policy Optimization · Stable-Baselines3 · PyTorch · Computer Vision · Python**

Visual deep reinforcement learning agent trained with **Proximal Policy Optimization (PPO)** to navigate Super Mario Bros World 1-1.

The project implements:

- Visual preprocessing from RGB to **84 × 84 grayscale observations**
- Temporal state representation using **4-frame stacking**
- Frame skipping for more efficient interaction with the environment
- Custom reward shaping based on progress, enemies, coins and level completion
- Parallel training using **16 vectorized environments**
- Observation and reward normalization with **VecNormalize**
- Periodic deterministic evaluation and checkpoint selection
- Training over **1,000,000 global timesteps**
- Best deterministic evaluation reward of **4,876.60 at 900,000 timesteps**

The repository includes the complete experiment notebook, trained PPO checkpoint, normalization state, quantitative results and gameplay recording.

🔗 **[Explore the project](https://github.com/pablonietopareja/super-mario-bros-ppo)**

---

## 🔬 Research

### Reactive Path Planning for Human-Robot Collaboration

**Monte Carlo Tree Search · Human-Robot Collaboration · ABB RobotStudio · Python**

Master's thesis investigating intelligent online robot scheduling using **Monte Carlo Tree Search (MCTS)** in a simulated human-robot collaborative manufacturing environment.

The system integrates **ABB RobotStudio** with a Python-based decision-making layer and evaluates MCTS against conventional FIFO scheduling.

🔗 **[View the publication](https://urn.kb.se/resolve?urn=urn:nbn:se:his:diva-26785)**

---

### Large-Scale Robotic 3D Printing

**Industrial Robotics · Robotic Additive Manufacturing · ABB RobotStudio · Experimental Validation**

Bachelor's thesis developed in collaboration with **ABB Robotics and RISE**, focused on standardized testing and process optimization for large-scale robotic additive manufacturing.

🔗 **[View the publication](https://urn.kb.se/resolve?urn=urn:nbn:se:his:diva-24035)**

---

## 🧰 Technical Focus

**Robotics**
- Industrial Robotics
- Autonomous Mobile Robots
- Robot Simulation
- Path Planning
- Localization
- Human-Robot Collaboration

**Automation**
- PLC Programming
- CODESYS
- Industrial Automation
- Robot / PLC Integration
- OPC UA
- Virtual Commissioning

**Artificial Intelligence**
- Reinforcement Learning
- Deep Reinforcement Learning
- Monte Carlo Tree Search
- Autonomous Decision-Making
- Computer Vision

**Software**
- Python
- C++
- ROS
- PyBullet
- MATLAB
- PyTorch

**Robotics Tools**
- ABB RobotStudio
- RAPID
- Digital Twin & Simulation

---

## 🎓 Background

- **M.Sc. — Intelligent Automation / Virtual Product Realization**  
  University of Skövde, Sweden

- **M.Eng. — Industry & Robotics**  
  ESILV, France

- **B.Sc. — Industrial Engineering**  
  University of Skövde, Sweden

- **Bachelor's Degree — Robotics Engineering**  
  University of Alicante, Spain

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pablo_Nieto_Pareja-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/pablo-nieto-pareja/)
[![GitHub](https://img.shields.io/badge/GitHub-pablonietopareja-181717?logo=github&logoColor=white)](https://github.com/pablonietopareja)

📧 **pablo.nietopareja02@gmail.com**

---

> Building intelligent robotic systems from simulation and algorithms to industrial automation.
