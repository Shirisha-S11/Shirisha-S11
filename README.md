# Hi, I'm Shirisha 👋

### Data Analyst | SQL · Power BI · Tableau · Looker · Excel · BigQuery · Python · Machine Learning · Data Visualization

I'm a Data Analyst with **5+ years of experience** turning messy data into stories that actually make sense. Whether it's building interactive dashboards, writing SQL to uncover hidden patterns, training machine learning models, or cleaning up a chaotic dataset — I enjoy the whole process from raw numbers to real decisions.

What sets my work apart is that I don't just build dashboards. I dig into *why* something is happening, not just *what* the numbers say. I've found system-level delivery failures hiding behind supplier data, discovered that air freight was slower than sea freight, and used ML to identify 308 high-risk customers before they churned.

My work lives at the intersection of data and decision-making, and I'm always looking for ways to make analytics more intuitive and impactful for the people using it.

---

## 🛠️ Skills & Tools

**Business Intelligence & Visualization**
- Power BI — Data Modeling, DAX, Interactive Dashboards
- Looker Studio — Live BigQuery-connected Dashboards
- Tableau — Predictive & Churn Analytics Dashboards
- Microsoft Excel — Power Query, Pivot Tables, Data Models, Slicers, Charts

**Data & Analytics**
- SQL — Data Extraction, Aggregations, Joins, Trend Analysis, Window Functions
- Google BigQuery — Data Warehousing, Query Optimization, ML in SQL
- BigQuery ML — ARIMA Time Series Forecasting (entirely in SQL)
- Python — pandas, scikit-learn, XGBoost, SHAP, Jupyter Notebooks

**Machine Learning & Modelling**
- XGBoost — Classification & Churn Prediction
- SHAP — Model Explainability & Feature Importance
- ARIMA / ARIMA_PLUS — Demand Forecasting
- Class Imbalance Handling, Threshold Tuning, Model Evaluation (AUC-ROC, Recall, Precision)

**Core Competencies**
- Data Cleaning & Transformation
- Business Intelligence Reporting
- End-to-End ML Pipeline Development
- Data Visualization & Storytelling
- Supply Chain & Operations Analytics
- Customer Analytics & Retention Strategy

---

## 📂 Featured Projects

---

### 🔮 Customer Churn Prediction
> *Python · XGBoost · SHAP · pandas · scikit-learn · Tableau Public · Jupyter*

[📊 View Live Tableau Dashboard](https://public.tableau.com/app/profile/shirisha.suruguru3037/viz/CustomerChurnPredictionDashboard_17737046092880/CustomerChurnDashboard)

Built an end-to-end machine learning pipeline to predict which telecom customers are likely to cancel their subscription — so the business can act before they leave.

**Model Performance**
| Metric | Score |
|--------|-------|
| AUC-ROC | 0.8389 |
| Recall (churners) | 0.78 |
| Precision (churners) | 0.56 |
| High-risk customers identified | 308 |

**Key Findings**
- Customers on month-to-month contracts with under 12 months tenure are **3x more likely to churn**
- Churned customers pay on average **$13/month more** than retained customers
- Top 3 churn drivers: tenure, contract type, and monthly charges
- Used SHAP values to translate model output into clear, actionable business recommendations
- Identified 308 high-risk customers — targeting even 10% for retention recovers significant monthly recurring revenue

**What I built**
- Full ETL pipeline from raw CSV to clean, modelling-ready data
- XGBoost classifier with class imbalance handling via `scale_pos_weight`
- SHAP beeswarm analysis to explain individual predictions
- Threshold tuning to match real-world retention budget constraints
- Published Tableau dashboard connected to final scored dataset

---

### 🔗 Supply Chain Analytics
> *SQL · Google BigQuery · BigQuery ML · Looker Studio · ARIMA Forecasting · GitHub*

[📊 View Live Dashboard](https://datastudio.google.com/reporting/60edeaa3-823a-458c-a5f7-c6f63a481b86)

An end-to-end supply chain analytics project built on 180,000 real orders from a global sporting goods distributor — from raw data to SQL to a machine learning demand forecast, using no Python whatsoever.

I expected to find that certain suppliers were causing late deliveries. What I actually found was that every single supplier, region, and warehouse had almost identical late delivery rates — all clustered between 56–61%. When everything fails the same way, it's not a supplier problem. It's a system problem.

**Key Findings**
- Late delivery rates of 56–61% were consistent across all suppliers, regions, and warehouses — a system configuration issue, not a people issue
- AIR freight had an **87% late rate** while SEA freight arrived early on average — the business was paying a premium for a slower, less reliable service
- The Perfect Fitness Rip Deck was selling 70 units/day approaching stockout, while the Polar Loop Activity Tracker moved just 0.35 units/day — a completely misaligned inventory strategy
- Golf Bags & Carts had the **highest gross margin at 19.1%** but ranked 49th in revenue — a potential undiscovered commercial opportunity
- Identified a data quality issue in October 2017 (95% demand drop across all categories) and excluded it from the forecast model

**What I built**
- 12 SQL analytics queries covering delivery performance, inventory health, supplier scorecards, revenue analysis, cost optimization, and warehouse efficiency
- BigQuery ML ARIMA_PLUS demand forecast model trained entirely in SQL — no Python, no separate ML infrastructure
- 4 Looker Studio dashboards connected live to BigQuery: Executive Overview, Inventory Health, Supplier Performance, and Cost & Demand Forecast
- Deduplication view to cleanly handle shipments table duplicates

**Dashboards**
| Dashboard | Business Question |
|-----------|-------------------|
| Executive Overview | Where are we losing money and why? |
| Inventory Health | What's running out vs sitting still? |
| Supplier Performance | Why is 57% of everything late? |
| Cost & Demand Forecast | Where can we save and what's coming? |

---

### 📱 Meta Ad Performance Analysis
> *Power BI · DAX · Power Query*

Built a Power BI dashboard to analyze advertising performance across Facebook and Instagram, helping stakeholders understand what's working — and what's not.

- Campaign reach, impressions, and engagement metrics
- Audience segmentation by age, gender, and location
- Conversion funnel analysis across ad formats
- Side-by-side ad format performance comparison

---

### 📞 Call Center Performance Dashboard
> *Microsoft Excel · Pivot Tables · Data Model · Slicers · Charts*

Analyzed call center operations and customer data to uncover performance gaps and revenue opportunities across a large agent team.

- Identified top revenue-generating representatives
- Compared customer satisfaction scores across agents
- Tracked monthly demand trends over time
- Broke down revenue contribution by city and customer demographics

---

### 🛒 Sales Performance Dashboard
> *SQL · Aggregations · Joins · Trend Analysis*

Used SQL to dig into sales data and surface the trends that matter most — from top products to underperforming regions.

- Total sales and revenue broken down by product category
- Regional performance comparison
- Month-over-month sales trend analysis
- Top-performing products and highest-value customers

---

## 📬 Let's Connect

I'm always open to interesting data projects, collaborations, or just a good conversation about analytics.

- 🔗 [LinkedIn](https://www.linkedin.com/in/shirishas11)
- 📧 [Shirishasd11@gmail.com](mailto:Shirishasd11@gmail.com)
