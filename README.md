# Lyonn Lie

Finance and Business Analytics student at I-Shou University, working towards quantitative
and markets roles in banking and asset management. The six repositories below are
self-contained studies in pricing, risk, market microstructure and empirical asset pricing.

[LinkedIn](https://linkedin.com/in/lyonn-lie/) · [lyonnfl@gmail.com](mailto:lyonnfl@gmail.com)

## Projects

| Project | What it is | Stack | Headline result |
|---|---|---|---|
| [ipo_underpricing_model](https://github.com/leeyawnnn/ipo_underpricing_model) | IPO first-day returns vs. prospectus tone | Python · LightGBM | No model beats a constant out-of-sample |
| [fixed_income_engine](https://github.com/leeyawnnn/fixed_income_engine) | Curve bootstrapping, swaps, key-rate risk | C++20 · Eigen | Reprices all 13 inputs to 1.8×10⁻¹¹ bp |
| [high_frequency_trading_engine](https://github.com/leeyawnnn/high_frequency_trading_engine) | Feed handler, book, strategy, risk gate | C++20 · ITCH 5.0 | p50 1,215 ns, 400,000 msg/s (synthetic feed) |
| [risk_management_system](https://github.com/leeyawnnn/risk_management_system) | Multi-asset VaR, ES, regulatory backtests | C++20 · Eigen · FRED | Passes Kupiec, fails Christoffersen (p=0.0001) |
| [options_pricing_engine](https://github.com/leeyawnnn/options_pricing_engine) | European and American options, three ways | C++20 · GoogleTest | Three independent methods, cross-checked |
| [earnings_surprise_analyzer](https://github.com/leeyawnnn/earnings_surprise_analyzer) | Post-earnings drift, with a costed backtest | Python · pandas | +0.78 pp drift, days 1–20; break-even 11 bp |

## How I build

I am a finance student, not a software engineer. I build these projects with AI coding
agents; my part is choosing the problem, specifying the method, checking the results
against theory and real data, and writing up what the numbers do and do not show. Every
repository runs its tests in CI on each push, and where a result is null or negative it
is the headline rather than a footnote — three of the six above lead with one.

## Tools

- **Languages** — C++20, Python
- **Libraries** — Eigen, pandas, NumPy, SciPy, statsmodels, scikit-learn, LightGBM, SHAP, matplotlib
- **Build and test** — CMake, GitHub Actions, Catch2, GoogleTest, pytest, ASan/UBSan/TSan, clang-tidy, ruff, mypy
- **Data** — SEC EDGAR, US Treasury CMT, FRED, Yahoo Finance via yfinance, Kenneth French Data Library
- **Outside the repositories** — Excel financial modelling (DCF, comps, LBO), Bloomberg/Refinitiv, TradingView, IBKR

## Currently

Teaching assistant at I-Shou University.
