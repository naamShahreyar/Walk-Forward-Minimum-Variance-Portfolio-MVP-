# Walk-Forward-Minimum-Variance-Portfolio-MVP-

This project implements a **Walk-Forward Minimum Variance Portfolio** using Modern Portfolio Theory (MPT) across a diversified set of equity ETFs, including U.S. large-cap, tech, small-cap, developed, emerging markets, and a single stock (MSFT).

The strategy dynamically rebalances monthly using a rolling 1-year lookback window, selecting weights that minimize portfolio variance. Performance is benchmarked against Equal Weight and Buy & Hold strategies.

---

## Tickers Used

```python
tickers = ['SPY', 'QQQ', 'IWM', 'VEA', 'VWO', 'MSFT']
