# Budget Forecast and Variance Analysis

Two illustrative Excel models for overhead budgeting and sales contribution, with a short PDF write-up for each. The data is for a fictional company.

> **Data privacy:** All figures, names and labels are fictional and were created for demonstration only. No confidential employer or third-party data is included. Remarks columns are left out on purpose.

## Files

| File | Description |
|---|---|
| `budget_vs_actual.xlsx` | FY'27 overhead budget against FY'26 projection, with monthly and quarterly phasing and a P&L summary |
| `overhead_budget_summary.pdf` | Two-page write-up: variances by expense group, largest line-item movements, phasing, P&L impact |
| `sales_budget_contribution.xlsx` | Product-level sales budget, cost of goods sold and contribution margin for seven sample products |
| `sales_budget_summary.pdf` | Two-page write-up: margin by product and business type, and the effect of import cost |

## Headline results

| Item | Result |
|---|---|
| Overheads (excl. ECL), FY'27 budget vs FY'26 projection | 924 vs 932 (thousands), 0.9% lower |
| Revenue plan | 13,000 vs 11,000 (thousands), +18% |
| EBITDA margin | 31% vs 26% |
| Sales contribution margin | B2C 28%, B2B 14% |
| Effect of import-value costing | Contribution about 9 lower (3.5%) |

## How it works

- Monthly budget = annual budget / 12, grouped into quarters (Q1 = Apr-Jun)
- Variance % = (FY'27 budget - FY'26 projection) / FY'26 projection
- Exchange rates are two input cells in the sales model, not hard-coded in formulas

## Assumptions and limitations

- Phasing is straight-line, so there is no seasonality.
- The sales model covers seven sample products only.
- Values are illustrative and are not benchmarks for any real business.

## Tools

Microsoft Excel
