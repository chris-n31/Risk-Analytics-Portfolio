# Value at Risk (VaR) Analysis: Historical Simulation & Monte Carlo VaR for TCS Equity
## Overview

## Project Snapshot
![VaR Project](var%20project.jpg)

This project implements a complete Value-at-Risk (VaR) framework for Tata Consultancy Services (TCS.NS) using Microsoft Excel. Two industry-standard approaches—Historical Simulation and Monte Carlo Simulation—are applied to estimate one-day downside risk across multiple confidence levels. The Monte Carlo model is further validated using Kupiec's Proportion of Failures (POF) backtesting methodology.

The analysis uses 245 trading days of TCS market data from February 2025 to February 2026.

## Objective

- Estimate one-day Value-at-Risk at multiple confidence levels
- Compare Historical Simulation and Monte Carlo approaches
- Quantify potential losses in both percentage and monetary terms
- Validate model performance through backtesting

## Methodology
### Historical Simulation VaR

- Calculated daily returns from historical TCS closing prices
- Ranked returns from worst to best
- Estimated VaR using empirical return percentiles
- No distributional assumptions imposed on returns

### Monte Carlo Simulation VaR

- Estimated return mean and volatility from historical data
- Generated 10,000 simulated return scenarios
- Constructed a synthetic profit-and-loss distribution
- Calculated VaR from left-tail percentiles of simulated outcomes

## Model Validation

- Conducted Kupiec POF backtesting over 245 trading days
- Compared expected and observed VaR exceptions
- Assessed model conservatism and reliability


## Key Results

| Method | Confidence Level | VaR (%) | VaR (₹) |
|---------|-----------------|---------|---------|
| Historical Simulation | 95% | -2.03% | ₹64 |
| Historical Simulation | 99% | -3.64% | ₹115 |
| Monte Carlo Simulation | 95% | -4.11% | ₹130 |
| Monte Carlo Simulation | 99% | -4.58% | ₹145 |

## Key Observations
- Monte Carlo VaR produced more conservative risk estimates than Historical Simulation.
- Only 2 VaR breaches were observed during the backtesting period versus 12.25 expected exceptions at the 95% confidence level.
- The model demonstrated strong downside-risk coverage during a period in which TCS declined approximately 22%.

## Tools Used
- Microsoft Excel
- Historical Simulation VaR
- Monte Carlo Simulation
- Kupiec POF Backtesting
- Statistical Analysis
- Skills Demonstrated
- Market Risk Measurement
- Value-at-Risk Modelling
- Quantitative Analysis
- Financial Modelling
- Statistical Analysis
- Model Validation
- Risk Reporting
- FRM Concepts Applied
- Value-at-Risk (VaR)
- Historical Simulation
- Monte Carlo Simulation
- Backtesting and Model Validation
- Tail Risk Measurement
- Confidence Intervals
- Market Risk Management

## Repository Contents
VaR_Calculation.xlsx — Excel model and calculations
Project Report.pdf — Detailed methodology and results
README.md — Project overview
## About

This project was independently developed as part of my preparation for a career in Market Risk, Credit Risk, and Financial Risk Management. It demonstrates practical application of FRM concepts using live market data, including risk estimation, model construction, and validation.

Qualifications: FRM Part I (2025) | FRM Part II Candidate
