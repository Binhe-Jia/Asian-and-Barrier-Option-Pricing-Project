# Asian and Barrier Option Pricing

## Overview

This repository contains the implementation and analysis for the **Asian and Barrier Option Pricing Project** completed for **ACT460 – Stochastic Methods for Finance (University of Toronto)**. The project combines **theoretical derivations** with **Monte Carlo simulations** to study the pricing and risk sensitivities of path-dependent derivatives under the Black–Scholes framework.

The core focus is on:

* Arithmetic and geometric **Asian call options**
* **Barrier up-and-in put options**
* Monte Carlo estimation, discretization effects, and convergence
* Numerical estimation of **Greeks** using finite differences and pathwise estimators

The repository is structured to support both **reproducible computation** and **academic reference**.

---

## Project Components

### 1. Arithmetic Average Asian Call Option

* Pricing under the Black–Scholes model using Monte Carlo simulation
* Analysis of payoff distribution and estimator variance
* Comparison with European call options

### 2. Parameter Sensitivity Analysis

The effect of key model parameters on the Asian option price:

* Initial price (S_0)
* Strike price (K)
* Risk-free rate (r)
* Volatility (\sigma)

Includes graphical comparisons and economic interpretation.

### 3. Discretization Effects

* Impact of the number of monitoring points (m)
* Comparison of simple averaging vs. trapezoidal integration
* Empirical convergence behavior and Monte Carlo noise analysis

### 4. Greeks Estimation

Greeks for the arithmetic Asian call option:

* Delta, Vega, and Rho

Methods compared:

* Finite differences (forward / central, independent vs. CRN)
* Pathwise estimators

Conclusion: pathwise estimators provide more stable and lower-variance estimates.

### 5. Geometric Average Asian Call Option

* Full derivation of the closed-form pricing formula
* Adjusted volatility and dividend yield
* Monte Carlo validation of the analytical solution

### 6. Barrier Up-and-In Put Option

* Financial intuition and payoff structure
* Closed-form pricing via in–out parity
* Monte Carlo simulation and discretization bias analysis

---

