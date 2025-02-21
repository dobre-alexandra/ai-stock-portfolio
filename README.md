# Constraint Satisfaction Problem: Personalized Stock Portfolio

The rise of retail investors in financial markets has highlighted a need for personalized portfolio guidance. This paper presents a novel algorithm that uses a refined approach to the Constraint Satisfaction Problem (CSP) framework to optimize stock portfolio allocations based on individual preferences, such as risk tolerance, return expectations, and sustainability ratings. By modeling stocks as variables, allocations as domains, and financial goals as constraints, we ensure portfolios align with investor objectives. Our approach bridges a gap in CSP literature by addressing portfolio optimization as a resource allocation problem, offering a practical tool for retail investors to make informed decisions and enhance financial inclusion.

**Disclaimer: The content presented in this notebook is for educational and illustrative purposes only. It does not constitute financial advice or a recommendation to buy, sell, or hold any securities or investments. Investments in financial markets involve risks, including the potential loss of capital.**

**Note**: In order to run this notebook, you will need to upload the associated file with stock data `stock_data.xlsx` to the working directory in Google Colab.

---

# AI Stock Portfolio Optimization

## Overview

This repository contains a Jupyter Notebook for optimizing a stock portfolio using **CVXPY**, **Pandas**, and **NumPy**. The notebook is designed to take in stock data and apply mathematical optimization techniques to determine an optimal allocation based on given constraints and user preferences.

## Features

- **Data Loading**: Reads stock data from an Excel file (`stock_data.xlsx`).
- **Portfolio Optimization**:
  - Uses convex optimization (`cvxpy`) to optimize stock allocations.
  - Allows user-defined constraints and preferences.
  - Computes portfolio metrics such as expected returns, risk, and Sharpe ratio.
- **Customization**:
  - Users can modify constraints and preferences for risk appetite and allocation limits.
  - The optimization framework can be extended to different asset classes and financial goals.

## Installation

Ensure you have Python installed, then install the required dependencies:

```sh
pip install cvxpy pandas numpy
```

## Usage

Run the Jupyter Notebook to optimize the portfolio:

```sh
jupyter notebook gen_stock_portfolio.ipynb
```

Modify the input data (`stock_data.xlsx`) and preferences as needed to adjust portfolio constraints.

## Files

- `gen_stock_portfolio.ipynb` - Jupyter Notebook for portfolio optimization.
- `report.pdf` - Summary of the optimization results.
- `stock_data.xlsx` - Example stock data input.

