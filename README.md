##Utilizing quantatative analysis techniques with Python and Pandas, a portfolio performance test was ran across multiple areas: volatility, returns, risk, and Sharpe ratios. Using jupyter lab as an analysis notebook, different "whale" portfolios were compared. Using this analysis, we can create a custom portfolio of stocks and compare to the S&P 500 index. 

##Using Pandas, a CSV file was read in as a DataFrame.Data was cleaned. Dates were converted to a "DateTimeIndex." Null values were removed. Data types were converted as needed. S&P500 closing prices were converted to daily returns. 'Whale'

2. Detect and remove null values.

3. If any columns have dollar signs or characters other than numeric values, remove those characters and convert the data types as needed.

4. The whale portfolios and algorithmic portfolio CSV files contain daily returns, but the S&P 500 CSV file contains closing prices. Convert the S&P 500 closing prices to daily returns.

5. Join `Whale Returns`, `Algorithmic Returns`, and the `S&P 500 Returns` into a single DataFrame with columns for each portfolio's returns.
