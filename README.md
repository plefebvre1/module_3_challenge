# Bitcoin Arbitrage Analysis

Data from two Bitcoin exchanges, Bitstamp and Coinbase, was analyzed to determine if arbitrage opportunities exist. Analysis was done by 

>Collecting the data by importing data from two .csv files to a .ipynb file in Jupyter Lab to create dataframes in Pandas

>Preparing the data by cleaning missing and eroneous data to stage the final analysis

>Analyzing the data at a high level through summary statistics and visualizations before specific days were selected for deeper analysis to identify arbitrage opportunities

## Results

A report summary can be found in the [Analysis summary](https://github.com/plefebvre1/module_3_challenge/blob/main/bitcoin_arbitrage_opportunities_analysis.md) in the main repo. At a high level, only one of the three days returned arbitrage profits totaling $2177 with profitable trades occuring primarily at the start of the day as seen in the cumulative profits graph below.

![Jan10CumProfits](/Images/Jan_10_CummulativeProfits.png)

## Technologies

This project leverages python 3.7 with the following packages:

* [pandas](https://pandas.pydata.org/) - For financial data analysis tools

* [matplotlib](https://matplotlib.org/) - For data visualizations

## Contributors

Starter code for this app was provided by the GWU Fintech Bootcamp program. Updates to that code to fulfill the analysis were done by Peter Lefebvre (peter.c.lefebvre@gmail.com)

## License

MIT License
