# Options Pricing & Greeks Engine

## Overview

A Python-based quantitative finance project implementing and comparing analytical,
numerical, and stochastic methods for European option pricing.

## Models

- Black-Scholes analytical pricing
- Cox-Ross-Rubinstein binomial tree
- Monte Carlo simulation

## Risk Analytics

Implemented the five core Black-Scholes Greeks:

- Delta
- Gamma
- Vega
- Theta
- Rho

## Numerical Methods

The project evaluates numerical convergence by comparing:

- Binomial tree prices against the Black-Scholes benchmark
- Monte Carlo estimates against the Black-Scholes benchmark

## Implied Volatility

Implemented a numerical root-finding framework to recover implied volatility
from an observed option market price.

## Sensitivity Analysis

Explored option-value sensitivity to:

- Underlying stock price
- Volatility
- Time to expiry
- Interest rates

## Key Results

For the baseline option:

- Black-Scholes call price: $10.4506
- Binomial tree price (500 steps): $10.4466
- Monte Carlo price (500,000 simulations): $10.4501

The binomial and Monte Carlo approaches converged closely to the analytical
Black-Scholes benchmark.

## Technologies

Python  
NumPy  
Pandas  
SciPy  
Matplotlib  
Plotly
