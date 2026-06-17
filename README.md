# TradingView Pine Seeds — Delta Exchange Funding Rates

Live perpetual futures funding rates from [Delta Exchange India](https://india.delta.exchange).

Updated every 5 minutes by the [aibattle.in](https://aibattle.in) dashboard scheduler.

## Datasets

| Seed name | Description | Pine Script usage |
|-----------|-------------|-------------------|
| `BTCFUNDING` | BTC/USD perpetual funding rate | `request.seed("yellapun/tv-pine-seeds", "BTCFUNDING", "close")` |
| `ETHFUNDING` | ETH/USD perpetual funding rate | `request.seed("yellapun/tv-pine-seeds", "ETHFUNDING", "close")` |

## CSV format

`Date` is a Unix timestamp (seconds). `Open/High/Low/Close` all carry the funding rate value. `Volume` is always 0.

```
Date,Open,High,Low,Close,Volume
1781707051,0.005024,0.005024,0.005024,0.005024,0
```
