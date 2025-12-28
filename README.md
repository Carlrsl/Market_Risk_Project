# Market Risk Project - ESILV A4 (2025-2026)

**Authors:** Carl ROUSSEL & Alec REYNEN  
**Course:** Market Risk  
**Date:** December 2025

## 📋 Project Overview

This project explores advanced methods for quantifying Market Risk, moving beyond standard Gaussian assumptions to capture the complex reality of financial time series. It involves implementing risk metrics and market models manually, without relying on pre-built financial packages.

### Key Topics Covered:

* **Part A & B (VaR & ES):** Estimation of **Value-at-Risk (VaR)** and **Expected Shortfall (ES)** on Natixis stock data using non-parametric methods (Biweight Kernel).
* **Part C (Extreme Value Theory):** Analysis of heavy tails using the **Pickands estimator** to determine the Generalized Extreme Value (GEV) parameters and assess tail risk.
* **Part D (Liquidity Risk):** Calibration of **Bouchaud’s Model** on microstructure data to quantify the concave impact of trading volume (Square-Root Law) and its temporal decay.
* **Part E (Fractal Analysis):** Multiresolution analysis using **Haar Wavelets** to test the **Epps Effect** and estimation of the **Hurst Exponent ($H$)** to calculate Fractal Volatility vs Standard Volatility.

**Libraries used:**
* `numpy`: Matrix calculations and math functions.
* `pandas`: Data manipulation and time-series handling.
* `matplotlib`: Data visualization and plotting.
* `statsmodels`: OLS Regression for parameter estimation.

## 📂 File Structure

This repository contains the following files:

* **`Market_Risk_Reynen_Roussel.ipynb`**: The main Jupyter Notebook containing all the Python code, analysis, and visualizations for questions A to E.
* **`Natixis.xlsx`**: Historical daily price data for the Natixis stock (Used for VaR, ES, and EVT analysis).
* **`Dataset TD4.xlsx`**: Market microstructure data (Transactions, Volume, Signs) used for Bouchaud's Liquidity Model.
* **`Dataset TD5.xlsx`**: High-frequency FX data (GBPEUR, SEKEUR, CADEUR) used for Fractal Analysis and Hurst Exponent estimation.
* **`Project Instructions.pdf`**: The official project guidelines and problem statement.


---
*Project carried out as part of the Engineering Degree at ESILV (École Supérieure d'Ingénieurs Léonard de Vinci).*