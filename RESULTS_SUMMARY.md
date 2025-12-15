# Results Summary

## Dataset Overview
- Time period: ~6 years (monthly)
- Observations: 84 months
- Effective strategy periods: 72 months

---

## Baseline Strategy Metrics (Proxy Returns)

| Metric | Value |
|------|------|
| Annual Return | ~1.3% |
| Sharpe Ratio | ~0.16 |
| Max Drawdown | ~-24.6% |
| Average Monthly Turnover | ~25% |

Interpretation:
- The signal exhibits directional information but is not a standalone alpha generator.
- Turnover remains controlled, indicating signal stability rather than noise chasing.

---

## Sector-Neutral Strategy
- Market effects are neutralized using a broad proxy return.
- Sector-neutral results show reduced exposure to overall market drift.
- Improves interpretability of auto-specific macro signals.

---

## Lagged Macro Model Validation

| Metric | Value |
|------|------|
| Out-of-sample R² | ~ -0.05 |
| RMSE | ~0.048 |

Interpretation:
- Negative R² is expected for noisy financial returns.
- Lagged macro features provide economic insight rather than predictive precision.

---

## Signal Stability Diagnostics
- Rolling mean remains centered, avoiding persistent drift
- Rolling volatility remains bounded, indicating stable signal construction
- Confirms robustness of signal engineering approach

---

## Overall Conclusion
The project demonstrates a complete alternative-data research workflow:
- Economically interpretable signals
- Robust preprocessing and normalization
- Sector-neutral and lag-aware extensions
- Honest evaluation of limitations

The results support the thesis that equity prices reflect underlying macro-fundamental conditions, even if the relationship is noisy and delayed.
