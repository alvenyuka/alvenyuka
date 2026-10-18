# Alven Yuka

**Data Scientist and Financial Analyst · credit risk, fraud and IFRS 9 · Nairobi**

I build credit-risk, fraud and IFRS 9 models for lenders and development-finance institutions, and I hold
them to an audit standard. I am a CPA Finalist and an Accounting Specialist at GIZ Kenya, where I run the books
of a 12-programme multi-donor portfolio with zero audit findings across two review cycles. So every figure in
these repos traces to the code that wrote it and is checked by a second tool: 215 tests run in CI across six
projects, each stating its result in money and its limits in plain words.

[![Portfolio](https://img.shields.io/badge/Portfolio-alven--yuka.vercel.app-12161f?style=flat)](https://alven-yuka.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alven_Yuka-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/alven-yuka-610b78174/)
[![Email](https://img.shields.io/badge/Email-alvenyuka2%40gmail.com-3d5a00?style=flat)](mailto:alvenyuka2@gmail.com)

---

## What I build

- **Credit-risk models.** Points-based scorecards with Weight of Evidence binning, Information Value
  screening, correlation and coefficient-sign gates, and a logistic regression coded from first principles
  whose predictions correlate 0.999999 with scikit-learn's. Each cut-off is judged by the credit losses it avoids.
  ([Credit Risk Scorecard](https://github.com/alvenyuka/Credit-Risk-Scorecard))
- **IFRS 9 expected credit loss and stress testing.** Stage 1, 2 and 3 allocation, scenario-weighted ECL and
  the capital-ratio impact of a severe downturn on a SACCO loan book.
  ([SACCO Stress Test](https://github.com/alvenyuka/SACCO-Stress-Test))
- **Fraud detection on mobile money.** Gradient-boosted classifiers with balance-discrepancy features, a
  strict time-based split, walk-forward validation, a threshold judged by how many honest customers it
  would freeze, and a live scoring API.
  ([Fraud Detection System](https://github.com/alvenyuka/Fraud-Detection-System))
- **Microfinance analytics.** Day-one funding-risk ranking with LightGBM and SHAP across 671,205 Kiva loans,
  chosen on earlier loans and scored once on later ones. ([Kiva Loans](https://github.com/alvenyuka/Kiva-Loans-Microfinance-Analytics))
- **Valuation and financial modelling.** A three-statement model and DCF of Apple from its SEC filings, and portfolio return
  and risk analytics (money-weighted return, CAPM, VaR, drawdown) in Excel, each rebuilt independently by a
  Python validator. ([Financial-Analyst](https://github.com/alvenyuka/Financial-Analyst),
  [Stock Portfolio Tracker](https://github.com/alvenyuka/Stock-Portfolio-Tracker-Analytics-Engine))
- **Finance operations.** Three years in donor-funded development finance at GIZ Kenya: 10 to 15 grant and
  local-subsidy agreements a month, about 300 payables vouchers a month, payroll for 350+ staff in SAP and Sage
  at 100% accuracy, receivables cut 40% in four months, a Power BI variance report that takes two hours instead
  of three days, and an Excel travel-claim tool localised for the Kenya and Somalia offices. (No public artefact)

## Featured projects

| Project | Stack | Scale | Result |
|---|---|---|---|
| [Credit Risk Scorecard](https://github.com/alvenyuka/Credit-Risk-Scorecard) · [case study](https://credit-risk-alven.vercel.app) | Python · pandas · scikit-learn · LightGBM · pytest | 307,511 applicants · 8 tables · 62 to 32 features · 69 tests | AUC 0.754, KS 0.381; approving the top 80% cuts credit losses 47% |
| [Fraud Detection System](https://github.com/alvenyuka/Fraud-Detection-System) · [live demo](https://fraud-detection-alven.vercel.app) | Python · XGBoost · SHAP · serverless API | 6.36M transactions · 4 walk-forward windows · 63 tests | 99.98% of fraud value stopped with 3 false alarms; PR-AUC 0.9984 |
| [Kiva Loans Microfinance Analytics](https://github.com/alvenyuka/Kiva-Loans-Microfinance-Analytics) | Python · LightGBM · SHAP · TF-IDF | 671,205 loans · 33 tests | Reviewing the riskiest 10% reaches 76% of a $5.8M funding shortfall |
| [SACCO Stress Test](https://github.com/alvenyuka/SACCO-Stress-Test) | Python · IFRS 9 ECL engine | 2,000 synthetic loans · 3 scenarios · 5 tests | ECL rises from KES 1.81M (base) to 19.27M (severe); capital falls from 14.2% to 6.7% |
| [Financial-Analyst](https://github.com/alvenyuka/Financial-Analyst) | Excel (no macros) · Python validator | 56 line items · 23 valuation figures · 20 tests | Apple base case $139.50 against a $338.40 close |
| [Stock Portfolio Tracker](https://github.com/alvenyuka/Stock-Portfolio-Tracker-Analytics-Engine) | Excel 365 · Python validator | 16 stocks · 112 trades · 25 tests | 32.2% a year since 2019; a 30% chip-sector fall costs $39,480 |

## Tools

| | In my public repos | At work, no public artefact yet |
|---|---|---|
| Languages and data | Python, pandas, NumPy | SQL (learning), Power Query |
| Modelling | scikit-learn, XGBoost, LightGBM, SHAP | |
| Testing and delivery | pytest, GitHub Actions, Vercel | |
| Finance and BI | Excel 365 (dynamic arrays, STOCKHISTORY) | Power BI (DAX), SAP S/4HANA, Sage, QuickBooks |

## Now

- **Building:** SQL depth on finance data, and pipelines that refresh real Kenyan financial data on a schedule.
- **Open to:** data scientist, credit-risk and financial data analyst roles with lenders, DFIs, fintechs and
  investment teams, in Nairobi or remote.

## How I work

1. **Start from the decision.** I ask what a wrong answer costs before choosing a metric: a false fraud alert
   freezes a customer's money, and a declined applicant is owed a reason.
2. **Check every number with a second tool.** Each Excel model has a Python validator, tested by breaking a
   copy of the file on purpose; hand-coded statistics are tested against scikit-learn.
3. **State results in money.** Credit losses avoided, fraud value stopped, funding shortfall reached, value at
   risk.
4. **Report what the result does not show.** The published score is the one chosen before the test set was
   seen: the Kiva model reports 0.374 even though a variant it passed over scored 0.386 on the test set.

## Connect

[Portfolio](https://alven-yuka.vercel.app) · [LinkedIn](https://www.linkedin.com/in/alven-yuka-610b78174/) · [alvenyuka2@gmail.com](mailto:alvenyuka2@gmail.com)
