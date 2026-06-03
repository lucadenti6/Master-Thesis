# Master-Thesis

# Master's Thesis: Parametrix Method for SPDEs and Applications in Quantitative Finance

Welcome to the repository dedicated to my Master's thesis in Mathematics / Financial Mathematics. This project bridges advanced stochastic analysis, partial differential equations (PDEs), and practical quantitative financial engineering.

## Abstract & Theoretical Framework

In this thesis, we extend a classical analytical tool: the well-known *parametrix method* used for the construction of fundamental solutions of PDEs with Hölder continuous coefficients. Specifically, we investigate an analogy of the Duhamel principle to construct the fundamental solution of Stochastic Partial Differential Equations (SPDEs). 

These analytical notions are shown to coincide with Donsker’s delta functions—generalized Wiener functionals that have been extensively studied within the framework of Malliavin calculus. This research rigorously follows and builds upon the advanced techniques exposed by Bally, Caramellino, and Prado (2023), which, to the best of our knowledge, represents the unique and pioneering work on the application of the parametrix method to this specific class of SPDEs.

## Quantitative Finance Applications & Tools

Beyond the pure theoretical and foundational mathematics, a core objective of this work was to bridge the gap between abstract stochastic calculus and financial engineering. To this end, this repository contains code, scripts, and implementations designed to leverage these theoretical results for practical market applications.

Key mathematical methods and tools developed in this project include:

* **Advanced Volatility Modeling:** Implementation and analysis of stochastic volatility frameworks (such as the Heston model), focusing on how structural transitions in SPDEs govern financial asset dynamics.
* **Efficient Numerical Pricing:** Leveraging fundamental solutions and numerical techniques to price derivative contracts under non-trivial, rough, or local-stochastic volatility environments.
* **Computation of Greeks:** Development of analytical and simulation-based tools for calculating Option Greeks ($\Delta, \Gamma, \mathcal{V}$, etc.). By utilizing the underlying smooth density structures provided by the parametrix method and Malliavin weights, the algorithms achieve high precision and stability, avoiding the high-variance pitfalls of standard finite-difference methods.
* **Numerical Optimization & Calibration:** Algorithms (utilizing root-finding methods like Newton-Raphson and Scipy optimization) designed to invert option prices and extract flat or skewed implied volatility surfaces.

## Repository Structure

* `/notebooks`: Jupyter Notebooks containing the numerical simulations, volatility smile plotting, and calibration scripts.
* `/src`: Core Python scripts implementing the financial models, Black-Scholes baselines, and pricing functions.
* `/docs`: Additional LaTeX summaries, notes, or presentation slides related to the thesis defense.

---
*For any questions, discussions on stochastic calculus, or potential collaborations in quantitative finance, feel free to reach out or open an issue!*
