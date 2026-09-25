# Portfolio-Optimization-Analysis

## Overview
This repository contains a quantitative finance project firstly developed in Matlab, then in Python, focusing on Modern Portfolio Theory and advanced portfolio optimization techniques. The project analyzes the behavior of different asset combinations (Amazon, Facebook, Apple) to construct efficient frontiers and determine optimal capital allocation under various constraints.

## Project Features
* **Efficient Frontiers Calculation**: Construction of the Markowitz efficient frontier for different pairs of assets (Amazon & Facebook vs. Facebook & Apple) and for the complete three-asset portfolio[cite: 1].
* **Minimum Variance Portfolio (MVP)**: Identification of the portfolio that minimizes risk for a given set of assets, highlighting the benefits of diversification[cite: 1].
* **Risk-Free Asset Integration**: Optimization of a portfolio containing three risky assets and one risk-free asset, utilizing a quadratic utility function to balance risk and expected return[cite: 1].
* **Exponential Utility Optimization**: Evaluation of investment choices using an exponential utility function with an absolute risk aversion coefficient, analyzing the impact of financial leverage[cite: 1].
* **Transaction Costs Penalty**: Determination of the optimal portfolio weights by maximizing a utility function penalized by transaction costs, demonstrating how transaction fees prevent extreme short selling and encourage a balanced, well-diversified allocation[cite: 1].

## Data Requirements
The original dataset (`Lab3-students.xlsx`) contains daily stock prices for Amazon, Facebook, and Apple. Due to academic/internal policy, the dataset is not included in this public repository. 
To run the notebook locally, place a compatible Excel file in a `data/` directory with the historical prices of the assets in a sheet formatted with the assets as columns.

## Technologies Used
* **Python 3**
* `numpy`: Linear algebra and matrix operations.
* `pandas`: Data manipulation and Excel parsing.
* `matplotlib`: Financial data visualization.
