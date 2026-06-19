# JF 2025 Monthly Expense Analysis

Financial analysis of JF's 2025 monthly sales, expenses, and profitability, based on a year-long Excel tracking workbook. Data was cleaned and arranged in Excel before analysis; full findings and recommendations are in [REPORT.md](REPORT.md).

## Repository Structure

```
JF-2025-Expense-Analysis/
├── README.md          # This file
├── JF_2025_Expense_Analysis_Report.pdf           # Full analysis report (chaptered)
├── data/
│   └── JF_2025_Monthly_Expenses.xlsx   # Source workbook
```

## Summary

- **Net result (2025):** ₹331,496 net loss, average margin -7.8%
- **Profitable months:** April, May, June, October (4 of 12)
- **Biggest single driver of loss:** a Swiggy delivery-commission spike in July–August (₹309,647 combined, vs. a typical ~₹13–23k/month)
- **Other key drivers:** stock/inventory cost spikes (up to 46% of sales) and a fixed rent & salary base that doesn't flex with low-season sales (Feb, Nov, Dec)

See [REPORT.md](REPORT.md) for the full chaptered breakdown, including restaurant-level changes and broader business recommendations.

## How This Was Built

1. Source data cleaned and arranged in Excel (consistent headers, numeric formatting, chronological month order).
2. Cleaned data analyzed to calculate monthly/quarterly trends and cost ratios (stock %, commission %, fixed-cost % of sales).
3. Findings written up as a chaptered report.
