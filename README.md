<!--
  ALVEN YUKA — GitHub profile README
  Replaces the previous capsule-render / tokyonight template with
  something that lives on its own. No GIF rainbows, no profile-views
  badges, no streak cards, no "What I Build / What I Bring" headers.
-->

### `alven yuka`

```
fraud detection · credit risk · portfolio analytics
nairobi → remote · finance ops → ml engineering
```

> I learned the cost of a model that can't survive a compliance review the
> same way most people learn it: the wrong way. Three years inside
> development-finance operations — 500+ multi-currency vouchers a month,
> 12 donor-funded programmes, two clean audit cycles — taught me that
> the audit-trail is the product. Now I build the same way.

---

#### one fraud-detection notebook, broken down honestly

```
                  ┌──────────────┐
   PaySim 6.36M ─►│  scoring     │─► 99.11% precision @ 96.88% recall
   step-time     │  pipeline    │   24 false positives in 132K
   split (66/34) └──────────────┘   Brier = 0.0005
                       ▲
                  errorBalanceOrig
                  (engineered from
                   accounting identity)
                  carries ~85% of
                  predictive power
```

Time-based split, not random — fraud models predict the future from the
past. Random splits leak future state and inflate PR-AUC dishonestly.

The PR-AUC = 1.000 on Random Forest is not a flex — it's what happens when
an engineered feature deterministically encodes the fraud signature in a
synthetic dataset. The honest read is: **the feature engineering solved the
problem; the model choice barely mattered**. That's a finding, not a brag.

→ [`Fraud-Detection-System`](https://github.com/alvenyuka/Fraud-Detection-System)
&nbsp;·&nbsp; PaySim · scikit-learn · XGBoost · LightGBM · imbalanced-learn · SHAP

---

#### one Excel workbook that I'd defend in front of a CFA charterholder

```
$303,680 portfolio  ·  16 stocks  ·  10 industries  ·  7 years
Sharpe 0.47  ·  Sortino 3.10  ·  Beta 1.47  ·  CAGR 14.89%
```

Not a Python notebook dressed up in an Excel skin — built natively in
Excel 365. STOCKHISTORY, linked Stocks data type, dynamic arrays. No VBA.
Black–Litterman optimisation, Cornish–Fisher VaR, parametric / historical /
Monte Carlo VaR, tax-aware lot matching with MAXIFS for ST/LT
classification under IRS §1222, and a 23-test Validation sheet that has
to PASS before the dashboard renders.

The non-obvious thing: a Sharpe of 0.47 against a Sortino of 3.10 is a
right-skew tell. Most of the volatility is upside — exactly the kind of
distribution where Sharpe under-rewards and Sortino is the honest read.

→ [`Stock-Portfolio-Tracker-Analytics-Engine`](https://github.com/alvenyuka/Stock-Portfolio-Tracker-Analytics-Engine)
&nbsp;·&nbsp; Excel 365 · Black–Litterman · CAPM · VaR/CVaR · CFA L1–L3

---

#### one Australian tax model that pays for itself in year one

```
salary sacrifice  ──►  offset account  ──►  annual sweep
   (15% vs 47%)         (interest drag)        (principal kill)

stage 3 brackets · concessional cap carry-forward · Div 293 · spousal
transfers · monthly granularity over 30 years
```

A side-by-side comparison of three repayment strategies (none / extra
after-tax / SuperSmart) for a dual-persona household. Every output is
formula-driven across 11 sheets — change the interest rate on the Input
sheet and the Dashboard, Loan, Offset, and YearlySummary all recalculate.
28 KPIs ship as Power BI–ready DAX measures in column D.

→ [`SuperSmart-Mortgage-Model`](https://github.com/alvenyuka/SuperSmart-Mortgage-Model)
&nbsp;·&nbsp; Excel 365 · DAX · ATO 2026–27 brackets · concessional cap modelling

---

#### what I'm wrong about (publicly)

So you don't have to find out the hard way in an interview:

- **PaySim is a toy.** Real mobile-money fraud has agent-tier signals, account-age, and graph features. PaySim collapses all three. The fraud detection results are a methodology demo, not a deployment claim.
- **Sharpe 0.47 is low** in absolute terms. The portfolio is concentrated and high-beta (1.47). It's a learning portfolio, not a benchmark proposal.
- **Excel ≠ production.** The mortgage model is decision-support for a household, not a banking system. It's auditable; it's not deployable.

---

#### what I'm hunting for

Fraud / AML / credit risk roles where the ML team works inside a regulated
function — not adjacent to one. Bonus points if your stack already has
SHAP in production and a quarterly model-risk review on the calendar.

`alvenyuka2@gmail.com` &nbsp;·&nbsp; [LinkedIn](https://linkedin.com/in/alven-yuka-610b78174) &nbsp;·&nbsp; Nairobi (remote-friendly across EU/AU/US)
