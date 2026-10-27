# Hi, I'm Osman Zakaria, PMP 👋

### Data & Research Analyst · Project Coordinator · Construction Safety Officer
**Power BI · SQL · Python · Tableau · Excel** | Vancouver, BC, Canada

[Portfolio](https://zosmano.github.io) · [LinkedIn](https://www.linkedin.com/in/osmanzakaria) · zosman50@gmail.com

---

## 🚀 About Me

I am an analytical and results-driven professional with over 6 years of experience in data management, payroll analysis, project coordination, data validation, and research and business analysis across education, public administration, and research sectors.

I am a **PMP-certified professional** with a **Master's in Analytics**, specializing in transforming complex data and processes into clear, concise reports, visualizations, and deliverables that inform decision-making and enhance operational efficiency. I find the errors, anomalies and cost leaks hidden in large records, then turn what I find into SQL checks, dashboards and models that others can rerun. I am adept at coordinating multi-stakeholder communications and supporting organizational change initiatives.

* 🔭 Current Focus: Research analysis at Participedia, and building public-data analytics projects in Power BI, SQL and Python.
* 💡 Goal: To leverage data science and project management to drive organizational efficiency and strategy.
* 📫 How to reach me: zosman50@gmail.com

---

## 🛠️ Toolkit

| Category | Tools |
|---|---|
| Analysis & BI | Power BI (DAX, Power Query), Tableau, Excel (advanced), SPSS |
| Data & code | SQL (PostgreSQL, MySQL, SQLite), Python (pandas, NumPy, matplotlib, CatBoost, XGBoost) |
| Project delivery | PMP, requirements and specifications, report automation, ETL workflows, document control |
| Safety credentials | Construction Safety Officer (CSO), Advanced First Aid (OFA Level 3), WHMIS, Confined Space Entry, Fall Protection, Traffic Control Person |

---

## 📂 Featured projects

| Project | What it shows | Tools | Links |
|---|---|---|---|
| ✈️ U.S. flight delay pipeline | End-to-end pipeline on 4.1M flights; reproduces all 96 published DOT figures | Python, SQL, SQLite | [Code & README](https://github.com/Zosmano/flight-delay-pipeline) |
| 🚌 Next Shift: Ontario autoworker job match | Interactive tool ranking jobs for laid-off autoworkers from 89,557 Job Bank postings | Python, JavaScript, open data | [Interactive tool](https://claude.ai/artifact/TosuEsDPFk3BEKgXYeCTBy) · [Repo](https://github.com/Zosmano/autoworker-transition-platform) |
| 📮 Canada Post turnaround analytics | Cost-saving and mailbox-siting model across 1,646 forward sortation areas | Python, Census 2021, optimization | [Interactive analysis](https://claude.ai/artifact/J7girjpym3SAGt3zXGScmi) · [Repo](https://github.com/Zosmano/canada-post-turnaround-analytics) |
| ⚡ Canadian household energy, 2011–2021 | Power BI dashboard cross-checked against a SQL analysis | Power BI, DAX, SQL | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMWFlMjQxZTUtNTVlYi00MjMzLWIzODAtMzk3MjE3ZDQyZjE3IiwidCI6ImM3ZTc5YjlkLWVjZTktNDEzMy04NzQzLWI2Y2FkMjZjNTc0ZiIsImMiOjEwfQ%3D%3D) · [SQL](https://github.com/Zosmano/Household-Energy_SQL_Analysis) |
| 🌍 Global Democratic Governance dashboard | Links country governance indicators to 2.26K+ participatory-democracy cases | Power BI, Power Query | [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZmFlMDhlMTEtOWE3NC00ZTRhLWFjNjEtZGY2ZGRiOGVkMGVlIiwidCI6ImM3ZTc5YjlkLWVjZTktNDEzMy04NzQzLWI2Y2FkMjZjNTc0ZiIsImMiOjEwfQ%3D%3D) · [Repo](https://github.com/Zosmano/Participedia-Global-Research-Dashboard) |
| 📊 Executive Portfolio Diagnostic Suite | PMO dashboard on 1M+ synthetic records: cost variance, earned value, burn-down | Tableau | [Tableau Public](https://public.tableau.com/app/profile/osman.zakaria/viz/ExecutiveDashboard_Tableau_17897535940690/PortfolioPerformanceCostVariance) · [Repo](https://github.com/Zosmano/Executive-Portfolio-Diagnostic-Suite-1M-Records-) |

More detail on each project is on [my portfolio site](https://zosmano.github.io).

### 🚌 Next Shift: Ontario autoworker job match

An interactive tool for workers laid off at Stellantis Brampton and GM CAMI Ingersoll. A worker picks a plant job and a longest drive, and the tool ranks Ontario occupations by skill fit (ESDC's OaSIS skills ratings), openings from Job Bank within a rush-hour drive on the Statistics Canada road network, pay, and training time. It then lists nearby college programs and funding. It is built on 89,557 Job Bank postings and 516 occupations. A planning view estimates how many of the laid-off workers local openings could absorb and where retraining helps most.

- **Link:** [Try the interactive tool](https://claude.ai/artifact/TosuEsDPFk3BEKgXYeCTBy)
- **Note:** independent analysis from public data. Postings are not hires, and the plant workforce mix and the share of openings workers can win are adjustable assumptions, not union data.

### 📮 Canada Post turnaround analytics

An interactive analysis of how Canada Post can cut delivery cost and win back parcel customers. It combines Canada Post's 2017 delivery-point and delivery-mode data with the 2021 Census and the National Address Register (10.7M buildings) across all 1,646 forward sortation areas. It estimates the saving from converting door-to-door delivery to community mailboxes (about $487M a year, a model estimate), ranks the areas to convert first, and sites mailboxes and plans routes on real street networks in three case-study areas. It also includes an early-warning model for business customer churn (on simulated customers) and an allocation of the 2025 parcel volume decline (79 million pieces, 32.6%) across areas by modelled demand.

- **Link:** [Read the interactive analysis](https://claude.ai/artifact/J7girjpym3SAGt3zXGScmi)
- **Note:** independent analysis, not produced by or affiliated with Canada Post.

### ✈️ U.S. flight delay pipeline, January to July 2026

An end-to-end Python and SQL pipeline that loads seven monthly Bureau of Transportation Statistics files (4,120,342 domestic flights, 13 carriers, 357 airports) into SQLite, runs 12 data-quality checks, and recomputes on-time rates for every carrier and month. All 96 recomputed figures match the Department of Transportation's published Air Travel Consumer Report within its rounding band. A Simpson's paradox check of all 78 carrier pairs found rankings that reverse at comparable airports.

- **Code, SQL and README:** [View the code, SQL and README on GitHub](https://github.com/Zosmano/flight-delay-pipeline)

### ⚡ Canadian household energy, 2011 to 2021

A Power BI dashboard on Statistics Canada data for 10 provinces, with slicer filtering and DAX measures built around a 70.84 GJ national benchmark. A matching SQL analysis of 989 provincial observations ranks provinces against that benchmark (Alberta is highest at +11.4 GJ) and reproduces the dashboard figure, so the two tools cross-check each other.

- **Dashboard:** [Open the interactive Power BI dashboard](https://app.powerbi.com/view?r=eyJrIjoiMWFlMjQxZTUtNTVlYi00MjMzLWIzODAtMzk3MjE3ZDQyZjE3IiwidCI6ImM3ZTc5YjlkLWVjZTktNDEzMy04NzQzLWI2Y2FkMjZjNTc0ZiIsImMiOjEwfQ%3D%3D)
- **SQL analysis:** [View the SQL analysis on GitHub](https://github.com/Zosmano/Household-Energy_SQL_Analysis)

### 🌍 Global Democratic Governance dashboard

A three-page Power BI report relating each country's governance variables (Gini index, Freedom House scores, internet penetration) to its participatory-democracy cases and preferred methods. A Power Query pipeline cleans and normalizes entries across 2.26K+ cases.

- **Dashboard:** [Open the interactive Power BI dashboard](https://app.powerbi.com/view?r=eyJrIjoiZmFlMDhlMTEtOWE3NC00ZTRhLWFjNjEtZGY2ZGRiOGVkMGVlIiwidCI6ImM3ZTc5YjlkLWVjZTktNDEzMy04NzQzLWI2Y2FkMjZjNTc0ZiIsImMiOjEwfQ%3D%3D)

### 📊 Executive Portfolio Diagnostic Suite (1M+ records)

An executive-level Tableau PMO diagnostic dashboard on a synthetic enterprise dataset of 1M+ records across 50 projects. It gives visibility into resource utilization, cost variance and multi-year project burn-down trends.

- **Live dashboard:** [View the interactive Tableau Public dashboard](https://public.tableau.com/app/profile/osman.zakaria/viz/ExecutiveDashboard_Tableau_17897535940690/PortfolioPerformanceCostVariance)
- **Key features:**
  - Burn-down trends: multi-year line analysis comparing Actual Cost, Earned Value and Planned Value.
  - Cost variance analysis: portfolio-level breakdown of cost variances with custom scaled numeric formatting.
  - Executive design: scaled numbers, right-aligned metrics and minimal visual noise for decision-making.
- **Data:** 1,000,000+ synthetic records. **Tools:** Tableau Desktop and Public, data prep scripts.

---

## 🔬 Research

### A Macro-micro–Hybrid Ensemble Framework for Institutional Governance 

A hybrid CatBoost and XGBoost ensemble that classifies 2.26K+ global participatory-democracy cases from Participedia data and forecasts annual case volumes through 2030. Accuracy is 76%, compared with baseline models near 52%.

- **Technologies:** Python, SQL, Power BI, predictive and statistical modelling.
- **Status:** paper submitted to Taylor & Francis (September 2026), under review.

### Leveraging Artificial Intelligence and Big Data for African Tax Reform

A research paper investigating AI adoption in Africa's informal sector and emerging markets. It integrates geospatial, mobile transaction and economic data in predictive models, built in Python and Power BI, to assess tax revenue potential and to identify digital infrastructure gaps, creating a scalable framework for tax collection. A field study with financial professionals and informal sector employees, conducted through interviews and focus groups with informed consent, informs an AI-powered tax roadmap.

- **Technologies:** Python, Power BI, geospatial data, economic data, statistical modelling.
- **Status:** accepted by the Global Conference Alliance Inc. (March 2025); in-person presentation pending.

---

## 📫 Get in touch

[Visit my portfolio](https://zosmano.github.io) · [Connect on LinkedIn](https://www.linkedin.com/in/osmanzakaria) · zosman50@gmail.com
