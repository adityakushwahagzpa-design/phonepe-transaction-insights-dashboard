# PhonePe Transaction Insights Dashboard | Power BI

An interactive Power BI dashboard that shows how customers pay and borrow on a digital payments app – by state, by payment type and by loan product – so a business team can track growth and spot risks in one place.

## Data
Synthetic sample data (Jan 2023 – Dec 2024), built to mirror digital-payment and lending records:
- **Customers:** 102,450 rows across 14 states
- **Transactions:** 640,000 rows across 5 payment types
- **Loans:** 18,600 rows across 4 loan types

## What was done
- **Power Query:** type changes, duplicate removal, text trimming, status clean-up, filter of invalid amounts
- **Data model:** star schema, with Customers and Calendar dimensions linked to the Transactions and Loans fact tables
- **DAX measures:** transaction value, active customers, YoY growth, success rate, loan amount, overdue rate, top-5 state share
- **Report pages:** Executive Overview, State-wise View, Payment Type View, Loan View, with synced slicers

## Key findings
- **₹76.52 Cr** transaction value, up **28.1%** in 2024 vs 2023, with an Oct–Nov festive peak
- **96.5%** payment success rate, stable across all payment types
- Top 5 states hold **51.0%** of value; West Bengal grows fastest (+34.9%)
- **₹122.21 Cr** loan book, up **67.0%** YoY; **6.6%** of loans overdue, Business Loans highest at 7.3%
- Only **16.6%** of customers borrow, so there is room to cross-sell credit

## Files
- `PhonePe_Transaction_Insights_Data.xlsx` – source data (Customers, Transactions, Loans, Calendar) plus a Dashboard sheet with 10 charts and a KPI_Check sheet with live formulas that match the report figures
- `PhonePe_Transaction_Insights_Project_Report.pdf` – step-by-step project report with snapshots and insights

## Tools
Power BI Desktop · DAX · Power Query · Excel

## Note
The data is synthetic, built for a project exercise. It is not official PhonePe data, and the project is not affiliated with PhonePe.

## Author
**Aditya Kushwaha** · [LinkedIn](https://www.linkedin.com/in/aditya-kushwaha16)
