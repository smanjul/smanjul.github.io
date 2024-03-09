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
<br/>

<div class="row">
  <div class="col-md-4" markdown="1">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  <img src="/assets/img/TG_vorticity.png" width="165" height=auto>
  </div>
  <div class="col-md-8" markdown="1">
  **CDS3D**: A high-order, high-fidelity solver for compressible Navier-Stokes equations in generalized curvilinear coordinates. The code uses a high-order compact difference scheme for spatial discretization with filtering operators.
  </div>
</div>

<br/>

<div class="row">
  <div class="col-md-4" markdown="1">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  <img src="/assets/img/NB_RBC.png" width="165" height=auto>
  </div>
  <div class="col-md-8" markdown="1">
  **InCurvCDS**: An incompressible Navier-Stokes solver in the generalized curvilinear coordinates. InCurvCDS uses a high-order compact difference scheme and filtering operators. It can simulate flow problems with and without thermal stratification in complex domains using body-fitted grids. The code is written in modern Fortran using derived data types to keep it generic. It is further enhanced to simulate the Non-Boussinesq flows. Recently, the solver has been extended to simulate the multiphase flows.
  </div>
</div>

<br/>

<div class="row">
  <div class="col-md-4" markdown="1">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  <img src="/assets/img/VEflow.png" width="200" height=auto>
  </div>
  <div class="col-md-8" markdown="1">
  **VEflow**: An incompressible Navier-Stokes solver in the cylindrical coordinates written in Fortran90. The solver employs a fractional-step algorithm and uses a central difference scheme on a fully staggered grid.
  </div>
</div>

<br/>

<div class="row">
  <div class="col-md-4" markdown="1">
  <!-- ![Alt Text](../img/folder/blah.jpg) -->
  <img src="/assets/img/ftle.png" width="75" height=auto>
  </div>
  <div class="col-md-8" markdown="1">
  <br/>
  **FTLE3D**: A Fortran90 program to compute the three-dimensional Finite Time Lyapunov Exponent from raw velocity data.
  </div>
</div>
