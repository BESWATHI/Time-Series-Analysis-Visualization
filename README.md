-- # Time-Series-Analysis-Visualization
This project involves time series analysis and visualization of historical stock data using both Python and Tableau. The dataset includes daily stock prices with columns such as Date, Open, High, Low, Close, Volume, and Adjusted Close.


-- **Files Included**

**stock_data.csv:** Raw dataset with daily Open, High, Low, Close, and Volume data

**Time Series Analysis in Python.ipynb:** Jupyter notebook performing data analysis, cleaning, resampling, and visualizations using libraries like Pandas, Seaborn, Matplotlib, and Statsmodels

**Tableau Dashboard Screenshot:** Final interactive dashboard built in Tableau Public


-- **Technologies Used**

**Python:** Pandas, Seaborn, Matplotlib, Statsmodels

**Tableau:** For interactive, comparative visual dashboards

**Jupyter Notebook:** For time series scripting and plots


-- **Key Visualizations
Python (Jupyter Notebook)**

Line plots of High prices

Monthly resampling to observe long-term trends

Autocorrelation plot to detect seasonality

Augmented Dickey-Fuller (ADF) test for stationarity

Differencing and Moving Average for smoothing noisy data


**Tableau Dashboard**

Line chart of Close Price over Time

Moving Average of Close Price

Dual-axis chart comparing Close Price vs Volume

Year-wise Daily Volume bar chart

Interactive filters for time range selection


-- Insights

Identified long-term upward trends in closing price

Observed declining volume over years

Moving averages helped smooth short-term price fluctuations

ADF and differencing confirmed non-stationarity in the High column

-- What I Learned

Fundamentals of time series data (trend, seasonality, noise, stationarity)

How to visually compare multiple metrics (Close vs Volume)

Creating dynamic dashboards using Tableau

Smoothing, differencing, and testing for stationarity in Python



