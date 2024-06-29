# PnL Calculator for Bitcoin Trading Strategy
## Overview
This repository contains a Python class PnlCalculator designed to execute a trading strategy on Bitcoin historical data and calculate the Profit and Loss (PnL) based on specific entry and exit signals.

The strategy uses Heikin-Ashi candlesticks and moving averages to generate buy and sell signals, with specific logic for trade execution and stop-loss conditions.

## Features
Calculates Heikin-Ashi candlesticks.
Generates buy and sell signals based on moving average crossovers.
Implements stop-loss logic to manage risk.
Calculates the overall PnL, including transaction costs.
Outputs the trade log and cumulative profit.
## Files
btc_3m_2019-24.csv: Historical Bitcoin data at 3-minute intervals from 2019 to 2024.

PnLCalculator.py: Python script containing the PnlCalculator class and its methods.

pnl_since_2019.csv: Output CSV file containing the trade log and cumulative profit.
