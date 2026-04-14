# 46755-offering-strategy_Asgn2
DTU 46755 – Renewables in Electricity Markets. Assignment 2: Stochastic offering strategy under one- and two-price balancing schemes, CVaR risk aversion, and ancillary service participation (FCR-D).

# 46755 – Offering Strategy (Assignment 2)

**Course:** Renewables in Electricity Markets – DTU  
**Teachers:** Jalal Kazempour, Lesia Mitridati  
**Deadline:** May 11, 2026  

---

## Project Overview

This project investigates optimal market participation strategies from a stakeholder perspective under uncertainty.

The assignment consists of two main components:

### Step 1 – Day-Ahead and Balancing Markets
- Stochastic offering strategy (≥ 1,600 scenarios)
- One-price balancing scheme
- Two-price balancing scheme
- 8-fold cross-validation
- Risk-averse strategy using CVaR (α = 0.90)

### Step 2 – Ancillary Services (FCR-D UP, DK2)
- ALSO-X formulation under P90 requirement
- CVaR-based reserve bidding
- Out-of-sample verification
- Sensitivity analysis on reliability threshold

---

## Methodology

- Scenario-based stochastic optimization
- Monte Carlo scenario generation
- Cross-validation for policy robustness
- Risk modeling via CVaR
- Out-of-sample performance evaluation

---

## Repository Structure

- `data/` → raw and processed datasets  
- `notebooks/` → analysis and optimization experiments  
- `src/` → reusable model formulations  
- `reports/` → final submitted report  

---

## Requirements

- Python 3.12+
- Gurobi
- NumPy
- Pandas
- Matplotlib
- SciPy

Install via: pip install -r requirements.txt

---

## Authors

Enlisted in the group report
MSc Sustainable Energy Systems – DTU
