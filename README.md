# Daily-Bitcoin-profit-and-losses-from-2020-2021
This notebook shows how much The BTC-USD has gained or lost price over the span of 1 year, from 2020 to 2021:
 This is how the Cell works
    **Cell 2**: Imports necessary libraries - `yfinance` for downloading financial data, `numpy` for numerical operations, `pandas` for data manipulation, and `matplotlib` for plotting.

   2. **Cell 4**: Downloads daily BTC-USD price data for the year 2020 using `yfinance`, storing it in a dataframe with columns like Open, Close, High, Low, Volume.

       3. **Cell 6**: Calculates two new columns:
        - `Benefit`: The daily price change (Close price - Open price)
        - `Profit`: Categorizes each day as either "Profit" (if Benefit > 0) or "Loss" (if Benefit ≤ 0)

        4. **Cell 8**: Creates a line plot showing the Close price and daily Benefit over time, with proper formatting (title, labels, legend, grid).

         5. **Cell 10**: Displays the complete dataframe with all relevant columns (Open, Close, Benefit, Profit) for inspection, showing which days were profitable and by how much.

The overall workflow is: download data → calculate metrics → visualize trends → display detailed results.
