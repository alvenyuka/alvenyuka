<h1 align="left">Hi, I'm Alven Yuka 👋</h1>

<p align="left">
  <strong>CPA Finalist building credit-risk and fraud models for development-finance lenders.</strong>
</p>

<p align="left">
  <a href="https://www.linkedin.com/in/alven-yuka-610b78174/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:alvenyuka2@gmail.com"><img src="https://img.shields.io/badge/Email-alvenyuka2%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

![Alven Yuka: credit risk, fraud detection and development finance](banner.svg)

---

## Projects

| Project | What it does | Result |
| --- | --- | --- |
| **[Credit Risk Scorecard](https://github.com/alvenyuka/Credit-Risk-Scorecard)** ([live](https://credit-risk-alven.vercel.app)) | From-scratch WoE/IV and logistic regression checked against scikit-learn and scipy at every step (99.9997% prediction agreement), on 307,511 real Home Credit applicants plus bureau/previous-application history | 0.762 AUC, 0.394 KS |
| **[Fraud Detection System](https://github.com/alvenyuka/Fraud-Detection-System)** ([live](https://fraud-detection-alven.vercel.app) · [dashboard](https://fraud-detection-system-kmeuq7hku8tglnxdpmalfk.streamlit.app/)) | XGBoost fraud classifier on 6.3M PaySim mobile-money transactions: balance-discrepancy feature engineering, isotonic calibration, walk-forward validated across 4 folds | 99.85% precision / 99.56% recall on the holdout (95.6% mean precision across 4 walk-forward folds) |
| **[Kiva Loans Microfinance Analytics](https://github.com/alvenyuka/Kiva-Loans-Microfinance-Analytics)** | Funding-risk model on 671K real Kiva microloans joined to region-level MPI poverty data, with SHAP attribution and a days-to-fund regression | 0.4889 PR-AUC, 7.43-day MAE |
| **[Financial-Analyst](https://github.com/alvenyuka/Financial-Analyst)** | Three-statement models and DCF valuations built from primary-source SEC filings, each with a validation tab tying every historical line back to the 10-K it came from, and a script that re-derives the arithmetic independently in CI | Apple DCF ≈ $240 vs. $232.50 reference; 50/50 data points traced to filings; 19/19 identities re-derived |
| **[Stock-Portfolio-Tracker-Analytics-Engine](https://github.com/alvenyuka/Stock-Portfolio-Tracker-Analytics-Engine)** | Portfolio risk/performance analytics engine in Excel: VaR/CVaR, CAPM, Black-Litterman optimisation, tax-aware rebalancing, with every derived figure recomputed in Python in CI | 12.59% 7-yr CAGR, 0.37 Sharpe, -12.33% max drawdown; 27/27 figures re-derived |

---

## How I work

Three habits show up in every repo above, and they are the part I would actually
want reviewed:

- **The metric is chosen before the model.** PR-AUC rather than accuracy at a
  0.13% fraud rate, minority-class PR-AUC rather than the majority class on Kiva
  funding, calibration alongside AUC on the scorecard. Picking the flattering
  metric afterwards is the easiest way to be wrong at length.
- **Leakage is checked, not assumed away.** Fraud and credit both split on time
  rather than at random, and the Kiva model runs an explicit guard that fails the
  build if a post-outcome column reaches the feature set. A leaked column does not
  break a model, it improves its score, so it survives every check that is not
  looking for it.
- **The parts that can break silently are unit-tested.** Not the model's score,
  which a walk-forward run already reports, but the pieces whose failure would
  leave every downstream number looking plausible: from-scratch AUC and KS against
  scipy, the gradient-descent solver against scikit-learn, the cost-sensitive
  threshold, and the leakage guards. 89 tests across five repositories, each
  running in continuous integration on every push. Two of them exist because of
  bugs the work hit, including a KS statistic that was correct on continuous
  scores and wrong under ties, which is what a bucketed scorecard produces.
- **A number is checked outside the tool that produced it.** The two Excel
  repositories each ship a script that recomputes the workbook's own figures in
  Python and never reads a cell containing a tick. A validation tab reporting
  its own pass is worth what its formulas are worth. The financial model has 19
  accounting identities re-derived this way and the portfolio engine has 27, both
  on GitHub's servers rather than on my machine. Each validator is itself tested
  by breaking a copy of the workbook and confirming the specific fault is
  reported, because one that has only seen a correct file proves nothing.

---

## Stack

**Demonstrated in the repos above**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/XGBoost-0055AA?style=flat-square" alt="XGBoost">
  <img src="https://img.shields.io/badge/LightGBM-9ACD32?style=flat-square" alt="LightGBM">
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/SHAP-8A2BE2?style=flat-square" alt="SHAP">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" alt="pytest">
  <img src="https://img.shields.io/badge/Microsoft_Excel-217346?style=flat-square&logo=microsoft-excel&logoColor=white" alt="Excel">
</p>

**Used in professional finance work, no public artefact yet**

<p>
  <img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=power-bi&logoColor=black" alt="Power BI">
  <img src="https://img.shields.io/badge/SAP-0FAAFF?style=flat-square&logo=sap&logoColor=white" alt="SAP">
  <img src="https://img.shields.io/badge/Power_Query-376C37?style=flat-square" alt="Power Query">
</p>

The split is deliberate. Everything in the first row can be checked by opening a
repo and running it. The second row is real work at an employer that has no public
artefact I can point you at, which is more useful to know than a single wall of
badges where everything looks equally earned.

Credit-risk work covers WoE/IV, scorecard development, and GINI/KS/PSI validation
against IFRS 9 ECL requirements. On the fraud side: imbalanced classification with
cost-sensitive thresholding, evaluated PR-AUC-first. Finance modelling spans
GAAP/IFRS, three-statement builds, and DCF valuation.

---

Open to **Credit Risk Analyst**, **Data Analyst**, and **Financial Data Scientist** roles.

📫 [alvenyuka2@gmail.com](mailto:alvenyuka2@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/alven-yuka-610b78174/) · 🐙 [GitHub](https://github.com/alvenyuka)
