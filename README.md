
# Stable Fluid Simulation

<div align="center">
  <img src="./Content/image.png" width="600" height="400" />
</div>


Solution to the Incompressible Navier Stokes equations using "Stable Fluids" method proposed by Jam Stam in a closed box with a forcing that creates a bloom. 



# Method

## Basic Equations

The solution is based off Navier Stokes Equation particularly:

$$\frac{\partial u}{\partial t} + (u \cdot \nabla)u = \frac{-1}{\rho} \cdot \nabla \rho + \nu \cdot \nabla^{2}u + f $$

Incompressibility Equation in the simulation is based on:

$$\nabla \cdot u = 0 $$ 

where:
 - u: Velocity (assumed to be a 2D vector)
 - p: pressure
 - f: Forcing
 - $\rho$: Density 
 - $\nu$: Kinematic Viscosity 
 - t: Time
 - $\nabla$: Nonlinear Convection as well as divergence and gradient
 - $\nabla^{2}$: Laplace Operator 
