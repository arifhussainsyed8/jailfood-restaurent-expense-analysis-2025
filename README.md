# JF 2025 Monthly Expense Analysis

Financial analysis of JF's 2025 monthly sales, expenses, and profitability, based on a year-long Excel tracking workbook. Data was cleaned and arranged in Excel before analysis; full findings and recommendations are in [REPORT.md](REPORT.md).

## Repository Structure

```
JF-2025-Expense-Analysis/
├── README.md          # This file
├── REPORT.md           # Full analysis report (chaptered)
├── data/
│   └── JF_2025_Monthly_Expenses.xlsx   # Source workbook
└── .gitignore
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

## Adding This Project to GitHub

If you don't already have a repository, run the following from inside this project folder:

```bash
git init
git add .
git commit -m "Initial commit: JF 2025 expense analysis"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-repo-name>.git
git push -u origin main
```

Steps explained:
1. **Create the repo on GitHub first** — go to github.com, click "New repository", give it a name (e.g. `jf-2025-expense-analysis`), and do **not** initialize it with a README (this folder already has one).
2. `git init` turns this folder into a Git repository.
3. `git add .` stages every file (README, REPORT, and the data file).
4. `git commit` saves a snapshot with a message.
5. `git remote add origin ...` points your local repo at the GitHub repo you created — copy the exact URL GitHub shows you after creating the repo.
6. `git push -u origin main` uploads everything.

If you'd rather skip the command line, you can also drag-and-drop this whole folder into GitHub's "Upload files" page on your new repository, then commit directly in the browser.
