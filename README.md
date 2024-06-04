# UCL COMP0171 Bayesian Deep Learning (2023/24)

This repository contains the first coursework I completed for my MSc module [COMP0171 Bayesian Deep Learning](https://www.ucl.ac.uk/module-catalogue/modules/bayesian-deep-learning-COMP0171).


## Tasks for coursework 1

1. **Bayesian Inference**
   - Computed log joint probability of a bayesian model
   - Implemented a MCMC sampler for estimating the posterior
   - Short questions on the MCMC method

2. **Bayesian Classifier**
   - Implemented a Bayesian logistic regression model
     - Finding maximum a posterior (MAP) esitmate through gradient descent
     - Approximating the posterior using Laplace approximation
     - Comparing features sets by estimating the model evidence
   - Short questions on the feature set selection strategy and overfitting problem in a bayesian setting


## Tasks for coursework 2

1. **Bayesian Neural Network**
   - Implemented stochastic gradient Langevin dynamics (SGLD) for sampling network parameters
   - Estimated epistemic and aleatoric uncertainty
   - Analysed temperature scaling and its impact on Expected Calibration Error (ECE)

2. **Fitting a Variational Auto-Encoder (VAE)**
   - Designed and implemented the encoder and decoder for the MNIST data
   - Trained the VAE to maximise per-datapoint evidence lower bound (ELBO)


## Python Environment

Requirement: `python=3.11`

    pip install -r requirements.txt