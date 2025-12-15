# Alternative-data-macro-signals-indian-equities
# Alternative Data & Macro-Fundamental Signal Research for Indian Equities

## Overview
This project explores the use of alternative data and macroeconomic indicators to construct economically interpretable signals for Indian equities, with a focus on the auto sector and Tata Motors as a case study.

The objective is not to build a production trading system, but to demonstrate a complete research pipeline covering:
- Alternative data sourcing and preprocessing
- Signal engineering with economic intuition
- Strategy diagnostics (risk, turnover, stability)
- Fundamental validation using regression models

The work was conducted as part of an industry-style research assessment.

---

## Data Sources
The project integrates multiple alternative and macro datasets:
- **Auto Industry Sales (Simulated)**: Monthly auto sales used as a proxy for demand cycles
- **RBI CPI Inflation (Official)**: Consumer Price Index data from RBI publications
- **RBI Policy Rates (Official)**: Repo rate changes reflecting monetary policy stance

Due to data-access constraints, **proxy return series** are used for illustrative strategy evaluation. Signal validity is assessed independently through economic reasoning and regression analysis.

---

## Methodology

### 1. Signal Construction
Two economically grounded signals are constructed:
- **Demand Signal**: Year-on-year growth in auto sales, capturing cyclical demand conditions
- **Monetary Signal**: Real interest rate (repo rate minus CPI inflation), capturing financing and policy tightness

Signals are normalized using historical z-scores and combined into a composite alpha signal.

---

### 2. Sector-Neutral Extension
To isolate sector-specific effects, a **sector-neutral framework** is implemented by subtracting a broad market proxy return from the auto-sector proxy return. This helps distinguish industry alpha from general market movements.

---

### 3. Lagged Macro Effects
Macro variables often impact equities with a delay. The project explicitly evaluates **1–3 month lagged macro features**, validating delayed transmission of policy and demand effects.

---

### 4. Signal Stability Analysis
Rolling mean and volatility diagnostics are used to assess signal stability over time, ensuring that the signal is not driven by short-lived anomalies.

---

## Results Summary
Key diagnostics include:
- Strategy risk metrics (Sharpe ratio, drawdown, turnover)
- Sector-neutral performance comparison
- Regression-based validation of macro-fundamental relationships
- Signal stability plots

Detailed metrics are provided in `RESULTS_SUMMARY.md`.

---

## Key Takeaways
- Macro-fundamental signals capture economically meaningful structure but are not standalone trading strategies
- Sector-neutral analysis improves interpretability
- Lagged macro variables align better with equity response dynamics
- Signal stability is as important as raw performance metrics

---

## Disclaimer
This project is intended for **research and educational purposes only**.  
Returns are based on proxy data and should not be interpreted as real-world trading performance.

---

## Author
Anish Deshmukh  
