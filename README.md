# Intermarket-Correlation-Study
The onset of the COVID pandemic in early 2020 gave rise to a brief period of high volatility, falling asset prices, and deep swings in currencies. 
In the bull market we have seen since March, the relationships between asset classes have appeared to differ from the period before COVID. 
My goal in this study is to examine intermarket relationships that have changed, if only temporarily, since March. 
Because I am only looking at correlations, my purpose is not to explain why these relationships have changed, 
but rather to explore previous instances of these changes, and how portfolio managers may adapt investment strategies this time.

There are three files available in this repository that were used for the project. All use Jupyter Notebooks, a platform for running python.

To run the code, you must install the yfinance module for python, pandas, and statsmodels.

'Study-Data.ipynb' is a program that scrapes yields from the FRED website and asset prices from Yahoo Finance. It creates the necessary CSV files for data analysis
'Data-Analysis.ipynb' is a program that runs OLS regressions and rolling correlations for key relationships.
'Historical-Analysis' uses historical data since 1985 to previous occurences of the trends found in 'Data-Analysis'. 
