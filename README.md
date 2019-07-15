# Hybrid Monte Carlo, or Hamiltonian Monte Carlo

## Metropolis-Hastings Method
<img src="http://www.sciweavers.org/upload/Tex2Img_1557063031/render.png"/>

## Random Walk Sampling
<img src="http://www.sciweavers.org/upload/Tex2Img_1557062476/render.png"/>
<img src="http://www.sciweavers.org/upload/Tex2Img_1557063410/render.png"/>

<p float="middle">
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/random_walk_0.01.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/random_walk_0.1.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/random_walk_1.0.png", width="30%", height="30%"/>
</p>

## Langevin Sampling

Langevin dynamics: <img src="http://www.sciweavers.org/upload/Tex2Img_1557064556/render.png">

<p float="middle">
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/langevin_0.01.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/langevin_0.1.png", width="30%", height="30%"/>
  <img src="https://github.com/Rafaelchen0625/Hybrid-Monte-Carlo/blob/master/Images/langevin_1.0.png", width="30%", height="30%"/>
</p>

## Hamiltonian Sampling

Hamilton dynamics: 

<img src="http://www.sciweavers.org/upload/Tex2Img_1557065364/render.png"/>

Where,[[2]](https://en.wikipedia.org/w/index.php?title=Hamiltonian_mechanics&oldid=848677024)
1. The first Hamilton equation means that the force equals the negative gradient of potential energy.
2. The second Hamilton equation means that the particles velocity equals the derivative of its kinetic energy with respect to its momentum.

#### Numerical Methods[[1]](https://arxiv.org/abs/1206.1901)
1. Euler's Method
<img src="http://www.sciweavers.org/upload/Tex2Img_1557068627/render.png"/>

2. Modified Euler's Method
<img src="http://www.sciweavers.org/upload/Tex2Img_1557068516/render.png"/>

3. Leapfrog Method
<img src="http://www.sciweavers.org/upload/Tex2Img_1557068596/render.png"/>


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
