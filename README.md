# Why do we bet on algorithmic trading?
We believe [technical analysis](https://en.wikipedia.org/wiki/Technical_analysis) could be an important factor to consider, when initiating a trade for a stock.

We can leverage charts available on different platforms, to look at various market technicals (sma, ema, rsi, and so) to initiate a trade upon receiving a buy/sell signal.
But, that is consuming and not scalable, when we want to do that for 'n' of number of instruments (stocks).

So, we turn our attention to automating our trades,
through algorithmic trading to achieve speed, consistency for executing various trading strategies efficiently and effectively.

# Why do we develop openTrading?
There must be numerous libraries and platforms out there to perform algorithmic trading and backtesting but each of them acts like a dependency to build a complete trading system
or developed using languages other than Java or their community is currently inactive.

So, the idea behind developing openTrading is to build a complete solution to achieve an end to end algorithmic trading system by leveraging the libraries and platforms out there but to not develop the aforesaid libraries or platforms and certainly to not reinvent the wheel!

# What does openTrading (v1.0) aims to achieve?
- read market data
- calculate market technicals
- persist market data
- replay market data
- form and execute trading strategies
- connect to a broker
- place trades on your trading account (virtual/real account)
- backtest strategies
- measure trading performance/drawdown
- sandbox

# Why do we prefer Java?
- We don't worry about millisecond lag in terms of system performance because execution of our strategies are not going to be that time sensitive.</br>
- We lean towards Java for its strongly statically typed nature and its robust features like collections, concurrency and its plethora of frameworks/strong communities.</br>
- Lastly, We have a solid development experience using Java. Thus, we want to use a language that we are pretty comfortable, so we can dig deep and understand what's going on under the hood, when a situation arises for debugging.
