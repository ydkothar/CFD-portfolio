# Flow Over Right-Angle Bend

## Objective
The objective of this project was to model air flow through a square duct with a right-angle bend. The aim was to understand the connection between wall treatment and mesh for different turbulence models.

## Approach
- **Software**: SOLIDWORKS, STAR-CCM+
- **Mesh**: Structured grid with refinement near wall areas
- **Model**: Turbulence model - Standard K-Epsilon model with high-y+, EB K-Epsilon model with low-y+, Realizable K-Epsilon model with all-y+
- **Boundary conditions**: Inlet - uniform velocity = 10 m/s, Outlet - flow outlet, wall - no slip condition
- **Initial conditions**: velocity = 0 m/s 

## Results

Here, the oil and water phases are represented by red and blue colors respectively. From the observation, it is clear that the explicit formulation of the VOF model captures the sharp interface between the oil and water phases with greater accuracy and minimal diffusion, compared to the implicit formulation of the VOF model.
