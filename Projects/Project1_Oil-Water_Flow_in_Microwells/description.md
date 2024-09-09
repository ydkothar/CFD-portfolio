# Oil-Water Flow in Microwells

## Objective
The objective of this project was to simulate the flow of oil in microwells initially filled with water, with the goal of comparing the performance of implicit and explicit Volume of Fluid (VOF) methods in ANSYS Fluent. The focus was on analyzing the sharpness of the oil-water interface and the differences in modeling accuracy between the two approaches.

## Approach
- **Software**: Ansys Workbench
- **Mesh**: Quadrilateral elements
- **Model**: Multiphase model - Volume of Fluid (Implicit & Explicit formulations)
- **Boundary Conditions**: Oil mass flow rate = 0.004 kg/s, outlet pressure = 0 Pa, and no-slip condition on the internal walls
- **Initial Conditions**: Phase 1 (i.e., water) volume fraction = 1 and Phase 2 (i.e., oil) volume fraction = 0 

## Results
![Oil Volume Fraction](animations/Implicit_VOF.wmv/https://github.com/user-attachments/assets/5151f6d8-0ec0-49fc-95b1-967a28713929)

The velocity contours and pressure distribution showed a clear vortex shedding pattern with Strouhal number calculated to be 0.21, matching well with theoretical predictions.
