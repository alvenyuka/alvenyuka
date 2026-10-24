# Alven Yuka

Data Scientist, Nairobi. I build credit-risk, fraud and development-finance models in Python and SQL, and I test them so every figure traces back to the code that produced it.

Each project re-runs from its repository, has its own tests and states where its results stop being reliable. The finance domain comes from my day job: I am a CPA Finalist with three years at GIZ Kenya, where as a Finance Specialist I report on 12 donor programmes (zero audit findings across two review cycles) and rebuilt a budget-variance report in Power BI to take two hours instead of three days.

## Models and data pipelines

| Project | What it does | Data | Result |
|---|---|---|---|
| [Credit Risk Scorecard](https://github.com/alvenyuka/Credit-Risk-Scorecard) ([live demo](https://credit-risk-alven.vercel.app)) | A points-based score that ranks loan applicants by default risk, with a reason for every decline | Home Credit Default Risk: 307,511 applications | AUC 0.754 on 61,503 held-out applicants; approving only the top 80% cuts credit losses by 47% |
| [Mobile-Money Fraud Detection](https://github.com/alvenyuka/Fraud-Detection-System) ([live demo](https://fraud-detection-alven.vercel.app)) | Flags fraudulent mobile-money transfers so a fraud team can freeze them | PaySim, simulated: 6.36 million transactions | Catches 99.6% of holdout frauds at 99.9% precision, with 3 false alarms |
| [Kenya Aid Flows](https://github.com/alvenyuka/kenya-aid-flows) ([results page](https://kenya-aid-flows.vercel.app)) | A data pipeline (Python, DuckDB, SQL checks) that measures how much of the aid planned for Kenya arrives in its year | IATI via d-portal: 469,065 transactions, 2010 to 2024 | 73% of scheduled aid arrived in its year across 2,901 activity-years; a model did not beat a simple rule |
| [SACCO Stress Test](https://github.com/alvenyuka/SACCO-Stress-Test) | Estimates a Kenyan SACCO's IFRS 9 expected credit loss under three economic scenarios | Synthetic: 2,000 invented loans, no real SACCO data | Loss rises from KES 1.81M (base) to KES 19.27M (severe) |
| [Kiva Microloan Funding Risk](https://github.com/alvenyuka/Kiva-Loans-Microfinance-Analytics) | Ranks new microloans by the risk they never get fully funded | Kiva: 671,205 loans | The riskiest 10% of loans hold 76% of the unfunded dollars |

## Financial models, checked by Python

- [Apple Valuation Model](https://github.com/alvenyuka/Apple-DCF-Valuation): an Excel three-statement model and DCF built from Apple's 10-K filings. A separate Python validator re-derives 23 of 23 valuation figures; the base case is $139.50 a share against a $338.40 market price.
- [Stock Portfolio Tracker](https://github.com/alvenyuka/Stock-Portfolio-Tracker-Analytics-Engine): an Excel workbook that tracks a 16-stock paper portfolio from 112 trades; a Python validator rebuilds 55 of 55 figures. NVIDIA is 45.1% of the portfolio, and a 30% fall in semiconductors would cost $39,480.

## Connect

[Portfolio](https://alven-yuka.vercel.app) · [LinkedIn](https://www.linkedin.com/in/alven-yuka-610b78174/) · [alvenyuka2@gmail.com](mailto:alvenyuka2@gmail.com)
