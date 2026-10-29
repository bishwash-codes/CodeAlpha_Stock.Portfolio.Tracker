# CodeAlpha Stock Portfolio Tracker

A simple command-line Python program that calculates the total value of a stock portfolio from stock names and quantities entered by the user.

Built as **Task** of the **CodeAlpha Python Programming Internship** (November 2026).

## Features

- Takes stock names and quantities as user input
- Looks up prices from a hardcoded dictionary (no API or internet required)
- Calculates the value of each holding and the total investment
- Displays a summary of the portfolio

## Built With

- Python 3
- Standard library only (no external packages to install)

## Concepts Used

- Dictionaries
- Input / output
- Basic arithmetic


## How It Works

1. A dictionary stores the price of each supported stock:

   ```python
   stock_prices = {"AAPL": 180, "TSLA": 250}
   ```

2. The user enters a stock name and a quantity.
3. The program multiplies quantity by price and adds it to the running total.
4. When the user is done, it prints each holding and the total investment value, then saves the result to a file.

## How to Run

1. Make sure Python 3 is installed:

   ```
   python --version
   ```

2. Clone the repository:

   ```
   git clone https://github.com/bishwash-codes/CodeAlpha_Stock.Portfolio.Tracker.git
   cd CodeAlpha_Stock.Portfolio.Tracker
   ```

3. Run the program:

   ```
   python portfolio.py
   ```

## Example Output

```
Enter stock name: AAPL
Enter quantity: 10
Enter stock name: TSLA
Enter quantity: 5

--- Portfolio Summary ---
AAPL: 10 x 180 = 1800
TSLA: 5 x 250 = 1250
Total investment: 3050
```

## Project Structure

```
CodeAlpha_StockPortfolioTracker/
├── portfolio.py
├── README.md
└── .gitignore
```

## Limitations

- Prices are hardcoded and do not update with the real market.
- Only the stocks listed in the dictionary are supported.

## Author

**Bishwash Poudel**
GitHub: [bishwash-codes](https://github.com/bishwash-codes)

## Acknowledgement

Completed as part of the Python Programming Internship at [CodeAlpha](https://www.codealpha.tech).