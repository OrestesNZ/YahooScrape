# Yahoo Financial Data Scraper and Dashboard

This script scrapes financial data from Yahoo Finance and creates two separate spreadsheets: one for financial statements (income statement, balance sheet, cash flow) and one for stock closing prices. It then displays the data on a Dash dashboard.

## Features

- Scrapes financial data from Yahoo Finance
- Creates separate spreadsheets for financial statements and stock closing prices
- Displays financial data on a Dash dashboard
- Allows selection of annual or quarterly data

## Installation

1. Clone the repository:

2. Install the required Python libraries:

3. Run the script:

## Usage

- Run the script and wait for it to scrape financial data and create spreadsheets.
- Open the Dash dashboard in a web browser by navigating to http://127.0.0.1:8050/.
- Explore the financial data using the interactive dashboard.

## Customization

- Modify the `ticker` variable to specify the stock ticker symbol you want to scrape data for.
- Choose the desired timeframe ('Annual' or 'Quarterly') by adjusting the `timeframe` argument in the `fetch_financial_data()` function call.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

