# Stock-Market-EDA-and-Prediction
# Predictive Stock Analysis
This repository contains a Jupyter Notebook that performs predictive analysis on selected stocks. The notebook leverages financial data, statistical models, and machine learning techniques to provide insights and predictions about stock performance.

# Project Overview
The goal of this project is to analyze the financial fundamentals of various companies and predict their stock prices using linear regression and time series forecasting models like Prophet. The stocks analyzed in this project are from the technology sector.

# Data Sources
The stock data is fetched using the yfinance library, which provides access to Yahoo Finance's comprehensive financial datasets. The notebook also computes and displays various financial ratios, which are critical for fundamental analysis.

# Stock Tickers Analyzed
The following stock tickers are analyzed in this project:

INTC: Intel Corporation
GFS: GlobalFoundries Inc.
QCOM: Qualcomm Incorporated
MCHP: Microchip Technology Inc.
NVDA: NVIDIA Corporation
ARM: Arm Holdings plc
Key Features
Data Fetching: The notebook fetches historical stock data and fundamental data for the selected tickers.
Fundamental Analysis: It computes and prints key financial ratios, including:
Profitability Ratios (P/E Ratio, Profit Margins, ROA, ROE)
Liquidity Ratios (Current Ratio, Quick Ratio)
Leverage Ratios (Debt to Equity, Total Debt)
Valuation Metrics (Market Cap, Enterprise Value, Price to Sales Ratio)
Growth Metrics (Earnings Growth, Revenue Growth)
Dividend Information (Dividend Yield, Payout Ratio)
Predictive Modeling: The notebook utilizes:
Linear Regression: To predict future stock prices based on historical data.
Prophet Model: For time series forecasting, providing trend and seasonality insights.
Visualization: The project includes visualizations using Plotly to plot stock trends, financial ratios, and model predictions.
# Requirements
To run the notebook, you need the following Python packages:

bash
Copy code
pip install yfinance pandas scikit-learn plotly prophet
How to Use
Clone this repository to your local machine.
Install the required packages.
Open the predictive_analysis_stocks.ipynb notebook in Jupyter.
Run the notebook cells to fetch data, perform analysis, and visualize results.
Future Enhancements
Integration with other machine learning models: Expanding the predictive modeling section with additional models like Random Forest, SVM, etc.
Automated Report Generation: Adding a feature to generate and export reports based on the analysis.
Real-time Data Analysis: Incorporating real-time stock data analysis using live data feeds.
Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or new features.
