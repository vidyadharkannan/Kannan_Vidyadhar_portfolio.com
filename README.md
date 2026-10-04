# Kannan Vidyadhar Portfolio

## About me


## My Vision 


## Experience
### Master's Research Intern — LS2N
**Laboratoire des Sciences du Numérique de Nantes | Nantes, France**  
*February 2026 – August 2026*
#### Collaborative Robot-Based Test Bench for Knee Motion Simulation and ICR Estimation
**Project Description**
The project aimed to develop a collaborative robot (cobot)-based knee test bench designed to detect and replicate the Instantaneous Centre of Rotation (ICR) of the human knee during flexion and extension. Additionally, it explored different control strategies to achieve the desired knee motion while ensuring compliant physical interaction.
**Biomechanical Modelling and ICR Reconstruction**
- Used experimentally measured tibiofemoral kinematic data, including flexion–extension(FE) angle and anterior–posterior(AP) and superior–inferior(SI) translations.
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
`ROS 2` `C++` `Python` `MATLAB` `SolidWorks` `Franka Research 3` `Genetic Algorithm` `Admittance Control` `ILC`

[**View Full Project →**](...)





  

## Technical Skills

## Projects

## Education
- École Centrale de Nantes
- SRM Institute of Science and Technology

## Research & Publications

## Contact
