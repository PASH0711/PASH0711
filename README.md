# Hi, I'm Pashang 👋

I'm building a career in markets operations and financial technology. My projects focus on the core workflows of a trading ops team — reconciliation, settlement, P&L reporting, and data quality.

---

## 📂 Portfolio Projects

### 🔁 [Trade Reconciliation Engine](https://github.com/PASH0711/trade-recon-engine)
Matches 10,000 trades between internal and counterparty blotters using a two-pass algorithm (exact → fuzzy match). Classifies breaks by type (price, quantity, timestamp, missing, duplicate) and outputs a formatted Excel exceptions report. Runs in under 0.2 seconds.

### 📊 [EOD P&L Report Automation](https://github.com/PASH0711/pnl-report-automation)
Pulls live market prices via yfinance, computes mark-to-market value and unrealized P&L for a 10-position portfolio, and generates a colour-coded Excel report with a dated filename. Scheduled to run every weekday at 5pm via Windows Task Scheduler.

### 🔍 [Data Quality Monitor](https://github.com/PASH0711/data-quality-monitor)
Pre-market data integrity checker that runs five validation rules against a daily price feed — missing fields, stale prices, outliers, duplicates, and schema drift. Logs every failure with ticker, date, and detail. Designed to act as a gatekeeper before downstream systems process the data.

### 📅 [Settlement Tracker](https://github.com/PASH0711/settlement-tracker)
Models trade lifecycles (Executed → Confirmed → Settled), computes T+2 settlement deadlines using the real NYSE business-day calendar, and flags SLA breaches. Produces a 3-tab Excel dashboard with aging buckets (1 day late / 2 days late / 3+ days late).

### 📋 [ETF Booking Automation](https://github.com/PASH0711/case-study-booking)
Processes ETF creation/redemption trades from an internal trading file and produces formatted CHESS settlement instructions. Filters by tag and trade date, maps Bloomberg codes to ISINs, and outputs a colour-coded booking file ready for submission.

---

## 🛠️ Tech Stack

Python · pandas · openpyxl · yfinance · pandas-market-calendars · Git

---

## 📫 Connect

### [LinkedIn](https://www.linkedin.com/in/pashang-vaid/)
