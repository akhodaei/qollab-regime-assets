# Qollab Regime Radar Assets

Public binary assets for the Qollab Regime Radar Playground.

## Files

- `regime_library_n12_lite_L8.npz` — n=12 lite L8 regime-reference asset for the v0 Qollab Playground app.
  As of 2026-06-02 this asset also bundles daily log returns for the seven
  Magnificent-7 tickers (AAPL, MSFT, GOOGL, AMZN, META, TSLA, NVDA) over
  2018-01-03 → 2026-06-01 in three arrays (`bundled_tickers`, `bundled_dates`,
  `bundled_returns`), so the in-browser playground runs without `yfinance`.

This repository was created by an AI agent (OpenHands) on behalf of akhodaei.
