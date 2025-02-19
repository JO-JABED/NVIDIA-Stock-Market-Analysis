Here are business analysis questions that you can solve in your Jupyter Notebook using Python:
________________________________________
📌 Stock Performance & Trends
1️. What is the overall trend of NVIDIA’s stock price over the last 5 years? (Use line charts and moving averages)
2️. What were the highest and lowest closing prices in the dataset? (Use min/max functions)
3️. What is the average monthly return of NVIDIA’s stock? (Use groupby with resampling)
4️. Is there a pattern in stock performance before and after earnings announcements? (Check dates & compare returns)
________________________________________
📌 Volatility & Risk Analysis
5. What is the standard deviation of daily returns, and how volatile is NVIDIA’s stock? (Use .pct _change() and .std())
6. How often does NVIDIA experience extreme price swings? (Detect outliers using boxplots or Z-score)
7️. What are the biggest one-day gains and losses in stock history? (Sort daily returns to find peaks and drops)
________________________________________
📌 Trading Insights & Investment Strategy
8️. Does a high trading volume indicate a major price movement? (Check correlation between volume & returns)
9️. What is the best time of year to invest in NVIDIA stock based on historical returns? (Analyze seasonal trends using .groupby())
10.  Can a Simple Moving Average (SMA) crossover strategy help identify buy/sell signals? (Implement 50-day & 200-day SMA strategy)
________________________________________
📌 External Factors & Market Impact
1️1. How does NVIDIA’s stock correlate with major indices like NASDAQ or S&P 500? (Use .corr() on stock data)
1️2. How did NVIDIA’s stock react to major news events (e.g., AI breakthroughs, acquisitions)? (Compare price movements on key dates)
1️3.What effect did the global chip shortage have on NVIDIA’s stock? (Analyze stock price during supply chain disruptions)
________________________________________

Basic Questions:
1.	What is the total number of records in the dataset?
2.	What is the date range covered in the dataset (earliest and latest date)?
3.	What are the column names and their data types?
4.	What is the highest and lowest closing price in the dataset?
5.	How many missing values exist in each column?

Intermediate Questions:
6.	What is the moving average of the closing price for a 7-day and 30-day window?
7.	Identify the top 5 highest trading volume days.
8.	Plot the closing price trend over time.
9.	Calculate the daily return percentage and plot the histogram of returns.
10.	Determine the month with the highest average closing price.

Advanced Questions:
11.	Identify and visualize trends using a rolling mean and Bollinger Bands.
12.	Calculate and plot the correlation between trading volume and price movements.
13.	Implement a simple moving average crossover strategy (e.g., compare 50-day and 200-day moving averages).
14.	Detect outliers in stock prices using the IQR method or Z-score.
15.	Perform a time series decomposition to analyze trends, seasonality, and residuals.


