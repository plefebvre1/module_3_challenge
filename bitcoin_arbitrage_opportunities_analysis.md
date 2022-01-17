## Bitcoin Arbitrage Opportunities

---

Historical trade data for two Bitcoin exchanges, Bitstamp and Coinbase, was used to determine if arbitrage opportunities exist for Bitcoin. The given data was collected and filtered down to show only close prices from 2018 Q1 for both exchanges. From there, smaller and smaller date increments were reviewed until we took a deep dive into three specific dates at varying points in the overall timeframe: Jan 10, Feb 27 and Mar 17.

For each date, arbitrage spreads were calculated by subtracting the lower valued exchange price fromt the higher valued exchange price. This was determined by looking at summary statistics for each daily dataset.

THe next step in the analysis was to determine if there were any profitable arbitrage opportunities. First the daily datasets were filtered down to just timestamps where the arbitrage spreads were positive. Jan 10 had 811/1441 timestamps that had positive arbitrage spreads, Feb 27 had 1325/1436 and Mar 17 had 950/1410. To compare across dates, these positive spreads were converted to return rates before conducting further analysis. A 1% minimum threshold was then set on the rates of return to account for any transaction feels incurred. Any arbitrage spread that had greater than 1% spread return was considered a profitable return and thus, an arbitrage opportunity to pursue. The total cummulative profit for each day was then calculated.

The final results:

>Jan 10, 2018: 14 profitable trades resulting in $2176.60 profit

>Feb 27, 2018: 0 profitable trades resulting in no profit

>Mar 17, 2018: 0 profitable trades resulting in no profit

Looking at the graph below for when arbitrage opportunities occured on Jan 10, the majority occured in the morning, just after the exchange would have opened. After the first few hours, the exchanges seemed to stabilize and remove opportunity for arbitrage profits.

