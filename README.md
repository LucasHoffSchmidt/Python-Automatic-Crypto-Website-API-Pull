# Python Automatic Crypto Website API Pull
Pulls data about crypto currencies from coinmarketcap at set intervals. 

## Tools and technologies
- **Jupyter Notebook**
- **Python**
  - requests
  - json
  - pandas
  - matplotlib
  - seaborn

## Programming steps
- Import libraries
- Make automated API pull function
  - Setup connection to coinmarketcap API
  - Showed all requested rows and columns
  - Created a dataframe from the API json data
  - Created a date column in the end of the dataframe with the current time
  - Combined functionality into an API pull function and wrote the dataframe to a csv file
  - Ran the API pull function intermittently
- Use pulled data
  - Showed csv file as a dataframe
  - Showed the first 5 decimals of each value
  - Grouped the crypto currencies names together and limited columns to percent change in USD
  - Transformed the dataframe into a stack, turning the percent change columns into rows for each cryptocurrency
  - Transformed the stack back into a dataframe
  - Changed the dataframes column names and turned the percent change values into their short form
  - Made a category plot to show the percent change of each crypto currency over time
  - Made a lineplot to show the percent change of bitcoin over time

 ## Visuals
**Cryptocurrencies percent change over time**

![Catplot over cryptocurrencies percent change over time](catplot_percent_change_cryptocurrencies.png)

**Bitcoins percent change over time**

![Lineplot over bitcoins percent change over time](lineplot_percent_change_bitcoin.png)

 ## Code
 [Automatic Crypto Website API Pull](automating_crypto_website_api_pull.ipynb)
