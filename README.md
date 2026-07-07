# Cointegration Analysis of Apple and Amazon Stock Prices

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue)
![Statsmodels](https://img.shields.io/badge/Statsmodels-Econometrics-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## Project Overview

This project investigates the long-run relationship between the stock prices of **Apple Inc. (AAPL)** and **Amazon.com Inc. (AMZN)** using econometric time series techniques. The analysis applies the **Engle-Granger Cointegration Test** and an **Error Correction Model (ECM)** to determine whether the two non-stationary stock price series share a stable long-run equilibrium relationship.

The project demonstrates the practical application of financial econometrics using Python and is intended as a portfolio project for quantitative finance, financial data science, and investment analytics.

---

## Objectives

- Analyze the historical relationship between Apple and Amazon stock prices.
- Test for stationarity using the Augmented Dickey-Fuller (ADF) test.
- Examine the existence of a long-run equilibrium relationship through cointegration analysis.
- Estimate an Error Correction Model (ECM) to analyze short-run dynamics.
- Evaluate model adequacy using residual diagnostics.

---

## Dataset

**Source:** Yahoo Finance (`yfinance`)

**Companies**

- Apple Inc. (AAPL)
- Amazon.com Inc. (AMZN)

**Frequency**

- Monthly Closing Prices

**Study Period**

- January 2015 – December 2024

---

## Methodology

The analysis follows the Engle-Granger two-step approach:

1. Import required libraries
2. Download historical stock price data
3. Data cleaning and preprocessing
4. Logarithmic transformation
5. Stationarity testing (ADF Test)
6. First differencing
7. Cointegration analysis using OLS
8. Residual stationarity testing
9. Error Correction Model (ECM)
10. Residual diagnostics and interpretation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Statsmodels
- yfinance
- Google Colab

---

## Repository Structure

```
Cointegration-Analysis-Apple-Amazon/
│
├── notebooks/
│   └── cointegration_analysis_apple_amazon.ipynb
│
├── figures/
│
├── data/
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## Key Findings

- Both stock price series are non-stationary at their levels.
- First differencing transformed both series into stationary processes.
- The Engle-Granger test confirmed a statistically significant long-run equilibrium relationship between Apple and Amazon.
- The Error Correction Model indicated gradual adjustment toward long-run equilibrium after short-run deviations.
- Residual diagnostics suggested that the ECM adequately captured the short-run dynamics of the series.

---

## Future Improvements

Potential extensions of this project include:

- Johansen Cointegration Test
- Vector Error Correction Model (VECM)
- Pair Trading Strategy
- Forecasting using Machine Learning models
- Incorporating macroeconomic variables

---

## Author

**Victor Ojwang**

GitHub: https://github.com/vojwang

---

## License

This project is licensed under the MIT License.
