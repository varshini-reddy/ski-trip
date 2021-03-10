## Bayesian Neural Networks

### Repo to track progress on bayesian/variational autoencoders

Following are good code references:

1. Reference to tensorflow probability 

2. TFP CVAE code

3. Flipout documentation

4. Blog1 - keras implementation

5. Blog2 - juandoriz


Research Papers to consider:

1. Kingma paper

2. BayesByBackprop

3. Weiwei Pan

4. Evidential Regression

5. Flipout


Following files contain the following: 

- TFP_DenseVAE_MNIST
> MNIST generation using Variational AutoEncoder

Uses TensorflowProbability. IndependentNormal for stochastic hidden units

- TFP_LinearRegression
> Using HMC for linear regression

Easy linear regression problem solved using MCMC HMC algorithm

- TFP_Understanding_HMC
> HMC algorithm code

Uses a one parameter example to demonstrate how to sample using HMC

- VAE_FromScratch
> Functional API, Gradient Tape

Using deterministic architecture to build a probabilistic model

- MCMC_Linear_MetropolisHastings
> From scratch implementation of MCMC. Use of Metropolis hastings algorithm

- FullMCMC_BNN_***
> Using MCMC to solve a simple neural network 

We try several stragies:
1. Randomly initialized weights
2. Some weights fixed
3. Early stopping

Early stopping gave good results.

- BNN_DenseVariational
> Using BayesByBackprop to find distribution of the weights 

In this exercise, we also experiment with flipout layers, and apparently get better results.
