# daytradingmethod
CryptoCoyns Day Trading Method

Copyright (c) 2017, Cryptocoyns.

Here are the day trading rules I use:

Keep emotion out of your trading, only trade off the charts, avoid FOMO (Fear of Missing Out).

Ignore FUD (Fear, Uncertainty and Doubt) in the market, just trust in the method and trade.

Keep informed, read the Crypto news from as many sources as you can. https://cryptopanic.com is a good source of the latest news.

Trade on coins that you don’t mind if they go up or down and can HODL (Hold On For Dear Life) if needs be.

Be disciplined and do not try other strategies mid way through, do not jump from strategy to strategy just stick to this strategy…it works!

Do the opposite of what everyone else is doing, so when everyone else is panic SELLing you are BUYing and vice versa. i.e. buy LOW sell HIGH

All Investment carries risk so only Trade with money you can afford to lose.

Charts:
Either use the free TraderView or a paid charting tool such as Coinigy

TraderView works but the free version doesn't allow you to save your settings so you have to redo your setup everyday.

Coinigy is my preference for day trading as it interfaces directly with the exchanges via API keys so you can trade directly off the chart. It also provides portfolio views across exchanges so you can see total holdings. i.e. Bittrex, Binance, etc.

Coinigy is a dedicated charting tool used by day traders. Coinigy can interface via API key to the Bittrex exchange and you can trade manually via the Coinigy charts rather than swapping back and forth between Coinigy and Bittrex all the time. So on Coinigy I am watching the charts to see if the parameters I mentioned on the Github post have been met. When they are I place a trade via the chart tools. The trade then appears on the Bittrex exchange. It can take a lot of time for the conditions to be met so you are always at your computer watching the charts. That's why I want to automate using PT to free me from having to watch the charts all day. I can and do set trades to run during the day on Coinigy but having an automated bot doing the same work is very appealing.

Indicators used:

- Two moving average exponential lines with colours chosen to stand out from background
- MACD histogram showing oscillation movement
- Volume (either scaled left or no scale depending on preference)
- RSI Stochastic's

Time interval on moving average lines:

- Pink average of last 13 candles on close price
- Blue average of last 34 candles on close price
- MACD by default shows 12,26 leave it as is
- RSI leave as is

Trading Rules:

1. Look for the lines to cross and wait for the breakouts;
2. BUY on the long red candles and SELL on the green candles;
3. If Pink (13) is below Blue (34) only BUY never sell;
4. Only BUY the big red candles that have separated from the rest and buy into the trade i.e. use DCA (with ANDERSON DOUBLING) to buy into the trade, buy 0.1 BTC each time it dips until fully separated and then buy larger amounts 0.5 BTC on the bottom;
5. The further the big red candle is from the Pink (13) line the better as it is likely to bounce back up so wait for it to separate fully;
6. When buying always have some BTC in reserve do not run out of BTC as long as the pink (13) remains below the Blue (34) keep buying the big red candles as they occur i.e. if you have 1 BTC to use then BUY 0.1 BTC every time it dips;
7. When the lines cross and the Pink (13) has gone above the Blue (34) then SELL taking some profits but keep some coin in reserve for potential future sales as it separates further;
8. Every time it peaks higher than the last time you sold then SELL again i.e. use DCA (with ANDERSON DOUBLING) to sell out of the trade, sell 0.1 BTC each time it dips until fully separated and then sell larger amounts 0.5 BTC at the peak;
9. MACD compliments the moving averages and is used when these cross; at that point look at the MACD histogram only and watch for the peaks at either end of the oscillation. Look for the longest peak in the oscillation and for the one following to be shorter. i.e. at peak of dip you would BUY, at peak of breakout you would SELL;
10. Volume also compliments the moving averages and is used to indicate the strength of the market i.e. low volume would indicate the trend down is going to continue, high volume indicates the trend upward will continue;
11. RSI also compliments the moving averages and provides an indication of the direction of the trend and if the cryptocurrency is oversold or undersold. It can also indicate if the trend is going to stay low or high as it travels sideways.

Always remember the following quotes:

How do you eat an elephant? One small bite at a time!

Start by doing what’s necessary; then do what’s possible; and suddenly you are doing the impossible.

------------------------------

I have now automated my day trading method using Profit Trailer an automated trading bot.

You can join our community on discord and get updates on CryptoCoyns Day Trading Method using this link: https://discord.gg/t8ymzAb

Your use of the CryptoCoyns Day Trading Method settings is subject to and indicates your acceptance of the license provide here:  https://github.com/cryptocoyns/daytradingmethod/blob/master/LICENSE
