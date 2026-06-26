# Sean Codner
### Workforce Planning & Operations Analytics | WFM · SQL · Python · Tableau | Fintech & Financial Services

📍 Houston, Texas &nbsp;|&nbsp; 🔗 [LinkedIn](https://www.linkedin.com/in/sean-codner-aa60822b)

---

## The Way I Think About Data

Most analytics projects show you what happened.
Mine are built to answer **what do we do next.**

I come from operations — ATM network management, call center forecasting, high-volume service environments where bad decisions cost real money in real time. That background shapes how I build analytical frameworks: not just querying data, but modeling the decisions that data has to support.

> A low-volume casino ATM located 142 miles from the nearest branch with 0.8 days of cash remaining is more operationally urgent than a high-volume urban machine with 6 days of runway. Standard reporting is blind to that. My work isn't.

---

## Technical Skills

![SQL](https://img.shields.io/badge/SQL-MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Business Intelligence](https://img.shields.io/badge/Business-Intelligence-F2C811?style=flat&logo=powerbi&logoColor=black)

**Domain expertise:** Workforce Management · Intraday Staffing · Erlang C · Shrinkage Modeling · ATM Network Operations · Cash Management Analytics · Call Center Forecasting · Service Level Management · Operational Risk Scoring · Executive Reporting

---

## Portfolio

Two parallel tracks. One argument: **operational analytics is most valuable when it moves beyond describing what happened and starts improving what happens next.**

---

### 📋 Track 1 — Workforce Planning & Optimization

---

### 🏗️ WFM Planning & Optimization Engine *(Active Development)*
**[→ View Repository](https://github.com/SEANSKIDATA/WFM-Demand-Forecasting)**

**Tools:** Python · Pandas · NumPy · Matplotlib · Erlang C · Jupyter

**The business question:** Given real contact-center arrival data, can we build the full WFM planning chain — from raw interval arrivals to staffing recommendations a manager can act on?

**The answer:** Yes. And the most important finding isn't in the forecast accuracy. It's in what happens after.

| Module | Description | Status |
|--------|-------------|--------|
| 1 — Forecast Engine | Interval-level volume forecast, holdout-validated (WAPE 21.2%) | ✅ Complete |
| 2 — Capacity Planning | Erlang C staffing, shrinkage build-up, FTE sizing | ✅ Complete |
| 3 — Gap Analysis | Required vs scheduled, interval-by-interval, delivered SL | ✅ Complete |
| 4 — Optimization Engine | Greedy redistribution — **+20.2% SL recovery, zero new hires** | ✅ Complete |
| 5 — Decision Lab | What-if simulator: redistribution, AHT, shrinkage, headcount levers | ✅ Complete |
| 6 — Multichannel | Voice + Chat (Erlang C + concurrency) + Email (backlog model) | ✅ Complete |
| 7 — Executive Dashboard | One-page KPI summary for operational leadership | 🔄 Planned |
| 8 — Executive Brief | Leadership summary in business language — no code | 🔄 Planned |

**Key finding:**

> Total scheduled headcount was within **1.6% of calculated requirements** — yet **53% of intervals were understaffed**, **44% overstaffed**, and delivered service level was **62.4% vs an 80% target.**
>
> The problem wasn't headcount. The problem was distribution.

**Optimization Engine result:** Redistributing existing agents without adding a single FTE recovered **+20.2% service level** — crossing the 80% target.

**Decision Lab — What-if results:**

| Lever | Service Level | Hits 80%? |
|-------|--------------|-----------|
| Baseline (current schedule) | 62.4% | ✗ |
| Redistribute only (no new hires) | 82.5% | ✓ |
| Add 5 FTEs | 95.5% | ✓ |
| Reduce AHT 15% | 76.2% | ✗ |
| Reduce shrinkage 4pts | 69.3% | ✗ |
| Redistribute + AHT 15% + Shrinkage 4pts | 94.4% | ✓ |

*Peer-validated by a WFM practitioner at Encore Capital Group (13+ years experience).*

---

### 📊 Track 2 — ATM Network Analytics Series

Three projects. One argument: **volume is the wrong primary signal for operational risk.**

---

### 🏧 Project 3 — ATM Predictive Demand Model
**[→ View Repository](https://github.com/SEANSKIDATA/ATM-Predictive-Demand-Model)** &nbsp;|&nbsp; **[→ Live Tableau Dashboard](https://public.tableau.com/app/profile/sean.codner/viz/ATMPredictiveDemandModel/Dashboard1)**

**Tools:** Python · Pandas · NumPy · Matplotlib · SQL · Tableau · MySQL

**The business question:** Which ATMs will hit a critical cash threshold in the next 72 hours — and what should operations teams do about it?

| | Metric | Value |
|---|---|---|
| 💰 | Revenue at Risk (72hr) | $830,880 |
| 🚨 | Critical ATMs | 5 locations |
| ⚡ | Immediate Dispatch Required | 5 machines |
| ⏱ | Avg Days to Failure (At-Risk) | 0.6 days |

**Key insight — The Refund Rush Effect:** Tax refunds had always been issued by check — until one season they weren't. With no advance notice, a major tax preparer switched to loading refunds directly onto debit cards. The first sign anything was wrong was iron-level alerts firing on machines that had never been a problem. A call to the store revealed what the data couldn't: every customer walked out with a card instead of a check and sprinted to the nearest ATM to pull their cash — often at the $500 limit, back to back. Standard reporting was blind to the cause. This model builds the institutional memory so the next pattern change doesn't blindside the network.

---

### 🔍 Project 2 — ATM Network Risk Intelligence
**[→ View Repository](https://github.com/SEANSKIDATA/ATM-Network-Risk-Intelligence)**

**Tools:** SQL · MySQL · Window Functions · CTEs

A composite risk scoring framework combining cash position, terminal distance, location type, and revenue impact into a single sortable priority register. A casino ATM 142 miles from the nearest branch with zero cash tolerance is categorically more urgent than a local retail machine at the same cash level. This framework reflects that.

---

### 📊 Project 1 — ATM Network Analysis Version 2
**[→ View Repository](https://github.com/SEANSKIDATA/ATM-Network-Analysis-Version-2)**

**Tools:** SQL · MySQL · Aggregations · Joins

Foundation SQL analysis establishing the core argument — volume is a misleading primary signal for ATM cash management risk.

---

## Portfolio Progression

| Project | Track | Tool | Status |
|---------|-------|------|--------|
| ATM Network Analysis V2 | ATM Analytics | SQL | ✅ Live |
| ATM Network Risk Intelligence | ATM Analytics | SQL | ✅ Live |
| ATM Predictive Demand Model | ATM Analytics | Python + Tableau | ✅ Live |
| WFM Planning & Optimization Engine | Workforce Planning | Python + Erlang C | ✅ Modules 1–6 live |

---

## Background

- **Workforce Management** — MCI Telecommunications (1994–1997). Intraday WFM for a 350+ agent contact center across Eastern/Central TZ sites. Real-time staffing against abandonment rate SLAs, schedule exception coding, IEX TotalView.
- **ATM Network Operations** — Cardtronics/NCR (2004–2022). 45,000+ terminal network, 98% contractual uptime SLA, ~$8M annual theft-loss avoidance coordination. Built and maintained executive reporting from the founding era.
- **Fintech Operations** — Margo/PowerCoin (2023). Built cash operations from scratch at an early-stage Bitcoin ATM startup.
- **Current** — Independent analytics consultant. Building this portfolio.

---

## Connect

I'm focused on remote roles at the intersection of **workforce management, operations analytics, and data analysis** — fintech, healthtech, SaaS, payments, or any environment where the data has to perform under pressure.

🔗 [LinkedIn — Sean Codner](https://www.linkedin.com/in/sean-codner-aa60822b)

---

*Portfolio datasets are real (Technion Anonymous Bank call-center data) or synthetic — purpose-built to reflect realistic operating conditions. WFM overlay assumptions are labeled throughout.*

