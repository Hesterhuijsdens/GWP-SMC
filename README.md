# Robust Inference of Dynamic Covariance Using Wishart Processes and Sequential Monte Carlo

This project combines the [Generalised Wishart process](https://arxiv.org/abs/1101.0240) with Sequential Monte Carlo sampling for modelling dynamic covariance between time series. Although the Wishart process is a flexible model, inference of its parameters remains challenging. In this repository, we compare Sequential Monte Carlo against MCMC and variational inference on two simulation studies, and find that Sequential Monte Carlo results in robust estimates and out-of-sample predictions of dynamic covariance. Moreover, we also apply the Wishart process with SMC on an empirical dataset. 

### Package requirements
package | version
--------|----------
[bayesianmodels](https://github.com/UncertaintyInComplexSystems/bayesianmodels.git) | 0.0.1
blackjax | [this version](https://github.com/Hesterhuijsdens/blackjax.git) 
[jaxkern](https://github.com/JaxGaussianProcesses/JaxKern.git) | 0.0.5
distrax | 0.1.5
[BANNER](https://github.com/DavidLeeftink/BANNER.git) | -

