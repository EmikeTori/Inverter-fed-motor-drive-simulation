# Inverter-fed-motor-drive-simulation
Simulink simulation of an inverter-fed motor drive with closed-loop PI speed control

Status: In progress (started 30 October 2026)

#Overview
This project is a MATLAB/Simulink simulation of a traction-style electric drive. A DC source feeds a three-phase inverter with PWM switching, which drives a motor whose speed is regulated by a PI controller. The aim is to understand how inverter switching, motor dynamics and feedback control interact, and to test how well the drive tracks a speed reference and rejects a sudden load-torque change. It is a self-directed, simulation-only study, and the control method and model limitations are stated in the sections below.

#Objectives
- Develop a Simulink model of a traction-style inverter-fed motor drive: a DC source, a three-phase inverter with PWM switching, and a motor.
- Design a closed-loop PI speed controller for the motor.
- Evaluate speed-reference tracking (rise time, overshoot, settling time, steady-state error).
- Evaluate load-disturbance rejection (speed dip and recovery time after a load-torque step), recording phase currents in both tests.
- Document the results, assumptions and limitations, with all figures reproducible from the repository.

#System Architecture
[To be added after the system architecture has been established.]

#Tools and Technologies
- MATLAB (Version)
- Simulink

#Methodology
1. Review the relevant principles of electric vehicle traction drives.
2. Develop and verify the inverter and motor models.
3. Implement the PWM switching scheme.
4. Design and integrate the speed controller.
5. Conduct simulation experiments under different operating conditions.
6. Analyse and document the results.

#Project Structure
Inverter-fed-motor-drive-simulation
Model  #Simulink models
Scripts  #MATLAB Scripts
Results  #Simulation results and plots
Docs  #Technical documentation

#System Architecture
{To be added after the system architecture has been established.}

#Scope and limitations
- Simulation only; no hardware.
- Control method: [].
- {Add limitations as they appear, e.g. ideal sensors, simplified losses.}

#Acknowledgements and references
{List any MathWorks examples, books or papers you use, and what you adapted from them.}


├── presentation/       # Project presentation
└── README.m
