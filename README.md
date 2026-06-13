# Stock-Price-Analysis-Time-Series-Dashboard
A Python-based project for analyzing stock market data using time series techniques, including data preprocessing, visualization, seasonal decomposition, and moving averages, along with a dashboard for insights using power bi..
# overview
This project focuses on analyzing historical stock market data to understand price behavior, trends, and patterns over time. The main goal was to transform raw financial data into meaningful insights using data analysis techniques and time series methods.
The project combines data preprocessing, exploratory analysis, statistical modeling, and visualization to provide a clear understanding of how stock prices evolve.
In addition, a dashboard was used to present the results in an interactive and visual way, making the analysis easier to interpret.


## Data Preparation
I started by working with a large dataset containing daily stock prices for multiple companies. The data included key features such as opening price, closing price, highest price, lowest price, and trading volume.
To ensure accuracy and reliability:

I converted the date column into proper datetime format
Sorted the data chronologically
Removed missing values to avoid incorrect analysis

This step ensured the dataset was clean and ready for time series analysis.

## Exploratory Data Analysis (EDA)
After cleaning the data, I explored how stock prices behave over time.
I focused on:

Tracking how prices change year over year
Comparing different companies
Understanding volatility and general price movement

This helped build a strong foundation before applying advanced analysis.

## Time Series Analysis
Since stock prices are time-based data, I applied time series techniques to better understand underlying patterns.
Trend Analysis
I analyzed long-term movement in stock prices to identify whether prices are generally increasing, decreasing, or stable over time.
Moving Average
I used a 20-day moving average to smooth out short-term fluctuations.
This made it easier to observe the overall direction of the stock without noise.
Seasonal Decomposition
I broke down the time series into three components:

Trend → long-term direction
Seasonality → repeating patterns over time
Residual (noise) → random variations

This helped uncover hidden patterns that are not obvious from raw data.

## Dashboard Development
To make the analysis more interactive and user-friendly, I created a dashboard that summarizes the key findings.
The dashboard includes:

Stock price trends over time
Highest and lowest values
Average stock prices
Market share distribution across companies
Trading volume analysis

It also allows filtering by year, quarter, and stock symbol, making it easy to explore different perspectives.

## Key Insights
From the analysis, several important observations were made:

 Stock prices generally follow long-term trends with short-term fluctuations
 Moving averages help clearly reveal overall price direction
 Seasonal patterns exist in stock data, influenced by market cycles
 A small number of companies dominate market share
 Trading volume often correlates with price movements


## Conclusion
This project demonstrates how raw financial data can be transformed into meaningful insights using data analysis and time series techniques.
It highlights the importance of:

Data cleaning and preparation
Visualization for understanding trends
Statistical methods for deeper analysis

The dashboard further enhances the project by presenting results in a clear and interactive way.
