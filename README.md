# Time-Series

# Overview

This assignment is a time series analysis. The notebook analyzes time series data, examines stationarity and explores potential seasonality. The analysis includes :

1. Visualization of time series data.

2. Augmented Dickey-Fuller (ADF) test for stationarity.

3. Interpretation of statistical results.

# Dataset

The dataset contains time series data related to employment statistics. The dataset is analyzed to determine stationarity and assess the impact of external factors such as COVID-19 on the trends.

# Prerequisites

To run this project, we would need the following libraries:

1. pandas

2. numpy

3. matplotlib

4. seaborn

5. statsmodel

# Usage

1. Load the dataset and visualize the time series data.

2. Observe overall trends and seasonal patterns.

3. Conduct an Augmented Dickey-Fuller (ADF) test to check for stationarity.

4. Intepret the results:

    1. Test Statistics = 0.307
  
    2. p-value = 0.978
  
    3. Critical Values = { -3.447 (1%), -2.869 (5%), -2.571 (10%) }
  
    4. Conclusion = The high p-value suggests that the time series is not stationary.

# Interpretation

1. The time series data exhibits fluctuations but does not show immediate trends.

2. There is potential seasonality in the data.

3. The COVID-19 pandemic might have affected the time series data.

4. The ADF test results indicate that differencing or transformation might be required to make the series stationary.
