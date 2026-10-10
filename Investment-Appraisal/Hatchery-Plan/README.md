# Fish Farming and Hatchery: Investment Appraisal Model

A fully linked Excel model that appraises a combined fish farming and hatchery project in Bangladesh and answers one question: *should this project be accepted?*

> **Illustrative case.** The company ("Sample Aqua Ltd."), its figures and all assumptions are a teaching and portfolio example, not an offer or investment advice.

## Base case result

| Metric | Result |
|---|---|
| Project cost / bank loan / owner equity | BDT 45.8 m / 22.9 m / 25.3 m |
| Discount rate (WACC) | 14.63% |
| NPV, 5 years only | BDT 3.1 m (IRR 16.6%) |
| NPV including recovery value | BDT 30.7 m (IRR 29.3%) |
| Payback / discounted payback | 3.66 / 4.78 years |
| Minimum DSCR | 1.61 (lending benchmarks met: 8 of 8) |

**Decision in the model: ACCEPT.** Be aware that the 5-year NPV is thin. Most of the headline value comes from the recovery value at the end of Year 5 (BDT 54.6 m). Under the Downside scenario (price -10%, yield -15%, feed +10%, capex +10%, interest +2 pp) the minimum DSCR falls to 0.92 and 6 of 8 benchmarks are met.

## What is inside (19 sheets)

- **Inputs:** Assumptions (all drivers, scenario selector)
- **Build-up:** Farming, Hatchery, Operations, FA Schedule
- **Statements:** Income Statement, Cash Flow, Balance Sheet, Working Capital, Funding
- **Analysis:** Investment Analysis, Loan Analysis, Owner Returns, Segment Analysis, Ratios
- **Risk and control:** Scenarios, Sensitivity and Break-even, Checks (15 integrity checks, "ALL OK")

## How to use

1. Open the workbook in Excel and start at **Dashboard**.
2. Change only the **blue input cells**; everything else recalculates.
3. Pick a scenario on the Assumptions sheet and confirm **Checks** shows "ALL OK".

## Limitations

- Five explicit years; value after Year 5 is a recovery-value assumption, not a forecast.
- Stocking is not capacity-constrained by formula. Working-capital days and the 20% cost of equity are judgement inputs.

Full documentation (logic, scenarios, verification): [`Model_Documentation.pdf`](Model_Documentation.pdf)

**Skills shown:** financial modelling, three-statement integration, NPV/IRR/payback, WACC, DSCR and lending benchmarks, scenario and sensitivity analysis, model auditing.
