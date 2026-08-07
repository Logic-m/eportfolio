<div align="center">

<img src="assets/banner.png" alt="Portfolio Banner" width="100%"/>

<img src="assets/profile.jpg" alt="Ofilwe Gabaitse" width="130" style="border-radius:50%;"/>

# Ofilwe Gabaitse
### Data Analyst

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-LINKEDIN)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your-email@example.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR-USERNAME)

<p>
  <a href="#about">About</a> •
  <a href="#tools">Tools</a> •
  <a href="#projects">Projects</a> •
  <a href="#codveda-internship">Codveda Internship</a> •
  <a href="#contact">Contact</a>
</p>

</div>

---

## About

I'm a Business Intelligence and Data Analytics graduate with a passion for turning raw data into meaningful insight. My work sits at the intersection of analytical thinking and practical problem-solving — whether that's writing clean Python pipelines, building interactive dashboards, or applying machine learning to real-world questions.

This portfolio showcases projects across a range of complexity, from foundational data cleaning to predictive modeling, time series analysis, clustering, and dashboard design.

<div align="center">

| 🎯 Focus | 🧠 Approach | 📈 Output |
|:---:|:---:|:---:|
| Data cleaning → insight → decision | Statistically grounded, reproducible analysis | Dashboards, models, reports |

</div>

---

## Tools

<div align="center">

<img src="https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
<br/>
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square"/>
<img src="https://img.shields.io/badge/Seaborn-3776AB?style=flat-square"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/statsmodels-4B8BBE?style=flat-square"/>
<img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white"/>

</div>

---

## Projects

### 📊 Sales Dashboard: Order-Level Sales Analysis — Excel

<table>
<tr>
<td width="45%">

<img src="projects/sales-dashboard/dashboard_preview.png" alt="Sales Dashboard"/>

</td>
<td width="55%">

**Company Sales Dashboard**

This dashboard gives a company sales manager a single-screen view of overall sales performance, replacing the need to dig through raw order data or multiple PivotTables.

At the top, four KPI cards summarize **Total Revenue (P2.45M)**, **Total Orders (2,000)**, **Quantity Sold (5,552)**, and **Average Order Value (P1.23K)**. Below that, a Revenue by Month line chart shows seasonal trends across the year, alongside a Revenue by Sales Channel donut chart showing Online (32%) as the top-performing channel.

The middle row breaks performance down further with Top 5 Products by Revenue (led by the Gaming Laptop), Revenue by Region (North and Central leading), and Revenue by Product Category (Computers dominating at P1M).

Slicers on the left let users filter by Sales Channel, Region, Product Category, and Customer Type, while timeline controls at the bottom allow filtering by Date, Quarter, Day, and Month — making the dashboard fully interactive.

**Built with:**
<img src="https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white"/>

