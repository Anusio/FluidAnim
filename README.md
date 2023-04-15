# FluidAnim
Fluid animation using pygame

In this notebook we tried to do a simple 2D animation version using Python folowing:

https://www.dgp.toronto.edu/public_user/stam/reality/Research/pdf/GDC03.pdf
and 
https://thecodingtrain.com/challenges/132-fluid-simulation

# Navier-Stokes Animation

Navier-stokes are partial differential equations that describe the motion of viscous fluid substances, their simplified equation is defined as:

$\frac{\partial u}{\partial t} + u \cdot \nabla u = g - \frac{1}{\rho} \nabla p + v \nabla ^2 u$

where:

- $u$ is the velocity vector, 
- $g$ is the acceleration vector due to a body force, 
- $p$ is pressure, 
- $v$ = $\frac{\mu}{\varrho}$ is the kinematic viscosity, 
- $\mu$ is the dynamic viscosity, and 
- $\rho$ is the density.
