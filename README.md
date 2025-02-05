# Cryptocurrency Data Analysis and Visualization

This project is designed to fetch, process, and analyze cryptocurrency data using the CoinGecko API. It includes functionalities for obtaining current and historical data, processing this data into a usable format, and visualizing it using various analytical techniques. The project is implemented in Python and utilizes libraries such as `requests`, `pandas`, and `matplotlib`.

## Features

1. **Fetch Current Cryptocurrency Data:**
   - Retrieve current market data for specified cryptocurrencies using the CoinGecko API.

2. **Fetch Historical Data:**
   - Obtain historical price data for a specific cryptocurrency over a given time period.

3. **Data Processing:**
   - Convert JSON data to pandas DataFrames for easy manipulation and analysis.
   - Clean and transform the data for better usability.

4. **Data Visualization:**
   - Visualize current and historical cryptocurrency prices using bar and line charts.
   - Calculate and visualize moving averages and Bollinger Bands.

5. **Portfolio Value Calculation:**
   - Calculate the total value of a cryptocurrency portfolio based on current prices.

6. **Error Handling and Retry Mechanism:**
   - Implement error management and retry mechanisms for API requests to handle failures gracefully.

7. **Correlation Analysis:**
   - Analyze the correlation between different cryptocurrencies to understand their relationships.

8. **Notifications:**
   - Send notifications when certain conditions are met (e.g., Bitcoin price crosses a threshold).

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/crypto-analysis.git
   cd crypto-analysis
2. **Install Required Libraries:**
   ```bash
   pip install requests pandas matplotlib

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
- CoinGecko API for providing cryptocurrency data.
- Python libraries: requests, pandas, and matplotlib.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
