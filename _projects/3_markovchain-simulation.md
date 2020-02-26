---
title: "Markov Chain Monte Carlo Simulations of Magnetic Spin Models"
excerpt: Created extensions of magnetic spin models, including the 2D XY model - demonstrated emergence vortices and anti-vortices <br/> <img src='/images/projects/markovchain_simulations/2D3D_combined.png' alt='2D XY model, 3D Heisenberg model' style='width:60%;border-radius:2%;' > "
collection: projects
---

This project consists of simulation software and an accompanying report on Markov Chain Monte Carlo (MCMC) simulations of magnetic 
spin models (specifically extensions of the Ising model). The software was written in Python and grew over time to encompass several 
different MCMC simulations of increasing complexity. We worked from the Metropolis algorithm to variations on the Wolff algorithm and 
the 2D XY model - observing (anti-)vortex phenomena not dissimilar to that featured in the work leading to the 2016 Nobel Prize 
in Physics: https://www.nobelprize.org/prizes/physics/2016/summary/. 

The finished simulation and data analysis software involved various features such as a fast Fourier transform to calculate 
the correlation between spins and the bootstrap statistical binning for error determination.

See the project [here](https://github.com/dominicwllmsn/markovchain_simulations).

<img src="/images/projects/markovchain_simulations/GIF_combined.gif" alt="Pleased" style="border-radius:2%;width:80%;align:center;" />

*2D XY model, illustrating the formation of vortices (blue, where all spins point to the same point) and anti-vortices 
(red, where all spins point away from the same point), as well as the 3D Heisenberg model*