# Walmart Stock Analysis and Option Pricing

The project focuses on analyzing historical stock data for **Walmart (WMT)**, performing statistical tests on the log-returns, and calculating the prices of European call and put options using various pricing methods.

## Project Overview

The key objectives of the project:

- [x] **Price Plot**: Visualizing the historical stock prices.
- [x] **Log-Returns Plot**: Calculating and plotting log-returns of the stock prices.
- [x] **Normality Tests**: Testing whether log-returns are normally distributed using QQ plot, histogram, and statistical tests (Jarque-Bera, Kolmogorov-Smirnov).
- [x] **Historical Volatility**: Estimating historical volatility using log-returns.
- [x] **Risk-Free Rate**: Identifying the risk-free rate for the USD (3-Months Treasury rate).
- [x] **Independence Test**: Test whether the log-returns are independent and uncorrelated.
- [x] **Option Pricing**:
    - Calculate the option prices for an **In-The-Money (ITM)** European call option and European put option with a maturity date of **May 31, 2024**.
    - Use the **Cox-Ross-Rubinstein (CRR)**, **Black-Scholes**, and **Monte Carlo Simulation** methods to compute option prices.
    - Compare the option prices obtained from different methods.
- [x] **Advanced Volatility Models**: Use volatility estimation methods beyond historical volatility (e.g., GARCH or Stochastic Volatility models).

## Tools and Libraries

- **Jupyter Notebook**: All the analysis and option pricing models are implemented using Jupyter.
- **Python Libraries**:
  - `numpy`, `pandas`: Data manipulation and analysis.
  - `matplotlib`, `seaborn`: Visualization.
  - `scipy.stats`: Statistical tests.
  - `statsmodels`: Time series analysis.
  - `yfinance`: Downloading stock data from Yahoo Finance.
  - `arch`: GARCH model for volatility estimation.
  - `mplfinance`: Plotting stock data.
  - `math`: Mathematical operations for option pricing models.
  
## Instructions

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/walmart-options-analysis.git
