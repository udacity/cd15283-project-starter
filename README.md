# Project: Forecasting Approach Evaluation and Recommendation

Your VP of Sales projected $4.1M in monthly revenue by December 2026 — 18% year-over-year growth. The data engineering team found bugs in the original data that inflated recent figures. They've handed you clean data. Your job: figure out what the numbers actually say.

## Getting Started

Open `starter/starter.ipynb` and work through all four phases.

### Dependencies

```
pandas>=2.0
numpy>=1.24
matplotlib>=3.7
statsmodels>=0.14
darts>=0.41
scipy>=1.11
scikit-learn>=1.3
```

### Installation

```bash
pip install pandas numpy matplotlib statsmodels darts scipy scikit-learn
```

## Project Instructions

Work through the notebook in order:

1. **Phase 1: Baseline Forecasts** — naive, moving average, linear trend
2. **Phase 2: Classical Models** — ARIMA, SARIMAX with diagnostics and prediction intervals
3. **Phase 3: Modern Models** — N-BEATS (neural) and Chronos-2 (foundation model) via Darts
4. **Phase 4: Comparison and Recommendation** — comparison table + written recommendation

### Deliverables

1. Completed notebook with all phases implemented
2. Comparison table showing all models, December 2026 forecasts, prediction intervals, and accuracy metrics
3. At least three charts: baseline comparison, classical model forecasts with intervals, modern model forecasts
4. Written recommendation (500-1000 words) answering:
   - What is the realistic range for December 2026 revenue?
   - What should the company plan for instead of $4.1M?
   - Which forecasting approach would you recommend for ongoing use, and why?

## Data

- `data/revenue.csv` — 60 months of monthly revenue (January 2021 through December 2025), cleaned by the data engineering team

## License

[License](LICENSE.txt)
