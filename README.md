# Ofilwe Gabaitse — Data Analyst Portfolio

<img src="./images/profile-photo.png" alt="Ofilwe Gabaitse" width="120"/>

![Portfolio Banner](./images/banner.png)

📊 **Data Analyst** | Business Intelligence & Data Analytics

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](#)
[![Email](https://img.shields.io/badge/Email-Contact-red?style=flat&logo=maildotru)](#)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=flat&logo=github)](#)

---

## About

I'm a completed student in Business Intelligence and Data Analytics with a passion for turning raw data into meaningful insights. My work sits at the intersection of analytical thinking and practical problem-solving, whether that's writing clean Python pipelines, building visual dashboards, or applying machine learning to real-world questions.

This portfolio showcases projects completed across different levels of complexity, from foundational data work to predictive modeling and NLP.

---

## Tools

![Tools Overview](./images/tools-panel.png)

| Tool | Use |
|------|-----|
| ![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black) | Interactive dashboards & DAX modeling |
| ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white) | Data cleaning, analysis, ML |
| ![Excel](https://img.shields.io/badge/-Excel-217346?style=flat&logo=microsoftexcel&logoColor=white) | PivotTables, dashboards, reporting |
| ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat&logo=jupyter&logoColor=white) | Notebook-based EDA & modeling |
| ![GitHub](https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white) | Version control & project hosting |

---

## Projects

### 📈 Sales Dashboard: Order-Level Sales Analysis — Excel

![Sales Dashboard Screenshot](./images/sales-dashboard.png)

A company sales dashboard that manages a single-screen view of overall sales performance, replacing the need to dig through raw order data or multiple PivotTables. Top KPI cards summarize total revenue, quantity sold, and average order value, while charts break down revenue by sales channel, month, product category, region, and customer type — with interactive slicers for full drill-down.

**Built with:** `Excel`
[View Report →](#)

---

### 🏦 Bank Branch Performance Dashboard — Power BI, DAX, Excel

![Bank Branch Performance Dashboard Screenshot](./images/bank-branch-dashboard.png)

An end-to-end Power BI dashboard analyzing performance across 10 bank branches in India, using a star-schema data model with custom DAX measures for Net Profit, NPA %, and Customer Growth %. Includes visualized deposit/loan trends, regional revenue mix, and branch/state-level profitability through bar, line, and donut charts. Iterated on the design by replacing a non-functional geo-map with a clearer state-level bar chart and adding data labels for improved readability.

**Built with:** `Power BI` `Excel` `DAX`
[View Report →](#)

---

### 💼 Codveda Technologies Internship Projects
Completed as part of a virtual data analytics internship with Codveda Technologies, a company specializing in IT solutions including AI/ML automation and data analysis. Structured across three progressive levels:

**Level 1 — Foundational Analytics**
- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Basic Data Visualization

**Level 2 — Intermediate Analysis**
- Regression Analysis
- Time Series Analysis
- Clustering Analysis (K-Means)

**Level 3 — Advanced Projects**
- Predictive Modeling (Classification)
- Building Dashboards with Power BI
- Sentiment Analysis (NLP)

---

### 📞 Telecom Churn Dashboard — Power BI

![Telecom Churn Dashboard Screenshot](./images/telecom-churn-dashboard.png)

A Power BI dashboard that analyzed 667 telecom customers (14.7% overall churn rate) to identify which characteristics and behaviors drive churn, and the clearest signals to emerge were plan type and support call frequency: customers with an international plan churned at roughly 39% versus ~20% for those without, while customers without a voicemail plan churned at roughly double the rate of those with one. Customer service calls proved to be an equally strong risk indicator — churn rate climbed sharply once a customer reached 3+ calls and kept climbing, indicating that usage volume isn't a related churn predictor on its own. Findings support retention efforts toward international-plan holders and customers with 3+ service calls as the highest-priority segments, with early-tenure customers as a secondary focus area.

**Built with:** `Power BI`
[View Report →](#)

---

### 🏠 Level 1 House Price Prediction: Exploratory Data Analysis

![House Price EDA Screenshot](./images/Screenshot%202026-08-12%20172008.png)

A two-stage data science workflow on the 506-record Boston Housing dataset: first a cleaning/preprocessing pipeline handling raw whitespace-delimited CSV, missing values, and duplicates (deferred/typed) that outputs a cleaned CSV, followed by an exploratory data analysis stage using pandas, numpy, matplotlib, and seaborn to generate summary statistics, distribution and relationship visualizations, and correlation analysis. Key findings: RM positively correlated with median home value (MEDV), while LSTAT/PTRATIO negatively correlated with it — the original dataset had no missing values or duplicates.

| | | |
|---|---|---|
| ![Boxplot of MEDV](./images/eda_boxplot_medv.png) | ![Correlation Heatmap](./images/eda_correlation_heatmap.png) | ![Histograms](./images/eda_histograms.png) |
| Boxplot — MEDV | Correlation heatmap | Feature histograms |

![Scatter: RM vs MEDV](./images/eda_scatter_rm_medv.png)
*Rooms (RM) vs. median home value (MEDV)*

**Built with:** `Python` `Pandas` `Matplotlib` `Seaborn`
[View Full Notebook →](#)

---

### 📊 Basic Data Visualization

Building on the previously cleaned Boston housing dataset (Task 3 of the Codveda Technologies internship), this project creates basic visualizations using Python, pandas, matplotlib, and seaborn — including a bar plot comparing average home values for riverside vs. non-riverside properties, a line chart tracking home values across building-age groups, and a scatter plot of room proximity, with all plots exported as high-quality images to a plots/ folder and generated via a single Jupyter notebook that runs on the 506-row, 14-feature cleaned dataset.

| | | |
|---|---|---|
| ![Bar plot: CHAS vs MEDV](./images/viz_barplot_chas_medv.png) | ![Line chart: LSTAT vs MEDV](./images/viz_linechart_lstat_medv.png) | ![Scatter: TAX vs MEDV](./images/viz_scatter_tax_medv.png) |
| Riverside vs. non-riverside (CHAS) home values | Home values by LSTAT | Tax rate vs. MEDV |

---

## Contact

Feel free to reach out via [LinkedIn](#), [Email](#), or [GitHub](#) to connect or discuss data analytics work.

---

*This README serves as a text-based summary of the full visual portfolio site.*
