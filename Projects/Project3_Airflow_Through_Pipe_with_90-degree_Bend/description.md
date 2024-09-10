# Airflow Through Pipe with 90-degree Bend

## Objective
The objective of this project was to model air flow through a pipe with a 90-degree bend. The aim was to understand the connection between wall treatment and mesh for different turbulence models.

## Approach
- **Software**: SOLIDWORKS, STAR-CCM+
- **Mesh**: Structured grid with refinement near wall areas
- **Model**: Turbulence model - Standard k-epsilon model with high-y+, EB k-epsilon model with low-y+, Realizable k-epsilon model with all-y+
- **Boundary conditions**: Inlet - uniform velocity = 10 m/s, Outlet - flow outlet, internal walls - no-slip condition
- **Initial conditions**: velocity = 0 m/s 

## Results
### 1. Velocity vector plots over the midplane of the square duct:

Velocity plot for standard k-epsilon model with high y+:[Velocity plot for standard k-epsilon model with high y+](images/high_y+_k-e_standard_Velocity_Midplane.png)
Velocity plot for Realizable k-epsilon model with all-y+:[Velocity plot for Realizable k-epsilon model with all-y+](images/realizable_all_y+_k-e_Velocity_Midplane.png)
Velocity plot for EB k-epsilon model with low-y+:[Velocity plot for EB k-epsilon model with low-y+](images/low_y+_k-e_EB_Velocity_Midplane.png)

All three models predicted flow acceleration in and after the bend. However, the region of the higher velocity field is different in each case which is highlighted by the color bars representing the velocity range for these models. The velocity through the bend predicted by the standard k-epsilon model is lower compared to other models.

### 2. Change in wall shear stress (WSS) when flow passes through the right-angle bend:

WSS plot for different turbulence models:[WSS plot for different turbulence models](images/WSS.png)

The Wall Shear Stress (WSS) plot for these cases shows that the standard k-epsilon model failed to predict flow separation. In contrast, the shift in WSS values observed in other models indicates successful prediction of flow separation as the air passes through the bend.
