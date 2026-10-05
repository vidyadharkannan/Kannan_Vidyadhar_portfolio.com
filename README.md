# Kannan Vidyadhar Portfolio

## About me

<p align="justify">
I am a Robotics Engineer with a Master's degree in Advanced Robotics from École Centrale de Nantes, France.
</p>
<p align="justify">
My experience spans robot control, mechatronic system development, biomechanical modelling, optimisation, and physical human–robot interaction. I have worked with collaborative robotic manipulators, haptic teleoperation, mobile robot navigation, and industrial automation, with experience taking robotic systems from mathematical modelling and simulation to implementation and experimental testing on real hardware.
</p>

<p align="justify">
My main interests are robot control, physical human–robot interaction, medical robotics, rehabilitation robotics, and mechatronics system Developement.
</p>

## My Vision 

<p align="justify">
I am fascinated by how robots can interact with humans in unstructured and unpredictable environments. Through my projects and research experience, I have developed a particular interest in rehabilitation and surgical robotics, especially in how robots can assist people and support complex tasks in healthcare.
I want to work on challenging problems in medical robotics where I can apply my experience in robotics, control, and mechatronics while continuing to learn. In the long term, I want to contribute to robotic systems that can make a practical difference in rehabilitation and healthcare.
</p>

## Experience
### Master's Research Intern — LS2N
**Laboratoire des Sciences du Numérique de Nantes | Nantes, France**  
*February 2026 – August 2026*
#### Thesis Title: Collaborative Robot-Based Test Bench for Knee Motion Simulation and ICR Estimation
**Project Description:**
<p align="justify">
The project aimed to develop a collaborative robot (cobot)-based knee test bench designed to estimate and reproduce the Instantaneous Centre of Rotation (ICR) of the human knee during flexion and extension. Additionally, it explored different control strategies to achieve the desired knee motion while ensuring compliant physical interaction.
</p>

**Biomechanical Modelling and ICR Reconstruction:**

- Used experimentally measured tibiofemoral kinematic data, including flexion–extension (FE) angle and anterior–posterior (AP) and superior–inferior (SI) translations.

- Reconstructed the motion of tibial reference points relative to the femur and applied the Reuleaux geometric method to estimate the Instantaneous Centre of Rotation (ICR) between consecutive configurations.

- Generated a reference ICR trajectory representing the migration of the knee centre of rotation throughout flexion–extension, which was subsequently used as the target for mechanism optimisation.

**Mechanism Design & Optimisation:**

- Modelled a closed-chain cross four-bar mechanism designed to reproduce the polycentric motion of the human knee and derived its kinematic and loop-closure equations.

- Determined the mechanism-generated ICR throughout flexion–extension and compared its trajectory with the reconstructed reference knee ICR from the tibiofemoral kinematics data.

- Implemented a Genetic Algorithm in MATLAB to optimise the geometric parameters of the mechanism by minimising the difference between the mechanism-generated and reference ICR trajectories.

- Designed and manufactured the optimised mechanism for integration with the robotic test bench.

**Robot Integration & Control:**

- Integrated the optimised cross four-bar mechanism with a Franka Research 3 (FR3) collaborative robot and implemented the control framework in ROS 2.

- Developed a Jacobian-based joint-velocity control framework, mapping the desired Cartesian motion to FR3 joint velocities using the pseudoinverse of the robot Jacobian.

- Implemented admittance control using the measured interaction wrench to provide compliant motion during physical robot–mechanism interaction.

- Developed and investigated three control strategies: Fixed ICR, mechanism-based Moving ICR, and Iterative Learning Control (ILC) for cycle-to-cycle adaptation of the desired ICR trajectory.

**Technologies:**  
ROS 2 • C++ • Python • MATLAB • SolidWorks • Franka Research 3 • Genetic Algorithm • Admittance Control • Iterative Learning Control (ILC)

<br>

[**Link for full project**] - ()


### Maintenance Engineer Trainee — Ali Shaihani Group of Industries
**Oman | September 2022 – June 2024**

**Description:**  
<p align="justify">
Performed maintenance, troubleshooting, and automation of industrial production and packaging machinery, gaining hands-on experience with electromechanical systems in an industrial environment.
</p>

**Maintenance & Troubleshooting:**
- Performed preventive and corrective maintenance on industrial machinery and assisted in diagnosing mechanical and electrical faults.


- Worked with production equipment involving motors, sensors, actuators, and industrial control systems.


**Industrial Automation:**
- Developed PLC control logic for an automated potato peeling machine as part of an industrial automation project.
- Supported the integration and testing of the automated system during implementation.

**Technologies:**  
PLC • Industrial Automation • Sensors & Actuators • Electrical Troubleshooting • Mechanical Maintenance


### Robotics Engineer — Consciente Technologies
**Hyderabad, India | November 2021 – August 2022**

