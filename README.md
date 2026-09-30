## Alven Yuka

CPA Finalist and Accounting Specialist at GIZ in Nairobi, where I have spent three years in donor-funded
development finance: receivables, reconciliations and management reporting across a multi-donor programme
portfolio. Outside work I build credit-risk, fraud and valuation models for lenders and development-finance
institutions, with every figure traceable to the code or filing that produced it.

[LinkedIn](https://www.linkedin.com/in/alven-yuka-610b78174/) · [Email](mailto:alvenyuka2@gmail.com)

### Selected work

| Project | What it does | Result |
|---|---|---|
| [Credit Risk Scorecard](https://github.com/alvenyuka/Credit-Risk-Scorecard) | Points-based scorecard on 307,511 Home Credit applicants; WoE, logistic regression and credit metrics implemented and tested against scikit-learn | AUC 0.761, KS 0.393 on 61,503 held-out applicants; a reason code behind every score; sex and marital status excluded under ECOA |
| [Fraud Detection System](https://github.com/alvenyuka/Fraud-Detection-System) | XGBoost on 6.3M simulated mobile-money transactions, time-based validation, cost-based alert threshold, [live demo](https://fraud-detection-alven.vercel.app) | Catches 2,743 of 2,754 frauds (99.6%) at 98.4% precision on a time-based holdout; walk-forward PR-AUC 0.998 across 4 later windows |
| [Financial-Analyst](https://github.com/alvenyuka/Financial-Analyst) | Apple three-statement model and DCF from SEC 10-K filings, with an independent Python validator | 49 of 49 line items and 16 of 16 valuation figures reconcile; Base DCF $135.98 a share against a $338.40 market price, which on the same cash flows implies a 5.3% discount rate |
| [Kiva Loans Microfinance Analytics](https://github.com/alvenyuka/Kiva-Loans-Microfinance-Analytics) | Funding-risk model on 671,205 microloans, tested on the most recent 20% of loans, joined to a regional poverty index | PR-AUC 0.389 on the at-risk class (base rate 4.6%); catches 76% of at-risk loans |
| [Stock Portfolio Tracker](https://github.com/alvenyuka/Stock-Portfolio-Tracker-Analytics-Engine) | Excel 365 tracker built from a 112-trade ledger, with CAPM and 12-month risk analytics and a Python validator | 32.2% a year since 2019 (money-weighted); 45 of 45 derived figures rebuilt independently |

### How I work

- **The metric follows the cost of a mistake.** Precision where a false fraud flag freezes a customer's money;
  a specific reason where a declined applicant is owed one.
- **Numbers are checked outside the tool that made them.** Spreadsheets are recomputed in Python, hand-written
  statistics are tested against standard libraries, and the checks are tested by breaking copies on purpose.
- **Limitations are stated next to the results**, including the ones that lower the headline.

### Now

Building an IFRS 9 expected-credit-loss stress-testing engine for Kenyan SACCO loan portfolios. Open to
financial analyst, FP&A, credit risk and financial data analyst roles with lenders, DFIs and fintechs, in
Nairobi or remote.

**Tools in the repos above:** Excel, Python (pandas, scikit-learn, XGBoost), pytest.
**Used in finance work, no public artefact yet:** Power BI, Power Query, SAP. Currently deepening SQL.
