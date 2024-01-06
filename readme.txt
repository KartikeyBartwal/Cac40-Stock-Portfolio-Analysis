# Cac40 Stock Portfolio Analysis

## Overview
This project, named "Cac40 Stock Portfolio Analysis," conducts a comprehensive analysis of a stock portfolio consisting of three major stocks listed in the CAC 40 index: BNP, MC, and TTE. The analysis involves various financial metrics and statistical techniques, including beta, time series analysis, portfolio value at risk, single stock value at risk, variance, correlation, and heatmap visualization.

## Data Sources
The stock data used for this analysis was obtained from Yahoo Finance. The data includes historical price information for the BNP, MC, and TTE stocks.

## Tools and Libraries Used
- **Python** for data processing and analysis.
- **Jupyter Notebook** for interactive analysis and visualization.
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn for data manipulation, analysis, and visualization.
- **Yahoo Finance API** for fetching historical stock price data.

## Analysis Performed
1. **Beta Calculation**: Calculated the beta values for the stocks to measure their volatility compared to the market index.
2. **Time Series Analysis**: Conducted a time series analysis to understand the trends, seasonality, and patterns in the stock prices over time.
3. **Portfolio Value at Risk (VaR)**: Determined the value at risk for the entire portfolio, considering the interrelationship between stocks.
4. **Single Stock Value at Risk**: Computed the value at risk for individual stocks in the portfolio.
5. **Variance Calculation**: Calculated the variance of stock returns to measure volatility.
6. **Correlation Analysis**: Studied the correlation between the stock prices to assess their interdependency.
7. **Heatmap Visualization**: Visualized the correlation matrix using a heatmap for easy interpretation.

## File Structure
- `data/`: Contains raw and processed data files.
- `notebooks/`: Jupyter notebooks for each analysis step.
- `images/`: Contains visualizations generated during the analysis.

## How to Use
1. **Clone the Repository**: Clone this repository to your local machine.
2. **Data Retrieval**: Ensure you have access to Yahoo Finance API or replace the existing data with your own historical stock price data.
3. **Open Notebooks**: Explore the analysis steps by opening the Jupyter notebooks in the `notebooks/` directory.
4. **Run the Code**: Execute the code cells in the notebooks to reproduce the analysis or modify them as needed.

## Conclusion
The analysis provides insights into the behavior and performance of the BNP, MC, and TTE stocks within the CAC 40 index. By understanding their volatility, trends, and correlations, it aids in making informed investment decisions or portfolio adjustments.
