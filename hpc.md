---
#layout: welcome
layout: home
title: High-Performance Computing
permalink: /hpc/
sidebar: false
#order: 2
---

Over the years I have developed a few Navier-Stokes solvers to suit my research.
<br/>
- **CDS3D**: A high-order, high fidelity solver for compressible Navier-Stokes equations in generalized curvilinear coordinates. The code uses a high-order compact difference scheme for spatial discretization with filtering operators.


- **InCurvCDS**: An incompressible Navier-Stokes solver in the generalized curvilinear coordinates. InCurvCDS uses high-order compact difference scheme and filtering operators. It can simulate flow problems with and without thermal stratification in complex domains using body-fitted grids. The code is written in modern Fortran using derived data types to keep it generic. It is further enhanced to simulate the Non-Boussinesq flows. Recently, the solver is extended to simulate the multiphase flows.


- **VEflow**: An incompressible Navier-Stokes solver in the cylindrical coordinates written in Fortran90. The solver employs fractional-step algorithm and uses central-difference scheme on a fully staggered grid.


- **FTLE3D**: A Fortran90 program to compute the three-dimensional Finite Time Lyapunov Exponent from raw velocity data.

<div class="row">
  <div class="col-md-8" markdown="1">
    <!-- ![Alt Text](../img/folder/blah.jpg) -->
    <img height="600px" class="center-block" src="assets/img/VEflow.png">
  </div>
  <div class="col-md-4" markdown="1">
    **VEflow**: An incompressible Navier-Stokes solver in the cylindrical coordinates written in Fortran90. The solver employs fractional-step algorithm and uses central-difference scheme on a fully staggered grid.
  </div>
</div>
