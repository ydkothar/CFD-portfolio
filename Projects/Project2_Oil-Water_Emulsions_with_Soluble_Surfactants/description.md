# Oil-Water Emulsions with Soluble Surfactants

## Objective
The goal of this project was to develop a diffuse interface model for a system of immiscible liquids (oil and water) and soluble surfactants. The objective was to accurately predict the reduction in surface tension caused by surfactants, a key factor in the enhanced oil recovery (EOR) processes.

## Approach
- **CFD code development**: FORTRAN
- **Model**: Phase field model (i.e., Diffuse interface model)
- **Numerical methods**: Lattice Boltzmann Method and Finite Difference Method
- **Post-processing**: Python, MATLAB, ParaView 

## Results
## 1. Adsorption dynamics of surfactants on the interface of oil drop dispersed in water for Langmuir isotherm:

Surfactant adsorption on oil-water interface:[Surfactant adsorption on oil-water interface](images/Oil-Water_drop_surfactant_adsorption.png)

Here, $\phi$ is the relative density difference between oil and water. It means that $\phi=-1$, $\phi=0$, and $\phi=1$ represent the water phase, oil-water interface, and oil phase, respectively. $\psi$ is the volume fraction of the surfactant. $\psi_{b}$ is a bulk surfactant volume fraction.

The results show that the surfactant distribution over the drop interface is more uniform for higher bulk surfactant volume fraction (Figure (b) vs Figure (d)).

## 2. Surface tension reduction in the presence of different surfactants for Langmuir and Frumkin isotherms:

Surfactant tension reduction for different isotherms:[Surfactant tension reduction for different isotherms](images/Surface_tension_reduction.png)

Here, $\psi_{0}$ is the surfactant volume fraction at the interface of oil drop dispersed in water. Higher values of $\lambda_{2}$ describe the type of surfactant with dense packing of surfactant molecules; whereas, lower values of $\lambda_{2}$ represent the loosely packed arrangement of surfactant molecules.  $\sigma_0$ is the surface tension of the pure system (i.e., oil-water mixture). The reduction of the surface tension compared to the surface tension of the pure system is expressed as, $\dfrac{\Delta\sigma}{\sigma_{0}}=\dfrac{\sigma(\psi_{0})-\sigma_{0}}{\sigma_{0}}$. $\alpha$ is a fitting coefficient for the analytical equation of surface tension.

In figures, The solid curves and markers represent the analytical and numerical solutions, respectively. As the parameter $\lambda_{2}$, which represents the compactness of surfactant molecules, increases, the surface tension decreases significantly for the same surfactant volume fraction. In addition, these results follow the experimental observations of the binary liquids-surfactant system for Langmuir isotherm, where the typical range of surface tension reduction is 30−60 % of $\sigma_{0}$.

Overall, the proposed diffuse interface model is capable of representing physical phenomena such as surfactant adsorption dynamics and surface tension reduction for different types of surfactants. 
