# Forecasting Net Prophet

## Overview

This project aims to analyze MercadoLibre's financial and user data to help predict future trends and drive company growth. The primary goal is to determine if predicting Google search traffic can translate into successful stock trading strategies. The project involves preparing data, conducting analyses, and visualizing time series data.

## Repository Contents

- `forecasting_net_prophet.ipynb`: The main Jupyter notebook containing the entire analysis, data preparation, visualizations, and forecasts.
- `Data/`: Directory containing all the necessary data files for the analysis.

## Key Features

1. **Data Preparation**:
   - Loading and cleaning of hourly Google search traffic data and stock price data.
   - Slicing the data for specific time frames, such as May 2020, to analyze patterns related to financial events.

2. **Pattern Identification**:
   - Identification of unusual patterns in Google search traffic during specific months.
   - Calculation of total search traffic for specific months and comparison to monthly medians.

3. **Seasonality Analysis (Optional)**:
   - Grouping and visualization of search traffic data by day of the week and week of the year to identify seasonal trends.
   - Heatmap visualization to pinpoint times of high search activity.

4. **Correlation with Stock Prices (Optional)**:
   - Analysis of the relationship between Google search traffic and MercadoLibre's stock price.
   - Creation of additional columns for lagged search trends, stock volatility, and hourly stock returns to examine correlations.

5. **Prophet Forecasting Model**:
   - Implementation of a Prophet model to forecast hourly Google search traffic.
   - Visualization of forecasted search traffic and individual time series components (daily and weekly trends).

6. **Revenue Forecasting**:
   - Use of Prophet model to forecast future company revenue based on historical sales data.
   - Identification of seasonal patterns in revenue and prediction of total sales for the next quarter, including best- and worst-case scenarios.

## Instructions for Use

1. **Setup**:
   - Open the `forecasting_net_prophet.ipynb` notebook in a Jupyter environment or Google Colab.
   - Ensure all necessary libraries are installed by running the provided setup cells.

2. **Execution**:
   - Follow the steps in the notebook to execute the data preparation, analysis, and forecasting tasks.
   - Review the visualizations and forecasts generated in the notebook.

3. **Customization**:
   - Modify the data slicing parameters and visualization settings as needed to explore different aspects of the data.

## Conclusion

This project demonstrates the application of time series analysis and forecasting using Google search traffic and financial data. By identifying patterns and correlations, and building predictive models, the analysis provides valuable insights for driving growth at MercadoLibre.

---

© 2024 Forecasting Net Prophet. All Rights Reserved.
