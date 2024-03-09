# Timeseries Analysis
## Dynamic Stock Data Analysis and Reporting Web Application
### Stock Data | Exploratory DataAnalysis | Flask Web Application

Welcome to my GitHub repository for the Flask-based Stock Data Analysis Web Application. This web app leverages the yfinance library to fetch historical stock data based on user inputs, including the stock symbol, data aggregation interval, and the desired date range for analysis. It is designed to provide users with a quick and easy way to perform exploratory data analysis (EDA) on stock data directly from their web browser.

## How to use this application?

*  This app conains a html page where Stock details, Start_date, End_date and Aggregation interval have to be specified.
*  On clicking submit button, the detailed EDA of the chosen stock is displayed.


## How to run this application?

*  This application contains an ipynb notebook.

*  Install packages as specified in the notebook.
  
*  Run each cell according to the comments specified in the notebook and open the local host page

  **Home Page:** http://127.0.0.1:5000/

  **EDA Page:** http://127.0.0.1:5000/fetch_stock_data?stock_symbol=AAPL&agg=1mo&start_date=2020-01-01&end_date=2023-01-31 

I tested this code in local Jupyter Environment in localhost. Hence, I recommend you to install anaconda and try the code in jupyter notebook/ jupyter lab.

