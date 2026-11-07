# Strategy Research Notebooks

Research and backtest notebooks for the strategy directions described in [strategy-research-overview](https://github.com/weiyutp6/strategy-research-overview).

**Placeholder parameters.** Thresholds, windows, sizes and cut-offs are replaced with named constants set to illustrative values (the first cell of each notebook, where used). Outputs, results and data are removed. The notebooks show the method, not the settings used in live research.

| Notebook | Content |
|---|---|
| `corr_alpha.ipynb` | Pairs trading on the log ratio of two related assets: rolling z-score, AR(1) mean-reversion estimate, stacked entries, trade-level P&L and performance metrics, live z-score check. |
| `gold_B.ipynb` | Gold ETF against gold-miner spread with a volatility regime filter, reversal-based entries, and a vectorised backtest. |
| `0DTESellCallOptions.ipynb` | Short-dated call-selling backtest conditioned on volatility level and recent drawdown, with threshold tables. |
| `vix_spike.ipynb` | VIX spike detection and Black-Scholes backtests of put, put-spread and calendar-spread structures over spike episodes. |
| `vixspyNEAT.ipynb` | NEAT neuroevolution mapping VIX and index-ETF features to positions, with rolling GARCH volatility. |
| `ARCC_credit_cycle.ipynb` | High-yield minus investment-grade spread as a rolling z-score against a listed credit vehicle, plus SOFR futures curve convexity. |
| `multiasset_PnL_surface.ipynb` | P&L surface of a two-leg SPY and VIX position, and performance metrics. |
| `baseball.ipynb` | Win-probability and fair-price logic for baseball markets. |
| `2330vsTSM.ipynb`, `dividendfilter.ipynb`, `btcprice_dtd.ipynb`, `Kalshi_BTC.ipynb`, `american_odds.ipynb`, `gld_garch.ipynb`, `dumbdumdjoy.ipynb` | ADR-versus-local spread, dividend screen, BTC distance-to-strike pricing, odds conversion, GARCH on gold, and a moving-average chart. |

Price files and licensed data are not included. For research and education only. Not investment advice.
