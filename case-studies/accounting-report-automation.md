# Accounting Report Automation using Power Query

## 🧩 Context
The accounting team relied on exported trial balances from their accounting software to manually build quarterly financial statements in Excel.  
This created delays and inconsistency across reports.

## 🎯 Objective
Automate the financial statement preparation workflow while keeping Excel as the main working environment due to budget and system limitations.

## ⚙️ Solution
- Designed a Power Query model to automatically read and normalize exported trial balance files placed in a target folder.
- Built account mapping logic that matches sub-accounts to their parent categories (e.g., Cash in Bank → Chase Bank – Operating).
- Created dynamic pivot tables that generate consistent FS reports for every reporting period.

## 💡 Impact
- Reduced FS preparation time from **2 days to under 2 hours**.
- Achieved data consistency and eliminated manual reformatting.
- Provided a scalable template reusable across entities and periods.

## 🧰 Tools Used
Excel, Power Query, Power Pivot, Folder Automation

## 🧠 Takeaway
A lightweight solution can still deliver high impact when it precisely fits operational needs — especially under time and budget constraints.
