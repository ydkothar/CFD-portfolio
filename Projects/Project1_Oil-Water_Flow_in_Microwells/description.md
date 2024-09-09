# Oil-Water Flow in Microwells

## Objective
The objective of this project was to simulate the flow of oil in microwells initially filled with water, with the goal of comparing the performance of implicit and explicit Volume of Fluid (VOF) models in ANSYS Fluent. The focus was on analyzing the sharpness of the oil-water interface and the differences in modeling accuracy between the two approaches.

## Approach
- **Software**: Ansys Workbench - Ansys SpaceClaim and Ansys Fluent
- **Mesh**: Quadrilateral elements
- **Model**: Multiphase model - Volume of Fluid (Implicit & Explicit formulations)
- **Boundary conditions**: Oil mass flow rate = 0.004 kg/s, outlet pressure = 0 Pa, and no-slip condition on the internal walls
- **Initial conditions**: Phase 1 (i.e., water) volume fraction = 1 and Phase 2 (i.e., oil) volume fraction = 0 

## Results
![Evolution of oil volume fraction for the case of implicit VOF model](animations/Implicit_VOF.mp4)
![Evolution of oil volume fraction for the case of explicit VOF model](animations/Implicit_VOF.mp4)

Here, the oil and water phases are represented by red and blue colors respectively. From the observation, it is clear that the explicit formulation of the VOF model captures the sharp interface between the oil and water phases with greater accuracy and minimal diffusion, compared to the implicit formulation of the VOF model.
