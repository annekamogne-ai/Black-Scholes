#  Pricing European Options with the Black-Scholes Model

##  Project Overview

This project implements the Black-Scholes model to price European call options using Python.
It also explores how key parameters such as volatility and time to maturity affect option prices.

The goal is to demonstrate both theoretical understanding and practical implementation of a fundamental model in financial engineering.

---

##  Theoretical Background

The Black-Scholes model assumes that the price of an asset follows a stochastic process:

dS_t = μ S_t dt + σ S_t dW_t

The price of a European call option is given by:

C = S₀ N(d₁) − K e^{-rT} N(d₂)

Where:

* S₀: initial asset price
* K: strike price
* r: risk-free interest rate
* σ: volatility
* T: time to maturity
* N(): cumulative distribution function of the standard normal distribution

---

##  Implementation

The model is implemented in Python using:

* NumPy
* SciPy
* Matplotlib

Main features:

* Analytical pricing using Black-Scholes formula
* Sensitivity analysis (volatility, maturity)
* Monte Carlo simulation for comparison

---

##  Results

###  Impact of Volatility

The option price increases as volatility increases.
This reflects higher uncertainty in the underlying asset price.

###  Impact of Time to Maturity

Longer maturities generally lead to higher option prices due to increased uncertainty.

###  Monte Carlo vs Black-Scholes

Monte Carlo simulation produces results close to the analytical solution, validating the implementation.

---

##  How to Run

1. Clone the repository:
   git clone https://github.com/annekamogne-ai/Black-Scholes.git

2. Install dependencies:
   pip install numpy scipy matplotlib

3. Run the notebook:
   pricing_option.ipynb

---

##  Conclusion

This project demonstrates how mathematical models can be used to price financial derivatives.
The Black-Scholes model provides a closed-form solution under simplifying assumptions, while Monte Carlo methods offer a flexible numerical alternative.

---

##  Possible Improvements

* Use real market data
* Estimate historical volatility
* Extend to other models (Heston, stochastic volatility)
* Price put options

---

##  Author

Kamogne Anne Marie
Master’s student in Mathematics (Probability, Statistics, Finance)
Aspiring Machine Learning Engineer
