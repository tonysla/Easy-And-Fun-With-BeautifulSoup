### README is still work in progress

# Easy And Fun With BeautifulSoup.   

Web scraping Yahoo Finance page to collect stock data.

## Packages Used
  - pandas
  - datetime
  - urllib.request
  - bs4 (BeautifulSoup)
  
## About the Files. 
  - symbols.ipynb
    - The symbols.ipynb file writes the stock symbols as .csv and .txt files. 
  - df_symbols.csv
    - The df_symbols.csv file it will be used to pass stock symbols to the provided URL. 
  - symbols_file.txt
    - Choose 'symbols_file.txt' symbol data instead of the 'df_symbols.csv' if you so wish.
  - yahoo_stock_data.ipynb
    - This is the main file that will call the symbol data and use them to collect the stock data from Yahoo Finance page. 
  - stock_data_yahoo_Apr_28_2020.csv
    - This is the csv file with all the stock data collected from the 'yahoo_stock_data.ipynb' file. 
