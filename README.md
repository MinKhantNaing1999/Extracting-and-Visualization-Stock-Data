# Tesla Stock and Revenue Visualization

## Description
This project visualizes Tesla stock prices and quarterly revenue.  
The graph compares Tesla's stock price trends with the company's revenue over time.

## Data Sources
- Tesla stock data: Obtained using the `yfinance` library.
- Tesla revenue data: Extracted from HTML tables provided in the IBM Skills Network lab.

## Visualization
- The graph shows Tesla stock prices on the primary Y-axis and quarterly revenue on the secondary Y-axis.
- Time period: Data is displayed up to June 2021.
- The purpose of the visualization is to see how Tesla's revenue correlates with its stock price.

## Usage
- Ensure you have Python and necessary libraries installed (`pandas`, `matplotlib`, `yfinance`, `BeautifulSoup`).
- Run the `make_graph(tesla_data, tesla_revenue, 'Tesla')` function to generate the graph.

## Notes
- Revenue values are cleaned and converted to numeric format for plotting.
- Stock data is obtained directly from Yahoo Finance using the `yfinance` API.
