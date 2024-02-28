---
#layout: welcome
layout: home
title: Research
permalink: /research/
sidebar: true
order: 2
---

 <img src="/assets/img/Research.png" usemap="#workmap">

 <map name="workmap">
  <area shape="rect" alt="Bubble-type vortex breakdown in the Vogel-Escudier flow" coords="81,0,250,205" href="/vorticity_dominated/">
  <area shape="rect" alt="Salt-finger convection in a double-periodic domain" coords="50,225,273,475" href="/geophysical/">
  <area shape="rect" alt="Rayleigh-Taylor instability" coords="309,50,390,325" href="/multiphase/">
  <area shape="rect" alt="Rayliegh-Benard convection in non-Boussinesq flow" coords="433,90,625,275" href="/hpc/">
 </map>

### Research interests and approach:
My primary research interest lies in the area of fluid mechanics.
My primary approach is to analyze a problem through numerical simulation, preferably Direct Numerical Simulation. I use various analytical techniques and theories to analyze the data obtained from these simulations to gain an understanding of the physics of the problem. Specific research interests are detailed below.
(*click on each title to learn more about them*)

[**Computational Fluid Dynamics (CFD) & High Performance Computing (HPC)**](/hpc/): Often CFD research is restricted by the availability of the code to simulate a problem of interest. Most efforts to reduce development time have focused on increasing code reuse. Reusing code for different problems requires object-oriented programming (OOP). OOP’s runtime polymorphism facilitates functional purity by enabling the construction of numerical libraries that never see the data on which they operate, also known as abstraction. Abstraction denotes a useful simplification that retains only those elements necessary for a given context.
I am also interested in high-order, high-fidelity simulations, and large-scale parallel computations on multi-core heterogeneous architecture (CPU+GPU).

[**Vortex dominated flows, axial vortex breakdowns, rotating flows & stratified flows**](/vorticity_dominated/): Due to ubiquity of vortical flows in rotating systems, their understanding is important from both physics and engineering perspectives. Rotating flows are dominated by axial vortices which suffer from breakdowns that have a profound impact on the dynamics of the flow. Often vortex breakdown is a different topology from the surrounding flow and affects the mixing and material transport adversely. Most of these vortical flows occur in stratified conditions. Stratitification introduces a competition between advection and convection scales in these flows and is responsible for a complex dynamics. I am interested in the scale interaction and effective material transport in these flows.

[**Geophysical flows**](/geophysical/): Rotation is responsible for a profound effect on geophysical flows such as hurricanes, tornadoes and supercell thunderstorms. Large helicity in such flows is responsible for large scale structures formation in geophysical flows, which is also responsible for dual cascade in these flows. I am interested in the correlation between the helicity and the breakdown in such flows. This correlation has shown a decoupling of the torroidal dynamics from the poloidal dynamics at large rotation rates.

[**Multiphase flows and Particle-laden flows**](/multiphase/): Multiphase flows have applications in energy, environmentally sustainable technologies, chemical processing, critical infrastructure, healthcare and biological applications including pharmaceuticals, the design of materials and advanced manufacturing processes. The development of aerial vortex bioreactors has led to an interest in two-fluid or multiphase flows. These reactors are common in tissue engineering. I am interested in understanding the interface instabilities, interaction between vortex development and interface evolution. I am also interested in understanding the physical nature of the mixing process and devise a control strategy for it.

Particle-laden flows are a special class of the multiphase flows and find applications in flows ranging from  biological flows such as human blood (a good approximation made of particulate red blood cells suspended in plasma) to geophysical flow such as dust particle transport in the atmosphere, particle sedimentation in river beds. I am interested in developing efficient numerical simulations techniques to study these flows and use simulations to understand the preferential concentration of inertial particles, agglomeration, and particle dispersion relations to understand the turbulence modifications of the fluid flow.
