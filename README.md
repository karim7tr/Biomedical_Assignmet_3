# Biomedical_Assignment_3

This repository contains MATLAB scripts and Simulink models developed by Our for the Biomedical Robotics course.

## Contents

- `Reaching.slx`: Simulink model for the reaching task of the Phantom Robot.
- `ForceField.slx`: Simulink model for the force field control of the Phantom Robot.
- `README.md`: This file providing an overview of the repository.
- `LICENSE`: License information for the code in this repository.

## Instructions

### Reaching Task

The `Reaching.slx` file contains a Simulink model for the reaching task of the Phantom Robot. The model consists of a stateflow chart named "chart1" which controls the robot's behavior. The robot aims to reach randomly generated targets within a specified radius. Targets change color and position based on certain conditions. The model also integrates with VR Slink for visualization.

### Force Field Control

The `ForceField.slx` file contains a Simulink model for implementing force field control on the Phantom Robot. The model incorporates initial and end gains, Omni Jacobian, and PhanTorque_3Dof to control the robot's movements. Experimental adjustments have been made to optimize the performance of the robot.

## Usage

To use these Simulink models, open them in MATLAB and simulate as needed. Make sure to have the necessary toolboxes installed for VR visualization if applicable.

---

Authors:
- Karim Triki
- Ines Haoula
- Romaissa Benkerda



