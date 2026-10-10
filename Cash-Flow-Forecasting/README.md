# Cash Flow Forecasting

A bank-by-bank monthly cash flow forecast for a fictional company. It covers one month of actuals (May) followed by three forecast months (June to August) across three bank accounts, and shows how fund transfers keep each account in positive balance.

> **Data privacy:** All figures and names are fictional and were created for demonstration only. No confidential employer or third-party data is included.

## Files

| File | Description |
|---|---|
| `cash_flow_model.xlsx` | The forecast model: inflows, outflows, net cash flow, fund transfers and closing balances by bank |
| `cash_flow_summary.pdf` | Short write-up of the results, the logic and what the transfers are doing |

## Model structure

- **Cash inflows:** sales collections, other income and refunds
- **Operating outflows:** raw material and inventory payments, manufacturing, general and administrative expenses, salaries, interest, income tax, VAT and customs, rebates and credit notes
- **Inter-company payments:** settlements with seven affiliates (labelled A to G)
- **Non-operating payments:** capital expenditure and other one-off payments
- **Net monthly inflow / (outflow)**, by bank and in total
- **Cash and debt position:** opening balance, balance before transfer, fund transfer and closing balance

## Key logic

- Net inflow = total inflows - total outflows
- Balance before transfer = opening balance + net inflow
- Closing balance = balance before transfer + fund transfer
- Fund transfers between banks always sum to zero, so total cash does not change
- Each month's closing balance becomes the next month's opening balance

## Headline results (fictional data)

| Month | Net inflow / (outflow) | Total closing cash |
|---|---|---|
| May (actual) | 58,970 | 237,970 |
| June (forecast) | (83,630) | 154,340 |
| July (forecast) | 64,470 | 218,810 |
| August (forecast) | 6,420 | 225,230 |

Amounts are in the model's currency units.

## What the model shows

- **June is the low point.** Payments of 173,630 against collections of about 90,000, driven by 58,000 of inter-company settlements and a 100,000 non-operating payment.
- **Fund transfers cover the gaps.** Before transfers, Y Bank and Z Bank would be overdrawn in June, so 200,000 is moved out of X Bank, which receives all sales collections.
- **X Bank is left thin.** By August it holds 16,400 while Z Bank holds 159,920. A next step would be a minimum balance rule for each account, with transfers sized to that rule instead of round amounts.

## Assumptions and limitations

- Collections and payments are entered as monthly totals. There is no receivables ageing or customer-level forecast.
- Interest is an input line only, with no debt schedule.
- No scenario or sensitivity analysis is included.
- Values are illustrative and are not benchmarks for any real business.

## Skills shown

Cash flow forecasting, liquidity management, multi-bank cash positioning, Excel modelling
