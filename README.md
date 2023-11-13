# Crypto_Data_Automation_Project

### Crypto API Data Automation and Visualization
This Python project is designed to automate the retrieval of cryptocurrency data via an API and perform visualizations for analysis purposes.

### Objective
The code utilizes the CoinMarketCap API to pull cryptocurrency data and stores it in a CSV file. It then performs data visualization, focusing on the price changes over specific timeframes for various cryptocurrencies.

### Libraries Used
- **requests:** For making API requests.
- **json:** For handling JSON data.
- **pandas:** For data manipulation and analysis.
- **seaborn and matplotlib:** For data visualization.

### API Configuration
The script is set up to fetch data from the CoinMarketCap API using the provided API key. Ensure the API key is updated to access the desired API endpoints and perform API testing.

### Data Retrieval and Storage
The script continuously retrieves cryptocurrency data from the API at set intervals and appends it to a CSV file. The file 'API.csv' stores the collected data for analysis.

### Visualization and Analysis
Visualizes price changes over time for specific cryptocurrencies using Seaborn and Matplotlib.
Groups and analyzes cryptocurrency data based on the percentage change in different timeframes.

### Note
Ensure to replace the sample API key with your own and modify the file paths according to your directory structure.
