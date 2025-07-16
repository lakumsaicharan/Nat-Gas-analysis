# Nat-Gas-analysis
# Natural Gas Price Analysis

This project analyzes historical natural gas prices and provides an estimate for any date, including extrapolation for one additional year using a seasonal pattern.

## Files
- `nat_gas_analysis.ipynb`: Jupyter Notebook with full analysis and functions.
- `Nat_Gas.csv`: Monthly natural gas price data.

## How it works
- Loads and visualizes historical prices.
- Allows estimating prices for any date via interpolation.
- Extrapolates future prices by repeating last year's seasonal pattern.
- Plots full price history and highlights estimated points.

## Usage
Run the notebook and call `estimate("YYYY-MM-DD")` to get the price for any date.
