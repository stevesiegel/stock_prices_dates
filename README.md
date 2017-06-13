# stock_prices_dates

Start of integrating kevinidea with Read_and_plot_IBM_prices.py

Integrated kevinidea with Read_and_plot_IBM_Prices.py
Used quantl because of problems with using Yahoo.  Hoping Yahoo function returns.
Commented out several commands so that each function could be tested step by step
Read_and_plot_IBM_Prices_quantl.py is not named correctly, since it accepts any ticker symbol, not just IBM
Script is now able to accept any stock symbol and successfully download stock table into tmp folder
Problem now is that script is expecting an output to be displayed, so error message received after stock ticker symbol entered
I am currently working on way to stop error message and as a first step display graph in command window.  Later need to use HTML to plot.
Dates are temporily set for the last 90 days
Initially, I would like to have the script plot stock prices for the last 90 days for the ticker symbol entered
After stock prices ploted, other stock statistics will be added



