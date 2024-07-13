# National_Stock_Exchange_ANALYSIS

# Stock Price Anomaly Detection and Analysis

This repository contains code and data for analyzing stock price trends, performing time series decomposition, correlation analysis, and detecting anomalies in stock prices. The analysis is performed using Python and various libraries including Pandas, Matplotlib, Seaborn, and Scipy.

## Table of Contents

- [Data Preprocessing and Cleaning](#data-preprocessing-and-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Correlation Analysis](#correlation-analysis)
- [Time Series Decomposition](#time-series-decomposition)
- [Anomaly Detection](#anomaly-detection)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
## Data Preprocessing and Cleaning

1. **Load the Dataset**: The dataset is loaded from a CSV file.
2. **Handle Missing Values**: Missing values are handled using forward fill and backward fill methods.
3. **Subset and Clean Data**: The first 10 stocks with the least number of missing values are selected. Rows with missing values are dropped, and the 'Date' column is converted to datetime format and set as the index.

## Exploratory Data Analysis

1. **Statistical Analysis**: Basic statistical analysis is performed on stock prices and volumes.
2. **Visualization**: The price trends of the first 10 stocks are visualized using line plots.

## Correlation Analysis

1. **Correlation Matrix**: A correlation matrix of stock returns is created.
2. **Most Correlated Pairs**: The most correlated pairs of stocks are identified and displayed.
3. **Heatmap**: Correlations are visualized using a heatmap for better understanding.

## Time Series Decomposition

1. **Choose Stock**: A single stock is chosen for time series decomposition.
2. **Decompose**: The time series is decomposed into trend, seasonality, and residual components.
3. **Visualization**: The components are visualized for better understanding.

## Anomaly Detection

1. **Method Development**: A method to detect anomalous price movements is developed using Z-scores.
2. **Identify Anomalies**: Anomalies are identified based on a threshold Z-score.
3. **Visualize Anomalies**: Anomalies are visualized separately and highlighted on the stock price time series.
4. **Investigate Anomalies**: Possible reasons for anomalies are investigated and explained.

## Installation

To use this repository, you need to have Python and the following libraries installed:

- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scipy
- Statsmodels

## Usage

git clone https://github.com/abhitt/National_Stock_Exchange_ANALYSIS.git
cd stock-anomaly-detection

## Result
  
Exploratory Data Analysis: Line plots of the first 10 stocks' price trends.
Correlation Analysis: Heatmap of the correlation matrix and most correlated pairs.
Time Series Decomposition: Visualization of trend, seasonality, and residual components.
Anomaly Detection: Plots highlighting the top 5 anomalies and their possible reasons.

