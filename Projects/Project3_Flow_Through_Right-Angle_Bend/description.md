# Flow Through Right-Angle Bend

## Objective
The objective of this project was to model air flow through a square duct with a right-angle bend. The aim was to understand the connection between wall treatment and mesh for different turbulence models.

## Approach
- **Software**: SOLIDWORKS, STAR-CCM+
- **Mesh**: Structured grid with refinement near wall areas
- **Model**: Turbulence model - Standard k-epsilon model with high-y+, EB k-epsilon model with low-y+, Realizable k-epsilon model with all-y+
- **Boundary conditions**: Inlet - uniform velocity = 10 m/s, Outlet - flow outlet, wall - no slip condition
- **Initial conditions**: velocity = 0 m/s 

## Results
### 1. Velocity vector plots over the midplane of the square duct:

All three models predicted flow acceleration in and after the bend. However, the region of the higher velocity field is different in each case which is highlighted by the color bars representing the velocity range for these models. The velocity through the bend predicted by the standard k-epsilon model is lower compared to other models.

### 2. Change in wall shear stress (WSS) when flow passes through the right-angle bend:

The Wall Shear Stress (WSS) plot for these cases shows that the standard k-epsilon model failed to predict flow separation. In contrast, the shift in WSS values observed in other models indicates successful prediction of flow separation as the air passes through the bend.
