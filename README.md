# Bayesian Model Calibration with Python

This repository contains Python code for performing Bayesian model calibration using Markov Chain Monte Carlo (MCMC) methods. It demonstrates the calibration of a simple logistic growth model, representing tumor growth, to synthetic data. The project utilizes libraries such as `numpy`, `matplotlib`, `scipy`, and `emcee`.

## Model Description

The logistic growth model is defined by the differential equation:

$$
\frac{dN}{dt}=rN\left(1-\frac{N}{K}\right),
$$

where:

- $N$ is the number of tumor cells,
- $r$ is the growth rate of the tumor cells,
- $K$ is the environmental carrying capacity.

## Dependencies

- Python 3
- NumPy
- Matplotlib
- SciPy
- emcee
- corner

## Installation

Ensure you have Python 3 installed on your system. You can then install the dependencies using pip:

```bash
pip install numpy matplotlib scipy emcee corner

## Key Features

- Model Definition: A logistic growth model simulating tumor growth.
- Data Generation: Synthetic data generation based on the true model parameters with added Gaussian noise.
- Maximum Likelihood Estimation (MLE): Estimation of model parameters by maximizing the likelihood function.
- Bayesian Calibration: Application of MCMC to estimate the posterior distributions of the parameters.

## Results

The code will generate plots showing the true data, measured (noisy) data, and the calibrated model fit. Additionally, it will produce corner plots showing the posterior distributions of the model parameters.

## Contributors

Ernesto Lima

Feel free to fork this project, contribute, and suggest improvements. For any questions or contributions, please open an issue or a pull request.