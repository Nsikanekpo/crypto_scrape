CoinMarketCap Web Scraping Project
This project scrapes cryptocurrency data from CoinMarketCap using Python. It retrieves the following details for each cryptocurrency:

Name
Price
Market Cap
Volume (24h)
Circulating Supply
The data is processed, cleaned, and stored in a Pandas DataFrame. Additionally, a timestamp is added to each entry to track when the data was scraped.

The project uses the following libraries:

requests: For sending HTTP requests to fetch the CoinMarketCap webpage.
BeautifulSoup: For parsing and extracting the table data from the HTML.
pandas: For storing and manipulating the scraped data.
datetime: For adding a timestamp to each entry with the date and time of scraping.
The data is saved into a CSV file (coinmarketcap_with_time.csv), which includes the scraped information along with the timestamp.
