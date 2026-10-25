# Manas Dhotre

### Data Analyst · SQL · Python · Visualization · Machine Learning Enthusiast

I turn raw data into decisions: finding out **why** something is happening and **what to do about it**. I analyze business datasets, build clear visualizations, and use machine learning where it genuinely helps answer the question.

<!-- OPTIONAL: announce your role by uncommenting and editing the next line
📌 Data Analyst @ <Company Name> · joining <Month Year>
-->

| | |
|---|---|
| 🎯 **Focus** | Business and product analytics (quick commerce, food delivery, retail) |
| 🛠 **Core tools** | SQL (MySQL, SQLite) · Python (pandas, NumPy) · Plotly · scikit-learn |
| 🎓 **Education** | B.E. Computer Science Engineering, Punyashlok Ahilyadevi Holkar Solapur University (2023 to 2027) |
| 📍 **Based in** | Pune, India |
| 📫 **Contact** | [manasdhotre995@gmail.com](mailto:manasdhotre995@gmail.com) · [LinkedIn](https://www.linkedin.com/in/manas-dhotre) |

---

## Impact snapshot

- 📦 Analyzed **1,000,000 order records** (947,752 after cleaning) across **8 quick-commerce platforms** and **12 cities**
- ❓ Answered **8 business questions** on revenue, order value, ratings, delivery speed, discounts and city expansion
- 🧹 Cleaned messy data: dropped 52,000 rows with no city, imputed ratings group-wise, capped outliers above Rs. 2,500
- 📈 Built a **KPI dashboard** (Rs. 541M total order value) and an interactive **Plotly efficiency chart**
- 🧠 Built **LLM agents with long-term memory** during the Google/Kaggle 5-Day AI Agents Intensive
- 🔬 Built **ML models** (regression, ensembles, deep learning) with proper evaluation (RMSE, R²)

---

## Skills in action

| Skill | Where I used it |
|---|---|
| Data cleaning and EDA | Quick Commerce Analysis (imputation, outlier capping, binning with `pd.cut`) |
| Metric design (KPIs) | Efficiency score = scaled order volume − scaled delivery time |
| Correlation and segment analysis | Delivery time vs. partner rating (r ≈ −0.003); discounted vs. non-discounted orders |
| Data visualization | KPI dashboard, Plotly bubble chart, matplotlib/seaborn charts |
| Business recommendations | Rule-based city expansion shortlist |
| Predictive modelling | House Sales Prediction (Linear Regression vs. Random Forest) |
| Deep learning | Blood clot detection with VGG-19 |
| LLM agents and evaluation | Farming agent and Multi-Agent Diagnostic Assistant |
| SQL analytics | 🚧 Food-delivery cancellation analysis (in progress, see below) |

---

## Featured analytics project

### 📊 Quick Commerce Platform Analysis
**Business question:** How do quick-commerce platforms compare on revenue, customer experience and delivery, do discounts matter, and where should platforms expand?

![KPI dashboard](https://raw.githubusercontent.com/ManasDhotre/quick-commerce-company-analysis/main/sources/kpi_dashboard.png)

| | |
|---|---|
| **Data** | Public quick-commerce orders dataset (course project): 1,000,000 raw orders across Amazon Now, Big Basket, Blinkit, Dunzo, Flipkart Minutes, Jio Mart, Swiggy Instamart and Zepto |
| **Approach** | Cleaning and imputation → outlier capping → MinMax normalization → correlation and segment analysis → KPI dashboard |
| **Output** | Platform scorecard, discount analysis, city expansion shortlist |
| **Stack** | Python · Pandas · NumPy · Plotly · Matplotlib · Seaborn · scikit-learn |

**What I found:**
- **Swiggy Instamart leads on both revenue (Rs. 76.4M) and average order value (Rs. 645)**; Jio Mart is lowest on both (Rs. 57.1M, Rs. 483). Order counts are almost identical across platforms (about 118,000 each), so the revenue gap comes from **basket size, not volume**.
- **Ratings differ more than expected:** Blinkit is highest (3.58) and Dunzo lowest (2.43). Dunzo is the second-fastest platform (14.2 min), so speed alone does not explain ratings.
- **Delivery time has virtually no link to delivery-partner ratings** (correlation −0.003).
- **Orders with a discount are 49.5% larger on average** (Rs. 712 vs. Rs. 476) with the same items per order (about 10.3), so discounts coincide with higher-value baskets, not more items.
- **Expansion shortlist** (rating ≥ 3.5, delivery ≤ 15 min, above-median volume): Blinkit in Amritsar, Chennai, Gurgaon, Kolkata and Pune, and Zepto in Bengaluru.

🔗 [Repository](https://github.com/ManasDhotre/quick-commerce-company-analysis)

---

## 🚧 In progress

### Food-Delivery Cancellation and Delivery-Time Analysis
**Business question:** Why do orders get cancelled, and which levers reduce cancellations and delays?
**Stack:** SQL (CTEs, window functions) · Python · dashboard
This is where my SQL work will live, with every query documented in the repo.

---

## Machine learning and AI projects

| Project | What it does | Stack |
|---|---|---|
| 🏡 **House Sales Prediction** | Predicts house prices; Linear Regression vs. Random Forest, evaluated with RMSE and R² | Python · scikit-learn |
| 🧬 **Multi-Agent Diagnostic Assistant** (team capstone) | I built the blood report (CBC) analysis agent within a multi-agent diagnostic workflow | Python · LLM agents |
| 🩸 **Blood Clot Detection** | Image classification using VGG-19 | Python · Deep learning |
| 🌾 **Long-Memory Adaptive Farming Agent** | Memory-aware agent that retains context across farming seasons; evaluation pipeline and season-over-season visualizations (Kaggle Kaggriculture capstone) | Python · LLM agents |
| ✍️ **Prompt Master** | Rule-based tool that scores and improves prompts | Python |

---

## How I approach a data problem

1. **Define the decision.** What will someone do differently because of this analysis?
2. **Understand and clean the data.** Nulls, duplicates, outliers, and metric definitions.
3. **Explore.** Segment, compare, and look for patterns before modelling.
4. **Test and model.** Use statistics or ML only where they answer the question.
5. **Communicate.** One clear chart, one clear recommendation, and honest limits.

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=mysql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat&logo=plotly&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/Seaborn-4c72b0?style=flat)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)

**Currently learning:** advanced SQL (window functions, CTEs) · Tableau / Power BI · statistics and A/B testing

---

## Certifications and languages

- **Certifications:** Data Analysis Bootcamp (Udemy) · Prompt Engineering (Udemy) · Git Version Control for Developers (Udemy)
- **Languages:** Marathi (native) · Hindi (professional) · English (professional working) · Japanese (beginner)

---

## Let's connect

Happy to talk about data analytics, ML projects, or breaking into analytics roles.

📫 [Email](mailto:manasdhotre995@gmail.com) · 💼 [LinkedIn](https://www.linkedin.com/in/manas-dhotre) · 🐙 [GitHub](https://github.com/ManasDhotre)
