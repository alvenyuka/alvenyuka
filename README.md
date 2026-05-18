![Alven Yuka - Finance and Data Science, Nairobi](https://capsule-render.vercel.app/api?type=waving&color=0:1e3a8a,50:6366f1,100:7c3aed&height=220&section=header&text=Alven%20Yuka&fontSize=68&fontColor=ffffff&fontAlignY=36&desc=Finance%20%C3%97%20Data%20Science%20%C2%B7%20Nairobi&descSize=22&descAlignY=56)

<p align="center">
  <i>CPA Finalist (Kenya), awaiting ICPAK membership.<br/>
  Moving from finance operations into ML for fraud and credit risk.</i>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/alven-yuka-610b78174/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?logo=linkedin&logoColor=white"></a>
  <a href="mailto:alvenyuka2@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-alvenyuka2%40gmail.com-D14836?logo=gmail&logoColor=white"></a>
  <a href="https://github.com/alvenyuka"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-@alvenyuka-181717?logo=github"></a>
</p>

---

## Background

For three years I worked on the operations side of donor-funded finance: posting multi-currency vouchers, supporting program managers across multiple jurisdictions, and getting through annual audits with no material findings. That meant a lot of time inside the controls layer of finance, which turned out to be a useful place to be when I started building ML models. Most of the work in production fraud or credit risk is the part that lets a risk reviewer sign off on the output, not the part that picks the algorithm.

This profile is where I publish the work I'm doing to build out the technical side.

---

## Projects

### Fraud Detection System
[github.com/alvenyuka/Fraud-Detection-System](https://github.com/alvenyuka/Fraud-Detection-System) - Python, XGBoost, SHAP

Fraud classifier trained on PaySim (6.36M synthetic mobile-money transactions). I used a time-based train/test split rather than a random one, because random splits leak future state in fraud problems. The deployable model is XGBoost at 99.11% precision and 96.88% recall on a 132K-row held-out window, calibrated to a Brier score of 0.0005. The notebook walks through the feature engineering (the balance-discrepancy features carry most of the signal) and operating-point selection at 99% precision.

### Stock Portfolio Tracker & Analytics Engine
[github.com/alvenyuka/Stock-Portfolio-Tracker-Analytics-Engine](https://github.com/alvenyuka/Stock-Portfolio-Tracker-Analytics-Engine) - Excel 365

A paper portfolio of 16 stocks built in Excel 365 as a place to work through quantitative finance methods on a plausible set of holdings. The transactions are hypothetical, not from a real brokerage account. Uses STOCKHISTORY and dynamic arrays for live data; no VBA. Coverage includes CAPM and factor attribution, parametric and historical VaR, tax-aware lot matching under IRS section 1222, and a Black-Litterman optimisation panel. A validation sheet runs 23 integrity checks across the workbook before any dashboard will render.

### Financial Analyst Portfolio
[github.com/alvenyuka/Financial-Analyst](https://github.com/alvenyuka/Financial-Analyst) - Excel

Company financial analyses built from primary-source filings: three-statement models, DCF valuations, scenario toggles. Each workbook has a validation tab that ties every historical line back to the filing it was sourced from. First model is Apple.

---

## What I bring

Three years in finance operations gives me working language for the constraints models hit when they touch money. On the finance side I know VaR and CVaR, IFRS accounting conventions, SAP S/4HANA workflows, and the kind of evidence trail auditors look for. On the ML side I default to time-based validation, calibrated probabilities, and SHAP-level explanations per prediction. Most of the operational work has been on donor-funded programmes across multiple currencies, which forces a discipline about reconciliation that transfers well to risk modelling.

## Stack

Python (pandas, scikit-learn, XGBoost, LightGBM, SHAP), SQL, Excel 365, Power BI / DAX, Jupyter.

## Open to work

Fraud detection, credit risk, or analytics roles where the model risk function matters. Nairobi-based; open to remote.

alvenyuka2@gmail.com - [LinkedIn](https://www.linkedin.com/in/alven-yuka-610b78174/)
