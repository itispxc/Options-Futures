# BlackScholes-Greeks-Analyzer

This repository provides a Python implementation of the Black-Scholes model for pricing European call options and calculating the Greeks (Delta and Gamma). The project includes functions to compute the option price, Delta, and Gamma, and visualizes how these metrics vary with changes in the strike price and time to maturity.

## Overview

The Black-Scholes model is a fundamental concept in financial engineering, used for pricing European options and assessing risk factors associated with various market conditions. This project focuses on:
- Calculating the price of a European call option.
- Determining the Delta and Gamma of the option.
- Visualizing how these Greeks change as functions of strike price and maturity.

## Features

- **Black-Scholes Pricing**: Compute prices of European call options using the Black-Scholes formula.
- **Delta Calculation**: Calculate the Delta of an option, indicating how the price of an option is expected to move relative to a small change in the price of the underlying asset.
- **Gamma Calculation**: Calculate the Gamma of an option, reflecting the rate of change in Delta in response to movements in the underlying asset's price.
- **Visualization**: Plot the Greeks against varying strike prices and maturities to analyze their behavior under different scenarios.

## Requirements

This project uses Python 3.x. You'll need the following libraries:
- numpy
- scipy
- matplotlib



# BlackScholes-Options-Deltas

This repository contains Python code for calculating and visualizing the delta of European call and put options using the Black-Scholes model. It aims to provide financial students and professionals with tools to understand how the delta values of options change with different strike prices and under a fixed set of market conditions.

## Overview

The Black-Scholes model is crucial in financial theory for pricing options and understanding the sensitivity of option prices to various factors. This project demonstrates how to compute and graphically represent the deltas for European call and put options, providing insights into their behavior as the strike price varies.

## Features

- **Delta Calculation for Call and Put Options**: Calculate deltas using the Black-Scholes formula.
- **Visualization**: Graphically compare the deltas of call and put options across a range of strike prices.
- **Interactive Analysis**: Users can modify parameters such as the volatility, risk-free rate, and maturity to see how these changes affect the deltas.

## Requirements

This project requires Python 3.x and the following Python libraries:
- numpy
- scipy
- matplotlib



# DeltaHedge-Visualizer

This repository contains a Python script for visualizing the delta of a European call option across different stock prices and times to maturity using the Black-Scholes model. The visualization helps to understand the behavior of the option's delta as it approaches expiration.

## Features

- **Delta Calculation**: Computes the delta of a European call option using the Black-Scholes formula.
- **Visualization**: Plots delta across a range of stock prices and several time to maturity intervals.
- **Special Cases**: Handles the special case of delta at expiration, where it behaves as a step function.

## Requirements

This project uses Python 3.x and the following libraries:
- numpy
- matplotlib
- scipy
