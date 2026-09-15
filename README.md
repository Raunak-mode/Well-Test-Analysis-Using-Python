# Well Test Analysis Using Python

## Overview

This project presents a Python-based workflow for pressure transient analysis of drawdown well-test data.

The analysis uses pressure and time data to calculate pressure drop and pressure derivative, identify flow regimes, estimate reservoir permeability and skin factor, and evaluate semi-steady-state behavior.

## Objectives

- Analyze pressure-time data from a drawdown well test
- Calculate pressure drop (ΔP)
- Calculate and analyze the pressure derivative
- Generate log-log diagnostic plots
- Identify the Infinite-Acting Radial Flow (IARF) region
- Estimate reservoir permeability
- Estimate skin factor
- Perform semi-log analysis
- Estimate drainage area from semi-steady-state behavior
- Calculate the Dietz shape factor

## Methodology

The workflow consists of:

1. Input well, reservoir, and fluid properties
2. Preparation of pressure-time data
3. Calculation of pressure drop (ΔP)
4. Numerical calculation of pressure derivative
5. Log-log diagnostic analysis
6. Automatic identification of a relatively stable IARF region
7. Permeability estimation
8. Skin-factor estimation
9. Semi-log analysis
10. Semi-steady-state analysis
11. Drainage-area estimation
12. Dietz shape-factor calculation

## Tools and Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- Google Colab / Jupyter Notebook

## Files

- `Well_Test_Analysis.ipynb` — Main well-test analysis notebook
- `well_test_data.csv` — Drawdown well-test pressure and time dataset
- `README.md` — Project documentation

## Key Results

The analysis estimates:

- Reservoir permeability, k
- Skin factor, S
- Drainage area, A
- Dietz shape factor, C_A

The project also demonstrates pressure-derivative analysis and identification of different flow regimes during a well test.

## Important Note

The dataset is intended for academic and educational purposes. The methodology demonstrates well-test interpretation concepts and should not be considered a substitute for commercial well-test interpretation software.

## Author

**Raunak Baranwal**

B.Tech Petroleum Engineering
