# Stock Comparison Tool

## Project Goal
I want to make it easier to compare stocks rather than just looking at current prices. This project will use historical price data to show how two stocks performed over the same period and how much their prices fluctuated.

## MVP
The first version will let users select two stocks and compare their percentage returns, volatility, and largest percentage drops from a previous peak. Results will appear side by side in a table with short explanations of each metric.

The app will read local CSV files, check for invalid data, and use matching dates for both stocks. If there isn't enough data to use, it will display an error message.

## Future Plans
After the basic comparison app work, I would like to add:
-Charts showing historical prices.
-An option to choose a specific date range.
-Automatic price updates through a stock API

## Tech Stack
-Python for processing stock data and for calculating metrics.
-Flask for handling user selection and displaying results of comparisons.
-HTML and CSS for selecting stocks, pages, and comparison tables.
-Python's built-in csv module and statistics module for reading data and performing calculations.
-Git and GitHub will be used for version control and documentation.
-Local CSV files will be used for the data rather than a live API for the MVP.

## Build Plan
1. Set up the GitHub repository, folders for project, python envioronment, and README.
2. Create basic Flask application and confirm homepage opens locally.
3. Find and verify historical stock data and add CSV files for a small sample selection of stocks. Document the source and file format.
4. Read stock data from CSV files and check for invalid or missing values. Use matching dates to compare two stocks over the same period.
5. Implement calculations like percentage return, volatility, etc., and check small sample results against hand calculations.
6. Build HTML form with two stock selectors and use the selections of stocks for the comparison calculations.
7. Display results in a use friendly comparison table with brief explanations of what each metric is.
8. Test the complete platform workflow and update the README with instructions on setup and usage.

## Current Status
The project is currently in the planning stage. I still need to verify the historical data source before starting implementation. This tool will compare past performance, not predict future stock prices.

## Planning Documents
- [Eisenhower Matrix](Eisenhower-Matrix.pdf)
- [System Diagram](System-Diagram.png)
- [Editable System Diagram](System-Diagram.drawio)
