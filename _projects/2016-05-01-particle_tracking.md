---
title: 'Bayesian Particle Tracking'
subtitle: 'Tracking particle motion with Bayesian statistics and Markov Chain Monte Carlo'
date: 2016-05-01 00:00:00
description: Particle tracking with Bayesian statistics and MCMC
featured_image: '/images/particle_tracking/real_particle.png'
---

![](/images/demo/demo-landscape.jpg)

# Bayesian Particle Tracking
Bayesian Particle Tracking was one of final projects of my undergraduate degree at Harvard. It is a Python package that calculates the diffusion coefficient for a diffusion process in 3D particle tracking given a trajectory and the uncertainty on the measurments in that trajectory. The pacakge uses Bayesian statistics, in particular Markov Chain Monte Carlo (MCMC) and Maximum Likelihood Estimation (MLE) to estimate the diffusion coefficient.

I have not kept up to date with current state of the art practices but at the time of this project, there did to exist a standard accepted procedure for calculating the diffusion coefficient. Methods were very ad hoc and had major room for improvement.