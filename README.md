# Design Ideas & Technology (DIT) - 3-Year Financial & Cash Flow Report (2024–2026)

Executive financial report, cash flow audit, and accounts receivable tracking for **Design Ideas & Technology (DIT)**.

## 🌐 Live Webpage Report
Once hosted on GitHub Pages, this dashboard will be live at:
`https://<your-github-username>.github.io/<your-repository-name>/`

---

## 📁 Repository Contents

| File | Description |
| :--- | :--- |
| **`index.html`** | Standalone interactive web dashboard with 3-year performance charts, individual year breakdowns, 34-month cash flow ledger, and searchable client receivables. |
| **`3_Year_Financial_Report_CashFlow_Receivables.xlsx`** | Full 6-sheet formatted Excel report with formulas, rollforwards, and aging tables. |
| **`Sales Invoice Update.xlsx`** | Original raw transaction ledger data. |
| **`dashboard_data.json`** | Pre-computed JSON dataset powering the dashboard charts and tables. |

---

## 🚀 How to Enable the Webpage on GitHub Pages

1. **Upload / Push** this repository to your GitHub account:
   ```bash
   git init
   git add index.html 3_Year_Financial_Report_CashFlow_Receivables.xlsx README.md .gitignore dashboard_data.json
   git commit -m "Add 3-Year Financial Report, Cash Flow Dashboard and Excel file"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
   *(Or drag & drop `index.html` and `3_Year_Financial_Report_CashFlow_Receivables.xlsx` into your GitHub repository in your browser!)*

2. **Turn On GitHub Pages**:
   - Go to your repository on GitHub.
   - Click **Settings** (⚙️ top right of repo).
   - In the left sidebar, click **Pages** (under the "Code and automation" section).
   - Under **Build and deployment** > **Branch**:
     - Select branch: **`main`**
     - Select folder: **`/ (root)`**
     - Click **Save**.
   - Within 1–2 minutes, your live web report link will appear at the top:
     `https://<your-username>.github.io/<repo-name>/`

---

## 📊 Summary of Financial Highlights (2024–2026)

- **Total Invoiced Revenue:** ৳ 158,043,383.80
- **Total Cash Inflow Collected:** ৳ 145,027,664.17
- **Collection Efficiency Rate:** 91.76% (Average across 3 years)
- **Net Operating Cash Flow Gap:** ৳ 13,015,719.63
- **Current Net Accounts Receivable:** ৳ 13,245,719.63
  - *Gross Outstanding Debtor Dues:* ৳ 30,649,014.00 (45 clients)
  - *Client Prepayments / Advances:* ৳ 17,403,294.00 (91 clients)
- **Top Inflow Mechanism:** Bank Transfer & RTGS (৳58.24M / 40.2%) followed by Cheques (৳50.47M / 34.8%).