**Description:**  
Worked on modelling, simulation, and motion planning for robotic manipulators, focusing on robot kinematics, dynamics, and ROS-based simulation.

**Robot Modelling & Analysis:**
- Implemented forward and inverse kinematics and studied the dynamics of a 6-DOF robotic manipulator.
- Performed workspace, velocity ellipsoid, and singularity analysis to evaluate manipulator behaviour.

**Motion Planning & Simulation:**
- Used ROS and MoveIt for manipulator motion planning, simulation, and testing.
- Evaluated robot configurations and trajectories in simulated environments.

**Technologies:**  
ROS • MoveIt • C++ • Python • Robot Kinematics • Robot Dynamics • Motion Planning








  
## Projects


### Robotised Tele-Echography System
**École Centrale de Nantes**

Bilateral teleoperation system using a Haption Virtuose 6D haptic device and a Franka Panda robotic manipulator.

**Key Work:**
- Developed Cartesian impedance control for the Franka Panda in C++.
- Used the Kinematics and Dynamics Library (KDL) for forward kinematics and Jacobian computation.
- Implemented Jacobian-based Cartesian-to-joint torque mapping for robot control.
- Integrated the Haption Virtuose 6D for master-side teleoperation.
- Implemented force feedback and a virtual spring boundary for haptic interaction.
- Analysed system behaviour using ROS bags and RQT.

**Technologies:**  
ROS 2 • C++ • Python • Franka Panda • Haption Virtuose 6D • Orocos KDL • Cartesian Impedance Control • Gazebo • RViz

[**View Full Project**](PROJECT_LINK)



### ROS 2 Predictive Navigation
**SOFAR — Software Architecture Lab, École Centrale de Nantes | May 2025**

**Description:**  
Developed a predictive navigation controller in ROS 2 for Turtlesim and TurtleBot, where candidate robot motions were evaluated to select safe velocity commands for goal-directed navigation around static obstacles.

**Key Work:**
- Developed a Python-based controller that predicted candidate robot trajectories for different angular velocities and selected a suitable path for obstacle avoidance.
- Used TurtleBot odometry and quaternion orientation data for robot pose and heading estimation.
- Implemented adaptive navigation behaviours including heading correction, straight-line motion when aligned with the target, and stopping at the goal.
- Implemented angle normalisation and Euler–quaternion conversions for stable heading tracking.

**Technologies:**  
ROS 2 • Python • TurtleBot • Turtlesim • Odometry • Predictive Navigation • Obstacle Avoidance


## Technical Skills

**Programming:**  
C++ • Python • MATLAB

**Robotics & Software:**  
ROS 2 • ROS • MoveIt • Orocos KDL • Gazebo • RViz • Git • Linux • CMake

**Robot Modelling & Control:**  
Forward & Inverse Kinematics • Jacobian Methods • Robot Dynamics • Cartesian Impedance Control • Admittance Control • Iterative Learning Control • Motion Planning

**Mobile Robotics & Navigation:**  
Mobile Robot Navigation • Odometry • Trajectory Prediction • Obstacle Avoidance • Heading Control • Quaternion & Euler Representations

**Mechanical Design & Engineering:**  
SolidWorks • CATIA • Fusion 360 • Mechanism Design • CAD • Additive Manufacturing

**Optimisation & Numerical Methods:**  
Genetic Algorithms • MATLAB Optimisation • Numerical Modelling

**Industrial Automation:**  
PLC • Sensors & Actuators • Industrial Automation • Electromechanical Troubleshooting




## Education
### Master’s in Advanced Robotics (CORO-IMARO)
**École Centrale de Nantes | Nantes, France**  
*2024 – 2026*

CORO-IMARO programme with a focus on robotics, control, modelling, and autonomous systems.

**Master's Thesis:**  
*Collaborative Robot-Based Test Bench for Knee Motion Simulation and Instantaneous Centre of Rotation Estimation*

### Bachelor of Technology — Mechatronics Engineering
**SRM Institute of Science and Technology | Chennai, India**  
*2017 – 2021*

## Research & Publications

### Cross Four-Bar Mechanism for Human Knee ICR Reproduction
**Research manuscript in preparation**

Ongoing research based on my Master's thesis at LS2N, focusing on the geometric optimisation of a cross four-bar mechanism for reproducing the physiological Instantaneous Centre of Rotation (ICR) trajectory of the human knee.

**Research Areas:**  
Biomechanics • Medical Robotics • Mechanism Optimisation • Human Knee Kinematics • Robot-Assisted Experimentation

## Contact

I am currently interested in opportunities in robotics, robot control, mechatronics, medical robotics, and research.

**Email:** kannanvidyadhar98@gmail.com 
**LinkedIn:** [Kannan Vidyadhar](www.linkedin.com/in/kannanvidyadhar)  
**GitHub:** [vidyadharkannan](https://github.com/vidyadharkannan)