**[View Report →](https://github.com/YOUR-USERNAME/sales-dashboard-excel)**

</td>
</tr>
</table>

---

### 📞 Telecom Churn Dashboard — Power BI

<table>
<tr>
<td width="45%">

<img src="projects/telecom-churn/dashboard_preview.png" alt="Telecom Churn Dashboard"/>

</td>
<td width="55%">

This Power BI dashboard project analyzed **667 telecom customers (14.2% overall churn rate)** to identify which characteristics and behaviors drive churn, and the clearest signals to emerge were plan type and support-call frequency.

Customers with an international plan churned at roughly **35%** versus ~10% for those without — making it the single strongest predictor in the dashboard, with customers without a voice mail plan churning at roughly double the rate of those with one.

Customer service calls proved to be an equally strong indicator, with churn rate climbing sharply once a customer reached 3+ calls, and dropping steadily as call counts decreased. Tenure also mattered: newer and mid-tenure customers (0–150 days) churned more than those with 150+ days on the account, suggesting retention risk is concentrated early in the customer lifecycle.

By contrast, total usage minutes showed no strong standalone relationship with churn — churned customers were scattered fairly evenly across the full usage range rather than clustering at high or low extremes, indicating usage volume alone isn't a reliable churn predictor and is more useful when combined with service-call frequency or plan type.

**Together, these findings point retention efforts toward international-plan holders and customers with 3+ service calls as the highest-priority segments, with early-tenure customers as a secondary focus area.**

**Built with:**
<img src="https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black"/>

**[View Report →](https://github.com/YOUR-USERNAME/telecom-churn-powerbi)**

</td>
</tr>
</table>

---

### 🏠 Level 1 House Price Prediction: Exploratory Data Analysis

<table>
<tr>
<td width="45%">

<img src="projects/house-price-eda/eda_preview.png" alt="House Price EDA"/>

</td>
<td width="55%">

This project is a two-stage data science workflow on the 506-record **Boston Housing dataset**:

1. **Cleaning/preprocessing pipeline** — loads the raw whitespace-delimited CSV, handles missing values and duplicates defensively, standardizes formats/types, and outputs a cleaned CSV.
2. **Exploratory data analysis stage** — uses pandas, numpy, matplotlib, and seaborn to generate summary statistics, distribution and relationship visualizations, and a full correlation analysis.

**Key findings:** `RM` (rooms per dwelling) correlates positively with median home value (`MEDV`), while `LSTAT`/`PTRATIO` correlate negatively with it. The original dataset itself turned out to have no missing values or duplicates.

**Built with:**
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square"/>
<img src="https://img.shields.io/badge/Seaborn-3776AB?style=flat-square"/>

**[View Full Notebook →](https://github.com/YOUR-USERNAME/house-price-eda)**

</td>
</tr>
</table>

---

### 📈 Basic Data Visualization

<table>
<tr>
<td width="45%">

<img src="projects/basic-data-viz/viz_preview.png" alt="Basic Data Visualization"/>

</td>
<td width="55%">

This project (Task 3 of the Codveda Technologies data analytics internship) builds on the previously cleaned Boston housing dataset to create basic visualizations using Python, pandas, matplotlib, and seaborn, including:

- A **bar plot** comparing average home value for riverside vs. non-riverside properties
- A **line chart** tracking home values across building-age groups
- A **scatter plot** of rooms vs. home value, colored by river proximity

All plots are exported as image files for reporting.

**Built with:**
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat-square"/>
<img src="https://img.shields.io/badge/Seaborn-3776AB?style=flat-square"/>

**[View Full Notebook →](https://github.com/YOUR-USERNAME/basic-data-visualization)**

</td>
</tr>
</table>

---

## Codveda Internship

<div align="center">

![Progress](https://img.shields.io/badge/Levels_Completed-2%2F3-brightgreen?style=for-the-badge)
![Tasks](https://img.shields.io/badge/Tasks_Completed-6-blue?style=for-the-badge)

</div>

The following projects were completed as part of a data analytics internship with **Codveda Technologies**, a company specializing in IT solutions including AI/ML automation and data analysis. The internship was structured across three progressive levels; the projects below reflect work done across all three.

<details>
<summary><b>🟢 Level 1: Foundational Analytics</b></summary>
<br/>

| Task | Status | Link |
|---|:---:|---|
| Data Cleaning and Preprocessing | ✅ | [View →](https://github.com/YOUR-USERNAME/codveda-level1-data-cleaning) |
| Exploratory Data Analysis (EDA) | ✅ | [View →](https://github.com/YOUR-USERNAME/codveda-level1-eda) |
| Basic Data Visualization | ✅ | [View →](https://github.com/YOUR-USERNAME/codveda-level1-data-viz) |

</details>

<details open>
<summary><b>🟡 Level 2: Intermediate Analysis</b></summary>
<br/>

| Task | Status | Description | Link |
|---|:---:|---|---|
| Regression Analysis | ✅ | Linear regression predicting AAPL close price from open price — **R² = 0.997** | [View →](https://github.com/YOUR-USERNAME/codveda-level2-regression) |
| Time Series Analysis | ✅ | Trend/seasonality decomposition of AAPL (2014–2017) + moving-average smoothing | [View →](https://github.com/YOUR-USERNAME/codveda-level2-timeseries) |
| Clustering Analysis (K-Means) | ✅ | Grouped 485 stocks into 4 risk/return clusters via K-Means + elbow method | [View →](https://github.com/YOUR-USERNAME/codveda-level2-clustering) |

<table>
<tr>
<td><img src="projects/codveda-level2/task1_regression_analysis.png" width="100%"/><p align="center"><sub>Regression: Actual vs. Predicted</sub></p></td>
<td><img src="projects/codveda-level2/task2_decomposition.png" width="100%"/><p align="center"><sub>Time Series Decomposition</sub></p></td>
<td><img src="projects/codveda-level2/task3_clusters_scatter.png" width="100%"/><p align="center"><sub>Risk vs. Return Clusters</sub></p></td>
</tr>
</table>

</details>

<details>
<summary><b>🔴 Level 3: Advanced Projects</b></summary>
<br/>

| Task | Status | Link |
|---|:---:|---|
| Predictive Modeling (Classification) | ⬜ | [View →](https://github.com/YOUR-USERNAME/codveda-level3-classification) |
| Building Dashboards with Power BI | ⬜ | [View →](https://github.com/YOUR-USERNAME/codveda-level3-dashboards) |
| Sentiment Analysis (NLP) | ⬜ | [View →](https://github.com/YOUR-USERNAME/codveda-level3-nlp) |

</details>

---

## Contact

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR-LINKEDIN)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your-email@example.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR-USERNAME)

`#CodvedaJourney` `#CodvedaExperience` `#FutureWithCodveda` `#CodvedaAchievements` `#CodvedaProjects`

<sub>Built by Ofilwe Gabaitse • Last updated 2026</sub>

</div>
