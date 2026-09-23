# Zetheta Project 1A — Data Analyst – Securitisation

## Project Overview

A Power BI Data Analyst project for analysing an auto-loan securitisation portfolio. The project covers portfolio balances, delinquency, defaults, recoveries, prepayments, losses, IFRS 9 ECL, stress testing, investor reporting, waterfall and trigger analysis, rating-oriented reporting, RLS and performance testing.

## Tools & Technologies

- Microsoft Power BI
- DAX
- DAX Studio
- Microsoft Excel
- SQL
- Python
- CSV datasets

## Dashboard Pages

1. DPD & Delinquency Analysis
2. Cumulative Loss / Default Analysis
3. IFRS 9 ECL
4. Stress Testing
5. Investor Reporting
6. Waterfall & Trigger Report
7. Rating Agency

## Key Results

| Metric | Result |
|---|---:|
| Total Current Balance | 317,785,202.14 |
| Original Pool Balance | 546,073,700 |
| Total Loan Count | 500 |
| Default Loan Count | 9 |
| Default Rate | 1.8% |
| Defaulted Balance | 6,789,682.49 |
| Total ECL Provision | 11,662,952.90 |
| Total Net Loss | 879,039 |
| Total Recoveries | 396,589 |
| DAX Studio Performance | 13 ms |

## Validation

The Power BI IFRS 9 ECL outputs were cross-checked against the Excel validation workbook. The differences were at normal rounding/precision level.

## Security & Performance

- 5 RLS roles configured and validated.
- Representative DAX Studio query completed in 13 ms.
- Project performance target: below 100 ms.

## Repository Structure

```text
PowerBi/
Excel/
Data/
Project_Report/
Presentation/
README.md
