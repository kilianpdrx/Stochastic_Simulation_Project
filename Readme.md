# EPFL MATH-414 Stochastic Simulation

## Project 2 — Importance Sampling by Optimal Control in Option Pricing

**Course:** MATH-414 — Stochastic Simulation  
**Project:** Importance Sampling by Optimal Control in Option Pricing  
**Deadline:** 11 January 2026  

**Group members:**  
- Kilian Pouderoux
- Barthélemy Welsch  
- Martin Engström  

---

## Project Overview

This repository contains our implementation and analysis for Project 2, which explores variance reduction via **Importance Sampling (IS)** in the context of option pricing.  
The goal is to compare crude Monte Carlo estimators with several IS techniques, including:

1. Importance Sampling via modification of the drift (changing the interest rate).  
2. Adaptive selection of the optimal modified drift.  
3. Optimal Importance Sampling obtained by solving a **Kolmogorov Backward PDE** to compute the optimal control.
4. Application of the method to both:
   - European Call options, and  
   - Up-and-Out barrier options.
