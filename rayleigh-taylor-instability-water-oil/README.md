# Case Description

Objective: Simulation of a classical hydrodynamic instability caused by a denser fluid placed above a lighter fluid, leading to interfacial instability and turbulent mixing.

Tools: OpenFOAM (interFoam solver), ParaView for visualization.

Tasks Completed:
- Setup of a two-phase water–oil system with oil density set to 800 kg/m³ and viscosity equal to water.
- Definition of an initial perturbation at the fluid interface (radius: 1 cm) to trigger the instability.
- Configuration of transport properties with zero surface tension.
- Mesh generation and gravity-driven flow setup.
- Transient simulation with end time of 4 s and specified write interval.
- Post-processing and visualization of the evolving flow field.
- Extraction and presentation of representative snapshots of the instability development.
