# Telco Customer Churn Analysis — ABC Communications Ltd.

**AnalystLab Africa — Week 1 Data Analytics Project**

## Business Problem

ABC Communications, a telecom provider, is losing a significant share of its customer base to churn. This project investigates *who* is churning, *why*, and what the company can do about it — using the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) (7,043 customers, 21 attributes).

Customer churn is costly beyond the lost sale: acquisition costs (marketing, onboarding) are only recovered over a customer's lifetime, so early churn means that investment is never fully recouped — making retention significantly cheaper than reacquisition.

## Key Findings

| Driver | Finding |
|---|---|
| **Contract type** | Month-to-month customers churn at 43%, vs. 11% (one-year) and 3% (two-year) |
| **Payment method** | Electronic check churns at 45% — more than double any other payment method |
| **Online security** | Customers without security add-ons churn at 42%, vs. 15% with it |
| **Senior citizens** | Churn at 42%, nearly double non-seniors (24%) |
| **Tenure** | Strongest numeric predictor of churn (correlation: -0.35); churned customers have a median tenure of 10 months vs. 38 months for retained customers |

Overall baseline churn rate: **27%** (1,869 of 7,043 customers).

## Repository Structure

```
├── data/         Raw dataset (CSV)
├── analysis/     Excel workbook — data cleaning, pivot tables, 9 charts, correlation heatmap
├── report/       Full business report (Word) — business case, analysis, insights, recommendations
├── charts/       Individual chart images (PNG)
└── presentation/ Summary slide deck
```

## Methodology

1. **Data inspection** — checked row/column counts, data types, missing values (found 11 blank `TotalCharges` values tied to new customers, corrected to 0), and duplicates.
2. **Exploratory analysis** — built 9 visualizations (3 bar charts, 2 pie charts, 2 histograms, 1 box plot, 1 correlation heatmap) to examine churn across contract type, payment method, service adoption, tenure, and demographics.
3. **Insight synthesis** — translated each chart into a factual insight, a business risk, or an opportunity, avoiding unsupported causal claims not backed by the data.
4. **Recommendations** — five actionable, specific recommendations tied directly to the strongest findings.

## Recommendations Summary

1. Incentivize month-to-month customers to migrate to longer contracts.
2. Offer simplified/bundled service packages and dedicated support for senior customers.
3. Proactively offer or bundle online security with internet plans.
4. Launch a structured 90-day onboarding program to reduce early-tenure churn.
5. Encourage manual-payment customers to switch to automatic payment methods.

## Tools Used

Excel (PivotTables, formulas, charting, Data Analysis ToolPak for correlation), Word (final report).

## Author

*Veronica Wanjiku Gika* — AnalystLab Africa Internship, Week 1
