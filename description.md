# Flow Over Cylinder Simulation

## Objective
The goal of this project was to simulate oil flow within microwells initially filled with water, focusing on comparing the performance of the implicit and explicit formulations of the Volume of Fluid (VOF) model in ANSYS Fluent. The objective was to analyze the sharpness of the oil-water interface produced by each method.

## Approach
- **Software**: Ansys Workbench
- **Mesh**: Quadrilateral elements
- **Model**: Multiphase model - Volume of Fluid (Implicit & Explicit formulations)
- **Boundary Conditions**: Oil mass flow rate = 0.004 kg/s, outlet pressure = 0 Pa, and no-slip condition on the internal walls
- **Initial Conditions**: Phase 1 (i.e., water) volume fraction = 1 and Phase 2 (i.e., oil) volume fraction = 0 

## Results
![Oil Volume Fraction](animations/Implicit_VOF.wmv)

The velocity contours and pressure distribution showed a clear vortex shedding pattern with Strouhal number calculated to be 0.21, matching well with theoretical predictions.
