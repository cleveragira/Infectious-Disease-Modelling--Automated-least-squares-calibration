# Automated Least-Squares Calibration using `optim()` in R

This repository contains a Jupyter Notebook demonstrating the use of R's built-in optimization function, `optim()`, for least-squares calibration. The goal is to estimate the best parameters for an SIR (Susceptible-Infected-Recovered) model by minimizing the sum of squared residuals.

## Description

The notebook walks through:

- Understanding the key arguments of `optim()`, including `par` (initial parameter values) and `fn` (the function to be minimized).
- Implementing an optimization function to estimate the best values of β (transmission rate) and γ (recovery rate) for the SIR model.
- Fitting the model to an example dataset.
- Visualizing the observed data against the best-fit model.

## Tasks Covered

1. Using `optim()` to determine the best-fitting β and γ parameters.
2. Plotting the example dataset against the optimized SIR model.

## Requirements

To run this notebook, ensure you have the following installed:

- R
- R packages: `deSolve`, `ggplot2`
- Jupyter Notebook with R kernel

## Running the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Mod_3_notebook_2_Automated_Least-Squares_Calibration.ipynb
   ```
3. Follow the instructions in the notebook to run the optimization process.


