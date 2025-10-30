# Ethereum Price Forecasting

This project predicts future Ethereum (ETH-USD) prices using time series forecasting techniques such as **ARIMA**.  

The data are collected from **Yahoo Finance** via the `yfinance` Python library.

## Project Structure

- **data/** – contains ETH historical price data *(not uploaded to GitHub)*
- **notebooks/** – main Jupyter notebook for analysis and modeling
- **reports/figures/** – forecast plots and visualizations

## Dependencies

All dependencies are specified in the `environment.yml` file.  
To recreate the environment, run:

```bash
conda env create -f environment.yml
conda activate eth_crypto
