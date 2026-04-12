# Aman Syed
**Quant Researcher · Derivatives Trader · Risk Engineer**

Building at the intersection of quantitative finance, systematic trading, and machine learning — from energy futures desks to crypto stat-arb, index rebalancing alpha, and counterparty risk modelling.

`Python` `C++` `KDB/Q` | `Stat-Arb` `Derivatives` `Factor Models` | `ML in Finance` `Time Series` `Stochastic Processes`

---

## About me

I'm a quant with experience spanning systematic energy futures trading (ICE/CME/NYMEX), index research at MSCI, power market price forecasting, and counterparty credit risk at State Street. My work lives at the edge of rigorous mathematical modelling and real market intuition — I care about strategies that work under live conditions, not just in backtests.

MSc Financial Mathematics · NCSU &nbsp;|&nbsp; BEng Computer Science · BITS Pilani &nbsp;|&nbsp; Boston, MA

---

## Featured Projects

### Crypto Statistical Arbitrage — Pairs Trading Engine
> End-to-end mean-reversion system across BTC, ETH, SOL, ADA, XRP, DOGE, DOT, AVAX, LINK via the Kraken REST API.

- Johansen + Engle-Granger dual cointegration test for pair selection
- Ornstein-Uhlenbeck half-life filter (3–30 day range) to screen for tradeable mean reversion
- Rolling 30-day z-score signals (entry ±2σ, exit ±0.5σ, stop ±3.5σ)
- Fractional Kelly position sizing at 25% with 7bps transaction costs
- Vectorized backtest with a 25% drawdown kill-switch

**Best pair — BTC/SOL:** Sharpe 3.7 · Max DD 0.3% · 4-month backtest window

`Python` `Kraken API` `Cointegration` `OU Process` `Kelly Criterion`

---

### Fixed Income — Interest Rate Modelling & Bond Pricing
> Vasicek, CIR, and Hull-White models calibrated via Monte Carlo simulation.

- Bond pricing via DCF on simulated short-rate paths
- Parameter calibration using SLSQP and MLE — fitting long-term mean, reversion speed, and term structure
- Benchmarked across multiple rate environments

`Python` `Monte Carlo` `Stochastic Calculus` `SLSQP` `MLE`

---

### Index Rebalancing Momentum — LSTM Alpha Capture *(Proprietary)*
> Short-term alpha from index constituent changes across Bloomberg, MSCI, Nasdaq, and S&P.

- LSTM model predicting post-rebalance price momentum from additions, deletions, and corporate events
- Systematic alpha capture strategy layered on top of predicted flows

`Python` `LSTM` `Index Events` `Bloomberg` `MSCI`

---

## Experience

| Firm | Role | Highlight |
|---|---|---|
| **State Street** | Portfolio Risk Manager | $600B Agency Lending book · CCAR/Basel III stress testing |
| **Clearway Energy** | Quant Modelling Intern | Jump-diffusion forecasting · BESS portfolio optimisation |
| **MSCI** | Quantitative Researcher | 70+ multi-asset strategies · MSCI Risk Control Indices |
| **Futures First** | Quant Trader (Oil & Gas) | $15MM+ intraday volume · Sharpe 2.8 · 80% hit rate |

---

## Currently working on

- Walk-forward validation on the crypto stat-arb pipeline
- Learning KDB/Q for tick-data workflows
- Exploring live execution and signal robustness under regime change

---

## Get in touch

Open to quant research, systematic trading, and front-office roles.  
📧 aman3599@gmail.com &nbsp;|&nbsp; [LinkedIn](#) &nbsp;|&nbsp; Boston, MA
