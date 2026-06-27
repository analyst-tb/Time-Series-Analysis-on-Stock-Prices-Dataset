# 📈 Time Series Analysis on Stock Prices Dataset

## 📖 Project Overview

This project demonstrates **Time Series Analysis** on a historical stock prices dataset using Python. The objective was to analyze stock price movements over time, identify trends and seasonal patterns, and apply smoothing techniques to better understand the behavior of the data.

---

## 🎯 Objectives

* Load and inspect the stock prices dataset.
* Convert the date column to datetime format.
* Set the date column as the index for time series analysis.
* Plot the stock closing prices over time.
* Apply moving average smoothing to identify long-term trends.
* Decompose the time series into trend, seasonality, and residual components using `statsmodels`.
* Interpret the results and identify key patterns in the stock prices.

---

## 📂 Dataset Features

The dataset contains the following columns:

| Column | Description             |
| ------ | ----------------------- |
| Symbol | Stock ticker symbol     |
| Date   | Trading date            |
| Open   | Opening stock price     |
| High   | Highest stock price     |
| Low    | Lowest stock price      |
| Close  | Closing stock price     |
| Volume | Number of shares traded |

---

## 🛠️ Tools & Libraries

* Python
* Pandas
* Matplotlib
* Statsmodels

---

## 📊 Project Workflow

### 1. Data Loading

Imported the dataset into a Pandas DataFrame and inspected its structure.

### 2. Data Preparation

* Cleaned column names.
* Converted the **Date** column to datetime format.
* Set the date column as the DataFrame index.

### 3. Time Series Visualization

Plotted the stock closing prices over time to identify overall trends and fluctuations.

### 4. Moving Average Smoothing

Calculated a **30-day moving average** to smooth short-term price fluctuations and reveal the long-term trend.

### 5. Seasonal Decomposition

Used the `seasonal_decompose()` function from **statsmodels** to separate the time series into:

* Trend
* Seasonal
* Residual

---

## 📈 Results

The analysis revealed:

* Overall trends in stock closing prices.
* Short-term fluctuations smoothed using the moving average.
* Seasonal patterns and random variations through time series decomposition.

---

## 📚 Skills Demonstrated

* Time Series Analysis
* Data Preprocessing
* Data Visualization
* Moving Average Smoothing
* Seasonal Decomposition
* Python for Data Analysis

This format is professional, easy to read, and suitable for showcasing your project to recruiters, internship supervisors, and potential employers on GitHub.
# Time-Series-Analysis-on-Stock-Prices-Dataset
