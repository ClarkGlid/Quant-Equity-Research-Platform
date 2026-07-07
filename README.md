# Quant-Equity-Research-Platform

Overview

This project is a Python-based quantitative equity research model designed to evaluate and rank publicly traded Nasdaq companies using both fundamental financial data and historical market performance. The objective was to create a systematic framework for analyzing companies through a combination of financial statement analysis, custom scoring methodologies, portfolio analytics, and risk assessment.

Rather than evaluating stocks subjectively, the model applies a consistent, data-driven approach by collecting financial information through the Yahoo Finance API and calculating key performance indicators for each company. These metrics are then combined into a weighted scoring system that ranks companies according to their overall financial strength and investment characteristics

Methodology

The project begins by collecting financial statement and historical price data for a universe of large-cap Nasdaq companies using Python and the Yahoo Finance API.
From this data, the model computes several fundamental metrics commonly used in equity research, including: Profit Margin, Revenue Growth, Return on Equity (ROE), Return on Assets (ROA), Free Cash Flow Margin and Debt-to-Equity Ratio.

Each company is evaluated using these metrics and assigned a weighted score based on its relative financial performance. Higher scores indicate stronger profitability, growth potential, and financial health while accounting for leverage and risk. Beyond the fundamental analysis, the project also incorporates portfolio analytics by calculating: Historical returns, Annualized volatility, Sharpe Ratio, Beta, Maximum Drawdown

Technologies Used: Python, Google Colab, pandas, yfinance,
