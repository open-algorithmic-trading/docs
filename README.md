# Hello there. Welcome to Open Trading!

## Why do we bet on algorithmic trading?
We believe [technical analysis](https://en.wikipedia.org/wiki/Technical_analysis) could be an important factor to consider, when initiating a trade for a stock.

We can use charts available on different platforms, to look at various market technicals (sma, ema, rsi, and so on) to initiate a trade, upon receiving a buy/sell signal.
But, that is consuming and not scalable, when we want to do that for 'n' of number of instruments (Stocks).

So, we turn our attention to automating our trades, through algorithmic trading to achieve speed and consistency, for executing various trading strategies efficiently and effectively.

## Why do we develop Open Trading?
There must be numerous libraries and platforms out there, to perform algorithmic trading and back testing, but each of them acts like a dependency, to build a complete trading system or developed using languages other than Java or their community is currently inactive.

So, the reason behind developing Open Trading is to build a complete algorithmic trading system for Stocks and Options, by leveraging the libraries and platforms out there but to not develop the aforesaid libraries or platforms and certainly to not reinvent the wheel!

## What does Open Trading (v1.0) aims to achieve?
- Read market data
- Consume/calculate market technicals
- Persist market data
- Replay market data
- Form and execute trading strategies
- Connect to a broker
- Place trades (for Stocks and Options) on your trading account (virtual/real account)
- Back test strategies
- Measure trading performance/drawdown
- Sandbox

## Why do we prefer Java?
- We don't worry about time-sensitive lag in terms of system performance, because execution of our strategies are not going to be that time-sensitive.</br>
- We lean towards Java for its strongly, statically typed nature and its robust features like collections, multithreading model and its plethora of frameworks/strong communities.</br>
- Lastly, we have a solid development experience using Java. Thus, we want to use a language that we are pretty comfortable, so we can dig deep and understand what's going on under the hood, when things go south.

## What is the tech stack of Open Trading?
> **Now .**
- Java
- Groovy
- PostgreSQL
- Docker
- AWS
- Amazon S3
- Terraform
> **Future +**
- gRPC
- Redis
- MongoDB
- Apache Kafka
- Kubernetes
- UI frameworks

## Markets & Brokers
Open Trading is designed to be a generic and an extensible platform and so it is possible to extend it for any market/broker. That said, we target to extend the platform for following markets/brokers.
> **US**
  - Alpaca
  - TD Ameritrade
  - Tastyworks
> **India**
  - Zerodha

## How can I contribute to Open Trading?
We strongly believe in collective efforts and Open Trading would love to have contributors like you.</br>

Join us [@open-trading](https://join.slack.com/t/open-trading/shared_invite/zt-h486t1ue-1Pt9Ais587FLdvcWkZZUAg) on Slack. And let us build this Open Trading platform, for us, together!
