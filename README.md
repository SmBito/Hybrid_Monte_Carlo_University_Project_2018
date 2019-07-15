# Hybrid Monte Carlo, or Hamiltonian Monte Carlo  - University Project
Comparing the performance of Hybrid MC, Langevin MC and a simple random walk

## Metropolis-Hastings Method

## Random Walk Sampling

<p float="middle">
  <img src="https://github.com/andrew-ve/Hybrid-Monte-Carlo-university-project-2018/blob/master/Images/random_walk_0.01.png", width="30%", height="30%"/>
  <img src="https://github.com/andrew-ve/Hybrid-Monte-Carlo-university-project-2018/blob/master/Images/random_walk_0.1.png", width="30%", height="30%"/>
  <img src="https://github.com/andrew-ve/Hybrid-Monte-Carlo-university-project-2018/master/Images/random_walk_1.0.png", width="30%", height="30%"/>
</p>

## Langevin Sampling

Langevin dynamics: 

<p float="middle">
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/langevin_0.01.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/langevin_0.1.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/langevin_1.0.png", width="30%", height="30%"/>
</p>

## Hamiltonian Sampling

Hamilton dynamics: 


Where,[[2]](https://en.wikipedia.org/w/index.php?title=Hamiltonian_mechanics&oldid=848677024)
1. The first Hamilton equation means that the force equals the negative gradient of potential energy.
2. The second Hamilton equation means that the particles velocity equals the derivative of its kinetic energy with respect to its momentum.

#### Numerical Methods[[1]](https://arxiv.org/abs/1206.1901)
1. Euler's Method

2. Modified Euler's Method

3. Leapfrog Method


<p float="middle">
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/HMC_epsilon_0_0_1.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/HMC_epsilon_0_5.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/HMC_epsilon_1_0.png", width="30%", height="30%"/>
</p>

<p float="middle">
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/HMC_temp_0_1.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/HMC_temp_1.png", width="30%", height="30%"/>
</p>

<p float="middle">
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/HMC_temp_2.png", width="30%", height="30%"/>
   <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/HMC_temp_1_5.png", width="30%", height="30%"/>
</p>

<p float="middle">
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/HMC_step_1.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/HMC_step_100.png", width="30%", height="30%"/>
</p>

## Comparison
<p float="middle">
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/comparison_accept_hmc.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/comparison_accept_lan.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/comparison_accept_rw.png", width="30%", height="30%"/>
</p>

<p float="middle">
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/comparison_500.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/comparison_1000.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/comparison_5000.png", width="30%", height="30%"/>
</p>

## Reference
[1] [Neal, Radford M. "MCMC using Hamiltonian dynamics, ArXiv e-prints." arXiv preprint arXiv:1206.1901 (2012).](https://arxiv.org/abs/1206.1901)

[2] [Hamiltonian mechanics](https://en.wikipedia.org/w/index.php?title=Hamiltonian_mechanics&oldid=848677024)
