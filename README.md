# Modeling Human Extinction: A Comparative Analysis and Deterministic and Stochastic Approaches

This repository contains Python code for modeling global population dynamics under the influence of declining fertility rates. It includes deterministic and stochastic models to project population growth and assess when critical thresholds for genetic diversity may be reached.

## Features

1. **Fertility Rate Forecasting**:
   - Models a linearly decreasing Total Fertility Rate (TFR) over time until it reaches zero.

2. **Deterministic Population Model**:
   - Simulates population growth dynamics using logistic growth with declining fertility rates.
   - Highlights thresholds for Minimum Viable Population (MVP) and Evolutionarily Viable Population (EVP).

3. **Stochastic Population Model**:
   - Simulates population dynamics with random variations in birth and death rates.
   - Performs multiple simulations to account for uncertainties and generates statistical insights.

4. **Visualization**:
   - Plots deterministic and stochastic projections.
   - Provides zoomed-in views of population thresholds.

5. **Critical Thresholds**:
   - Identifies years when population falls below MVP (50 individuals) and EVP (500 individuals).

## Requirements

- Python 3.x
- NumPy
- Matplotlib
