# Sterile neutrino dark matter in non-standard cosmological scenarios
Production of keV sterile neutrino dark matter through oscillation and collisions in non-standard cosmological scenarios.

## Project

### Authors 
- [Cristina Benso](https://github.com/cristinabenso92) (Max-Planck-Institut für Kernphysik, Heidelberg)
- [Manfred Lindner]()(Max-Planck-Institut für Kernphysik, Heidelberg)
- [Vedran Brdar]()(Max-Planck-Institut für Kernphysik, Heidelberg)
- [Werner Rodejohann]()(Max-Planck-Institut für Kernphysik, Heidelberg)

### Goal
We want to provide a tool to explore how the production of sterile neutrino dark matter is modified in non-standard cosmological scenarios, for example if the reheating temperature is much lower than in the standard case or if the mass of sterile neutrinos undergoes a dynamical change related to a phase transition or to a misalignment mechanism.

### Description
We provide a Mathematica implementation of the standard Dodelson-Widrow production mechanism. 
The effect of non-standard cosmology is concretely implemented in the code as a change of the integration extrema of the Boltzmann equation.
With this code it is possible to obtain the distribution function and the abundance of sterile neutrino dark matter, taking into account the delay in its production due to non-standard cosmology.  
The code can be used to study both the case in which sterile neutrinos constitute the entire content of dark matter of the universe and the "cocktail dark matter" case, where only a certain percentage of dark matter is constituted by sterile neutrinos. 

In the code there are two additional hybrid sections where the Mathematica language is used to organize the data simulated with a modified version of the publicly available sterile-dm code (https://github.com/ntveem/sterile-dm). 

The first hybrid section can be used to study the realization of the standard Shi-Fuller mechanism in non-standard cosmological scenarios. We apply it to the case in which the production of sterile neutrinos starts at T = 30 MeV.

The second hybrid section can be used to study a special case of the Shi-FUller mechanism in which sterile neutrinos violate CPT symmetry. The concrete effect of such violation is that only sterile neutrinos (antineutrinos) mix with active neutrinos (antineutrinos) and therefore the presence of primordial lepton asymmetry can lead to a natural suppression of the final abundance of sterile neutrino dark matter, even in standard cosmological scenarios.

### Useful external links
Sterile-dm code: https://github.com/ntveem/sterile-dm
This code is used to carry out the work published in https://arxiv.org/abs/1911.00328 
