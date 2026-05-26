# Cross-Market Arbitrage Strategy

A quantitative research project on cross-market arbitrage between Gold ETFs and futures, using cointegration analysis and LSTM prediction.

## Description

This project implements a statistical arbitrage strategy by analyzing the cointegration relationship between gold ETF prices and gold futures. It includes real-time data collection, cointegration testing, signal generation, and LSTM-based basis prediction.

## Features

| Module | Description |
|--------|------------|
| Market Data Sync | Real-time multi-source data collection via Tushare Pro |
| Data Storage | Structured data management |
| Cointegration Analysis | ADF test / Error Correction Model |
| Signal Generation | Standard deviation breakout alert |
| Basis Prediction | LSTM time series forecasting |

## Tech Stack

- Python 3.9+
- Tushare Pro API
- Pandas, NumPy
- TensorFlow/Keras (LSTM)
- scikit-learn
- Jupyter Lab + VSCode

## Project Management

- Git version control
- Daily standups and code review
