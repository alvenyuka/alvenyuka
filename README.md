<!-- ALVEN YUKA — GITHUB PROFILE README -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1B4B,50:1565C0,100:E65C00&height=220&section=header&text=Alven%20Yuka&fontSize=52&fontColor=FFFFFF&fontAlignY=42&desc=Data%20Scientist%20%7C%20Development%20Finance%20%7C%20Fraud%20Detection%20%7C%20Risk%20Analyst&descAlignY=62&descSize=20&descFontColor=FFD580&animation=fadeIn" width="100%"/>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Alven%20Yuka-1565C0?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1B4B)](https://linkedin.com/in/alven-yuka-610b78174)
[![Email](https://img.shields.io/badge/Email-alvenyuka2%40gmail.com-E65C00?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1B4B)](mailto:alvenyuka2@gmail.com)
[![GitHub Followers](https://img.shields.io/github/followers/alvenyuka?style=for-the-badge&logo=github&color=1565C0&labelColor=0D1B4B&logoColor=white)](https://github.com/alvenyuka)
[![Profile Views](https://komarev.com/ghpvc/?username=alvenyuka&style=for-the-badge&color=E65C00&label=PROFILE+VIEWS&abbreviated=true)](https://github.com/alvenyuka)

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## Who I Am

I spent three years inside development finance operations processing 500+ multi-currency vouchers a month, supporting 12 donor-funded programmes, and navigating two audit cycles without a single finding. That work taught me something most data scientists learn the hard way: the gap between a model that runs and a model that a risk desk actually trusts is enormous.

That gap is what I work to close. I build ML systems for financial problems — fraud detection, credit risk, portfolio analytics — with the compliance layer built in from the start, not bolted on at the end.

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## What I Build

### 🔍 Fraud Detection System
**PaySim · Python · XGBoost · Random Forest · SHAP**

Trained on 6.36M synthetic mobile-money transactions on a time-based split — fraud models predict the future from the past, so random splits leak future state and inflate metrics dishonestly. The hard part was not the model — it was making the outputs explainable enough for a KYC/AML audit trail. **99.11% precision at 96.88% recall** on a 132K held-out window, calibrated to Brier 0.0005, with permutation importance showing the engineered `errorBalanceOrig` feature carries ~85% of predictive power.

[![Repo](https://img.shields.io/badge/View%20Repo-Fraud%20Detection-1565C0?style=flat-square&logo=github&logoColor=white&labelColor=0D1B4B)](https://github.com/alvenyuka/Fraud-Detection-System)

---

### 📈 Stock Portfolio Tracker and Analytics Engine
**Excel 365 · CAPM · VaR · CVaR · Sharpe · Sortino · Calmar · Black–Litterman**

Built natively in Excel 365 — STOCKHISTORY, linked Stocks data type, dynamic arrays, no VBA. Covers 16 stocks across 10 industries over 7 years, with drawdown analysis, risk-adjusted return attribution, parametric / historical / Monte Carlo VaR, Cornish-Fisher VaR, tax-aware lot matching under IRS §1222, Black-Litterman optimisation, and a 23-test Validation sheet that has to PASS before the dashboard renders. CFA Level I–III methodology end-to-end.

[![Repo](https://img.shields.io/badge/View%20Repo-Portfolio%20Analytics-1565C0?style=flat-square&logo=github&logoColor=white&labelColor=0D1B4B)](https://github.com/alvenyuka/Stock-Portfolio-Tracker-Analytics-Engine)

---

### 🏡 SuperSmart Mortgage Strategy Model
**Excel 365 · DAX · Australian Tax Law · Offset Structuring**

An Australian tax-optimised mortgage repayment model for dual-persona households. Coordinates salary sacrifice (15% vs 47% marginal), offset account accumulation, and annual principal sweeps across 30 years. Models concessional cap carry-forward, Division 293 surcharge, spousal transfers, and Stage 3 brackets. 11 sheets, every output formula-driven; 28 KPIs ship as Power BI–ready DAX measures. Demonstrates how financial modelling translates directly from operations into strategy.

[![Repo](https://img.shields.io/badge/View%20Repo-Mortgage%20Model-1565C0?style=flat-square&logo=github&logoColor=white&labelColor=0D1B4B)](https://github.com/alvenyuka/SuperSmart-Mortgage-Model)

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## What I Bring to a Team

| The Problem | My Answer |
|:---|:---|
| Models that cannot survive a compliance review | SHAP explanations per prediction — built for KYC/AML reporting |
| Engineers who do not speak finance | 3 years on the operations side — VaR, CVaR, IFRS, SAP S/4HANA |
| Time-leaked validation that breaks in production | Time-based splits, walk-forward evaluation, calibrated probabilities |
| Analysts without international context | 12 donor-funded programmes across multiple currencies and jurisdictions |

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🛠️ Tech Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-1565C0?style=for-the-badge&logo=python&logoColor=white&labelColor=0D1B4B)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-E65C00?style=for-the-badge&logo=scikitlearn&logoColor=white&labelColor=0D1B4B)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boost-E65C00?style=for-the-badge&labelColor=0D1B4B)
![LightGBM](https://img.shields.io/badge/LightGBM-Ensemble-1565C0?style=for-the-badge&labelColor=0D1B4B)
![SHAP](https://img.shields.io/badge/SHAP-Explainability-E65C00?style=for-the-badge&labelColor=0D1B4B)
![Pandas](https://img.shields.io/badge/Pandas-Wrangling-1565C0?style=for-the-badge&logo=pandas&logoColor=white&labelColor=0D1B4B)
![NumPy](https://img.shields.io/badge/NumPy-Numerics-1565C0?style=for-the-badge&logo=numpy&logoColor=white&labelColor=0D1B4B)
![Excel](https://img.shields.io/badge/Excel%20365-Advanced-1565C0?style=for-the-badge&logo=microsoftexcel&logoColor=white&labelColor=0D1B4B)
![PowerBI](https://img.shields.io/badge/Power%20BI-DAX-E65C00?style=for-the-badge&logo=powerbi&logoColor=white&labelColor=0D1B4B)
![SAP](https://img.shields.io/badge/SAP%20S%2F4HANA-ERP-E65C00?style=for-the-badge&logo=sap&logoColor=white&labelColor=0D1B4B)

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 📊 GitHub Activity

<div align="center">

<a href="https://github.com/alvenyuka">
  <img width="96%" src="https://github-readme-activity-graph.vercel.app/graph?username=alvenyuka&theme=tokyo-night&bg_color=0D1B4B&color=FFD580&line=E65C00&point=FFFFFF&hide_border=true&area=true&radius=12&custom_title=Contribution%20Activity%20%E2%80%94%20last%2031%20days&days=31" alt="Contribution activity graph"/>
</a>

<br/><br/>

<a href="https://github.com/alvenyuka">
  <img height="175" src="https://github-readme-streak-stats.herokuapp.com/?user=alvenyuka&theme=tokyonight&hide_border=true&background=0D1B4B&ring=E65C00&fire=FFD580&currStreakLabel=E65C00" alt="Streak stats"/>
</a>

<br/><br/>

<a href="https://github.com/alvenyuka">
  <img width="96%" src="https://github-profile-trophy.vercel.app/?username=alvenyuka&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&margin-w=10&margin-h=10" alt="GitHub trophies"/>
</a>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🚧 Currently Building

<table align="center">
  <thead>
    <tr>
      <th align="center">Status</th>
      <th align="left">Project</th>
      <th align="left">What's left</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center">🟧&nbsp;<sub>In&nbsp;flight</sub></td>
      <td><b>FastAPI service for Fraud Detection</b><br/><sub>turn the notebook into a deployable artefact</sub></td>
      <td><code>/score</code> endpoint · Pydantic request schema · Dockerfile · CI workflow</td>
    </tr>
    <tr>
      <td align="center">🟦&nbsp;<sub>Designing</sub></td>
      <td><b>Open-banking credit scoring pipeline</b><br/><sub>PSD2-style transaction features → risk score</sub></td>
      <td>Feature taxonomy from transaction categories · cohort backtesting harness</td>
    </tr>
    <tr>
      <td align="center">📝&nbsp;<sub>Documenting</sub></td>
      <td><b>FinTech ML reference stack</b><br/><sub>for finance-ops folks moving into ML</sub></td>
      <td>End-to-end walkthrough · model risk checklist · deployment patterns</td>
    </tr>
  </tbody>
</table>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

## 🤝 Open To

<div align="center">

I am focused on **fraud detection** and **credit risk** roles in **FinTech** and **development finance** — teams where explainability and audit-readiness matter as much as model performance.

<table>
  <thead>
    <tr>
      <th align="left">🎯 Role focus</th>
      <th align="left">📍 What signals "right team" for me</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ML-driven fraud intelligence</td>
      <td>SHAP / model-risk reviews already in production</td>
    </tr>
    <tr>
      <td>Credit scoring pipelines</td>
      <td>Open banking / PSD2-style data access</td>
    </tr>
    <tr>
      <td>AML / KYC compliance tooling</td>
      <td>Quarterly model-risk governance on the calendar</td>
    </tr>
    <tr>
      <td>Development-finance analytics</td>
      <td>Multi-donor, multi-currency portfolios</td>
    </tr>
  </tbody>
</table>

If that sounds like your team, reach out directly.

<br/>

[![LinkedIn](https://img.shields.io/badge/Connect%20on%20LinkedIn-1565C0?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1B4B)](https://linkedin.com/in/alven-yuka-610b78174)
&nbsp;
[![Email](https://img.shields.io/badge/Send%20an%20Email-E65C00?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1B4B)](mailto:alvenyuka2@gmail.com)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:E65C00,50:1565C0,100:0D1B4B&height=120&section=footer" width="100%"/>
