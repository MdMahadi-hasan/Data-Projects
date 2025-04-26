
# Bitcoin vs S&P 500 Volatility Analysis using GARCH(1,1)

## Project Overview
This project conducts a comparative analysis of the volatility between Bitcoin and the S&P 500 index using the GARCH(1,1) model. It aims to understand the differences in volatility behavior between a digital asset (Bitcoin) and a traditional stock market index (S&P 500).

## Data Used
- Bitcoin historical price data.
- S&P 500 historical price data.
- Data was cleaned, log-transformed (where necessary), and converted into returns for model fitting.

## Methodology
- Data preprocessing and stationarity testing (ADF Test).
- Visual inspection through rolling statistics and ACF plots.
- Fitting GARCH(1,1) models separately for Bitcoin and S&P 500 returns.
- Evaluation and comparison of estimated GARCH parameters (omega, alpha, beta).
- Testing implications against Efficient Market Hypothesis (EMH).

## Key Results
- Bitcoin shows significantly higher volatility and a longer response to market shocks compared to S&P 500.
- S&P 500 exhibited lower and more stable volatility, making it a more suitable candidate for risk-averse investment strategies.
- GARCH(1,1) parameters highlighted volatility clustering in Bitcoin, challenging the weak and semi-strong forms of EMH.
- The S&P 500 data confirmed the presence of more predictable and stable financial behavior.

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- Arch (for GARCH models)
- NumPy

## Skills Demonstrated
- Time Series Analysis
- Financial Econometrics
- GARCH Modeling
- Data Visualization
- Critical Analysis of EMH in the context of cryptocurrencies

## How to View
Please open the `.ipynb` notebook file with Jupyter Notebook or JupyterLab to view all code, outputs, and interpretations.

## Acknowledgment
- Grammar and code corrections were assisted using claude.ai.

---
