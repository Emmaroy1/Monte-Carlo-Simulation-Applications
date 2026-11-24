# Monte-Carlo-Simulation-Applications
Monte Carlo simulation exploring probability theory, stochastic interest rate modeling, light transport, and structural reliability through numerical methods.
# Monte Carlo Simulation: Theory and Applications

### Mathematical Foundations and Numerical Applications in Finance, Architecture and Engineering

## Overview

This project explores **Monte Carlo simulation** as a numerical method for estimating mathematical expectations, probabilities and outcomes in systems involving uncertainty.

It introduces the mathematical foundations of Monte Carlo methods, including the **Law of Large Numbers (LLN)** and the **Central Limit Theorem (CLT)**, and demonstrates how simulation accuracy evolves as the number of random samples increases.

The theoretical concepts are applied to three practical problems across different disciplines, with particular emphasis on stochastic interest rate modeling in quantitative finance.

## Applications

### 1. Quantitative Finance — Vasicek Interest Rate Model

Implementation of the Vasicek short-rate model to simulate possible future interest rate paths using stochastic processes and Monte Carlo methods.

The model is based on the stochastic differential equation.

The simulation explores:
- Mean-reverting interest rate dynamics.
- Brownian motion and random market shocks.
- Generation of multiple interest rate scenarios.
- Statistical analysis of simulated terminal interest rates.

### 2. Architecture — Monte Carlo Ray Tracing

A two-dimensional simulation of light propagation and diffuse reflection inside a room.

Using a Lambertian reflection model, random light-ray directions are generated to investigate how light travels through an enclosed space.

The simulation explores:
- Random sampling of reflection angles.
- Ray trajectories and wall interactions.
- Diffuse reflection.
- Estimation of light reaching a specified location.

### 3. Reliability Engineering — Structural Failure Probability

A probabilistic model investigating the impact of uncertainty in material properties, structural dimensions and applied loads on beam failure.

Using the bending stress equation.
Monte Carlo sampling is used to estimate the probability that structural stress exceeds material yield strength.

The simulation explores:
- Random distributions of applied loads and beam dimensions.
- Variability in material yield strength.
- Structural stress calculations.
- Estimation of failure probabilities under uncertainty.

## Mathematical Concepts

- Monte Carlo methods and random sampling
- Probability distributions and expected values
- Law of Large Numbers
- Central Limit Theorem
- Confidence intervals and standard errors
- Stochastic differential equations
- Brownian motion and mean reversion
- Numerical simulation and probabilistic modeling

## Technologies and Tools

- Python
- SageMath
- NumPy
- Matplotlib
- CoCalc / Jupyter Notebook environment

## Repository Structure

```text
monte-carlo-simulation-applications/
│
├── README.md
└── Monte_Carlo_Simulation.ipynb
```

## How to Explore

The Jupyter Notebook contains the mathematical explanations, simulation code, visualizations and interpretation of results.

To explore the project:
1. Open the `.ipynb` notebook directly on GitHub to view the documented analysis.
2. Download the notebook to run the simulations.
3. Use a compatible SageMath environment for full execution.

## Project Information

**Project Type:** Academic Group Project  
**Course:** Mathematics & Computer Science  
**Date:** December 2025

**Authors:**
- Emma Roy
- Elizabeth Baril
- Loraine Ouellet
- Rebecca Jovin

---

This project demonstrates how computational methods and probability theory can be applied to model uncertainty and analyze complex systems across different disciplines.
