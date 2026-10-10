# IFRS 16 Lease Accounting

An illustrative IFRS 16 lease accounting model built in Excel: lease liability measurement, amortization schedule, right-of-use (ROU) asset depreciation and monthly journal entries.

> \*\*Data privacy:\*\* All names, contract references, account codes and amounts are anonymized or illustrative. This is a portfolio demonstration model, not an extract of any current or former employer's records. No lease agreement is included in this repository.

## What's in this repository

|File|Description|
|-|-|
|`lease\_schedule.xlsx`|The working model (tabs: `ReadMe`, `LeaseCalculation`, `PortfolioNotes`)|
|`lease\_accounting\_summary.pdf`|Short methodology note: inputs, formulas, journal entries, judgements|

## Model coverage

* Lease assumptions and payment profile (72 months, annuity due, fixed 5% escalation, advance rent)
* Present value of lease payments / initial lease liability
* Monthly interest and principal allocation (effective interest method)
* ROU asset and straight-line depreciation over the lease term
* Illustrative monthly journal entries, including withholding tax and VAT presentation

## Headline results (illustrative lease)

|Item|Amount|
|-|-|
|Initial lease liability|19,374,133|
|Add: advance rent|683,780|
|**Initial ROU asset**|**20,057,913**|
|Monthly depreciation|278,582|
|Total interest over the term|5,173,569|

## How the model works

1. **Initial recognition (IFRS 16.22-27):** Lease liability = PV of lease payments at the monthly incremental borrowing rate (8.5% / 12). ROU asset = lease liability + advance rent.
2. **Subsequent measurement (IFRS 16.29-38):**

   * Interest = opening liability x monthly rate
   * Principal = lease payment - interest
   * Depreciation = ROU asset / lease term (straight-line)
3. **Checks:** liability and ROU net book value both close at nil; journals balance every month.

See `lease\_accounting\_summary.pdf` for the full explanation and the key judgements and limitations.

## Tools

Microsoft Excel | IFRS 16

## Disclaimer

For demonstration and learning purposes only. Verify assumptions and journal-entry treatment against the facts of any specific lease. Tax, VAT and withholding requirements must be assessed separately under local law.

