# Cryptocurrency Data Analysis and Visualization

This project fetches, processes, and analyzes cryptocurrency data using the CoinGecko API. It includes functionalities for obtaining current and historical data, transforming it into a usable format, and visualizing trends using Python libraries like `pandas` and `matplotlib`.

## Features
**Fetch Current Cryptocurrency Data**: Retrieve real-time market data for specified cryptocurrencies using the CoinGecko API.

**Fetch Historical Data**: Obtain historical price data for a specific cryptocurrency over a defined period.

**Data Processing**: Convert JSON data to pandas DataFrames for easy manipulation. Clean and transform data for improved usability.

**Data Visualization**: Create bar and line charts for current and historical prices. Calculate and display moving averages and Bollinger Bands.

**Portfolio Value Calculation**: Compute the total value of a cryptocurrency portfolio based on current prices.

**Error Handling**: Implement retry mechanisms and error management for API requests.

**Correlation Analysis**: Analyze correlations between cryptocurrencies to identify relationships.

**Notifications**: Send alerts when specific conditions are met (e.g., Bitcoin price crosses a threshold).

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/crypto-analysis.git
   cd crypto-analysis
2. **Install Required Libraries:**
   ```bash
   pip install requests pandas matplotlib

## Acknowledgements
- CoinGecko API for cryptocurrency data.
- Python libraries: `requests`, `pandas`, and `matplotlib`.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
