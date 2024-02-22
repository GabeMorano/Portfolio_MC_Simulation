# Portfolio Monte Carlo Simulation

This repository compares Monte Carlo Simulations between different weight allocations among portfolios and use this analysis to create an ideal, custom porfolio.

## Objective

The objective of this project is to:

  1. Read in and clean portfolio data
  2. Determine the gains/losses over a time period
  3. Build and evaluate a custome portfolio

## Methods

This project focuses on reading, organizing and manipulating dataframes retrieved using an Alpaca API using Pandas. Quantitative analysis is conducted to calculate the risk metrics and performance of each portfolio. Daily returns are used to calculate the Sharpe ratios for each portfolio.

Then, a custom portfolio is build and compared to the given portfolios and the S&P500. This new porfolio is built from a combination of the previous portfolios' assets and optimized for the customer's investment goals and risk tolerance. The future value of this custom portfolio is then projected using a Monte Carlo Simulation.

## Goal

The goal of this project is the determine which assets in the given portfolios are performing best across returns, risk, Sharpe ratios, and volatility. Then, a custom portfolio is built to optimize performance between these given variables.
