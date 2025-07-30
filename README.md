# Stock Price Data Analysis using Python & Plotly

This short project is focused on exploratory data analysis (EDA) and visualization of stock price data using Python. For this analysis, we use TCS (Tata Consultancy Services) stock data and explore it using libraries like Pandas, Matplotlib, and Plotly.

# Inside the Notebook:

*Steps:*

1. **Data Loading & Inspection**  
   - Loaded CSV data using pandas
   - Checked for nulls and basic statistics

2. **Date Handling**  
   - Converted the date column to `datetime` format
   - Extracted day, month, year, and weekday features for deeper insights

3. **Visualizations Galore**  
   - Line plot of Closing Price over Time
   - Interactive Candlestick Chart using Plotly
   - Histogram of Daily Returns

4. **Returns Analysis**  
   - Calculated daily percentage returns
   - Analyzed distribution of returns and basic return stats
  
5. [View Jupyter Notebook](./Stock_Price_Data_Analysis.ipynb)

# Tech Stack

- Python 
- Pandas
- Numpy
- Matplotlib
- Plotly (for interactive visuals)

# Data Used

The dataset used is a CSV file named 
[TCS.csv](https://raw.githubusercontent.com/DatumLearning/Single_Stock_Analysis/main/TCS.csv), which contains historical stock price data for TCS including columns like `Open`, `High`, `Low`, `Close`, and `Date`.

# Output Highlights

- Trend of TCS Closing Prices over time
- Interactive candlestick chart to visualize market behavior
- Histogram of returns to observe volatility and distribution

# Behind the Analysis

- Time-series data handling and date manipulation
- Building interactive charts using Plotly
- Calculating and interpreting stock returns
- Building insightful visualizations with minimal code

# Open Notebook in colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DatumLearning/Single_Stock_Analysis/blob/main/Stock_Price_Data_Analysis.ipynb)




