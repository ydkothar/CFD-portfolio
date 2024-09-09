# Oil-Water Emulsions with Soluble Surfactants

## Objective
The goal of this project was to develop a diffuse interface model for a system of immiscible liquids (oil and water) and soluble surfactants. The objective was to accurately predict the reduction in surface tension caused by surfactants, a key factor in enhancing oil recovery (EOR) processes.

## Approach
- **CFD code development**: FORTRAN
- **Model**: Phase field model (i.e., Diffuse interface model)
- **Numerical methods**: Lattice Boltzmann Method and Finite Difference Method
- **Post-processing**: Python, MATLAB, ParaView 

## Results
- **Adsorption dynamics of surfactants on the interface of oil-water drop for Langmuir isotherm**:



Here, $\phi$ is the relative density difference between oil and water. It means that $\phi=-1$, $\phi=0$, and $\phi=1$ represent the water phase, oil-water interface, and oil phase, respectively. $\psi$ is the volume fraction of the surfactant. $\psi_{b}$ is a bulk surfactant volume fraction.

The results show that the surfactant distribution over the interface is more uniform for higher bulk surfactant volume fraction (Figure (b) vs Figure (d)).

- **Surface tension reduction in the presence of different surfactants for Langmuir and Frumkin isotherms**:



Here, $\psi_{0}$ is the surfactant volume fraction at the oil-water drop interface. Higher values of $\lambda_{2}$ describe the type of surfactant with dense packing of surfactant molecules; whereas, lower values of $\lambda_{2}$ represent the loosely packed arrangement of surfactant molecules.  $\sigma_0$ is the surface tension of the pure system (i.e., oil-water mixture). The reduction of the surface tension compared to the surface tension of the pure system, $frac{\Delta\sigma}{\sigma_{0}}=\frac{\sigma(\psi_{0})-\sigma_{0}}{\sigma_{0}}$.
