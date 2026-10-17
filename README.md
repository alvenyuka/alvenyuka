## Hi, I'm Alven Yuka 👋

**Data Scientist · Financial Analyst** · credit risk, fraud and valuation · Nairobi

I build and validate models for finance: credit-risk scorecards, fraud detection, company valuation and
portfolio risk, for lenders and development-finance institutions, with every figure traceable to the code or
filing that produced it. The finance side is first-hand: I am a CPA Finalist and an Accounting Specialist at
GIZ in Nairobi, with three years in donor-funded development finance.

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://github.com/alvenyuka?tab=repositories)
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)](https://github.com/alvenyuka/Credit-Risk-Scorecard)
[![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=flat)](https://github.com/alvenyuka/Fraud-Detection-System)
[![Excel](https://img.shields.io/badge/Excel-217346?style=flat)](https://github.com/alvenyuka/Financial-Analyst)

### Selected work

| Project | What it does | Result |
|---|---|---|
| [Credit Risk Scorecard](https://github.com/alvenyuka/Credit-Risk-Scorecard) | Scores loan applicants for default risk and gives a reason for every decline ([live case study](https://credit-risk-alven.vercel.app)) | Approving the top 80% of applicants would have cut credit losses by 47% on past data (AUC 0.754) |
| [SACCO Stress Test](https://github.com/alvenyuka/SACCO-Stress-Test) | Stress-tests a Kenyan SACCO loan book under three economic scenarios and reports IFRS 9 expected credit loss | In the severe scenario losses rise from KES 1.81M to KES 19.27M and capital falls to 6.7%, KES 7.68M short of a 10% minimum (synthetic portfolio) |
| [Fraud Detection System](https://github.com/alvenyuka/Fraud-Detection-System) | Flags fraudulent mobile-money transfers before the money leaves ([live demo](https://fraud-detection-alven.vercel.app)) | Stopped 99.98% of fraud value on unseen simulated (PaySim) transactions, against 1.1% for the built-in rule, with 3 false alarms |
| [Kiva Loans Microfinance Analytics](https://github.com/alvenyuka/Kiva-Loans-Microfinance-Analytics) | Warns which microloans may never be fully funded, on the day they are posted | Reviewing the riskiest 10% of loans reaches 76% of the $5.8M that went unfunded |
| [Financial-Analyst](https://github.com/alvenyuka/Financial-Analyst) | Values Apple from its SEC filings, with every figure re-checked by a separate program | Shares worth $139.50 on a standard cost of capital, against a $338.40 market price |
| [Stock Portfolio Tracker](https://github.com/alvenyuka/Stock-Portfolio-Tracker-Analytics-Engine) | Works out a portfolio's real return and risk from its trade history, in Excel | 32.2% a year since 2019, but a 30% fall in semiconductors would cost $39,480 |

Each repository has an executed notebook, a validated workbook or a tested engine, a test suite that runs in CI, and a README
that states the result in money, the method, and what the result does not show.

---

- 🔭 **Just published:** an IFRS 9 expected-credit-loss stress test for a Kenyan SACCO loan book, on a synthetic
  portfolio with every figure reproduced in CI.
- 🌱 **Learning:** SQL on the finance datasets above, and deeper valuation and portfolio-risk work.
- 💼 **Day job:** Accounting Specialist at GIZ Kenya, running the finance operations of a 12-programme
  multi-donor portfolio: 10 to 15 grant and local-subsidy agreements a month with partner organisations, monthly close and
  donor reporting with zero audit findings across two review cycles, payroll for 350+ staff in SAP and Sage
  at 100% accuracy, about 300 payables vouchers a month, receivables cut 40% in four months, a Power BI
  dashboard that takes two hours instead of three days, and an Excel travel-claim tool localised for the
  Kenya and Somalia offices.
- 💬 **Ask me about:** credit scorecards and Weight of Evidence, IFRS 9 expected credit loss and stress testing, fraud detection on mobile-money data, DCF
  valuation and three-statement models, portfolio risk (volatility, drawdown, value at risk), Power BI for
  finance teams, month-end close across a multi-donor portfolio.
- 📫 **Reach me:** [alvenyuka2@gmail.com](mailto:alvenyuka2@gmail.com) ·
  [LinkedIn](https://www.linkedin.com/in/alven-yuka-610b78174/) · [Portfolio site](https://alven-yuka.vercel.app)
- 📍 **Open to:** data scientist, data analyst, credit-risk and financial data analyst roles, and financial
  analyst roles, with lenders, DFIs, fintechs and investment teams, in Nairobi or remote.

---

### How I work

1. **I start from the decision, not the model.** Before choosing what to measure, I ask what a wrong answer
   costs. A false fraud alert freezes a customer's money, so the fraud project counts how many legitimate
   customers would be frozen. A declined loan applicant is owed a reason, so the scorecard gives one for every
   decline.
2. **I check every number with a second, independent tool.** Each Excel model comes with a Python program that
   recalculates its figures from the raw inputs, and I test those programs by deliberately breaking a copy of the
   file to confirm they catch the error. In the credit scorecard, the statistics and logistic regression I
   coded myself are tested against scikit-learn.
3. **I state results in money.** Each project ends with what it is worth to the business: credit losses
   avoided, fraud value stopped, funding shortfall reached, value at risk.
4. **I report what the results do not show.** Every project lists its limitations, and the published score is
   the one chosen before the test set was seen: the Kiva model is picked on earlier loans and scored once on
   later ones, so it reports 0.374 even though a variant it passed over scored 0.386 on the test set.

---

**In the repositories above:** Python (pandas, scikit-learn, XGBoost, LightGBM, SHAP), Excel, pytest.
**Used daily at work, no public artefact yet:** Power BI, Power Query, SAP S/4HANA.
