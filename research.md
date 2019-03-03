---
layout: page
title: My research
sidebar_link: true
---

I am always curious to learn more about nature, and numerical methods and computer algorithms are the tools of my trade. In my PhD studies, I focus on fully kinetic Particle-In-Cell (PIC) simulations of ionospheric plasmas, in particular in relation to spaceborn Langmuir probes. Langmuir probes are instruments used to measure the electron density in the ionosphere. Unfortunately, the accuracy of the measurements is degraded due to non-ideal effects, such as excess charging of the spacecrafts, finite-length effects of the probe, and lack of thermal equilibrium in the ionosphere which causes the plasma to be non-Maxwellian. I study, and characterize these effects, and suggest ways to mitigate them.

![CubeSat mesh](/assets/cubesat.png)

Since the simulations contain probes and spacecraft of complex geometrical shapes, we developed our program, PUNC++, to use an unstructured mesh, where the field quantities are solved using the finite element problem solving environment FEniCS. Below is a very rough 2D simulation using PUNC++. It shows the charge density of a streaming plasma past the conducting letters PUNC++. The red color indicates an excess of positively charged ions, and the blue color an excess of electrons. The electrons travel much faster than the ions due to their higher mobility, and therefore fills the domain from the boundaries immediately, whereas the ions are slower, and are mostly carried along by the wind. More realistic simulations in 3D are run on a supercomputer, and can take anywhere from a day to several months.

![PUNC++](/assets/punc++.gif)

Earlier projects in computational electromagnetics involves studying scattering phenomena using inetgral equation solver of Maxwell's equations, as well as the Finite-Difference Time-Domain (FDTD) equation with Perfectly Matched Layers (PML). I have also designed, simulated, built and tested two antennas with feeding networks during my master's thesis, and I have two years of experience designing motor driviers and DC/DC converters.
