<div align="center">

<img src="your-photo.jpg" width="150" height="150" style="border-radius: 50%;" alt="Profile photo" />

# Your Name Here

### Data Analyst | Power BI & Python

Turning raw data into decisions — dashboards, EDA, and statistical storytelling.

📍 Your City, Country &nbsp;|&nbsp; 📧 your.email@example.com &nbsp;|&nbsp; 🔗 [LinkedIn](https://linkedin.com/in/yourprofile) &nbsp;|&nbsp; 💼 [Portfolio Site](https://yourwebsite.com)

[![GitHub](https://img.shields.io/badge/GitHub-Logic--m-181717?style=for-the-badge&logo=github)](https://github.com/Logic-m)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/yourprofile)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)

</div>

<br>

> ✏️ **Add a short bio here** — 2–3 sentences on who you are, your background, and what kind of analytics work excites you. e.g. *"I'm a data analyst focused on turning messy transactional and behavioral data into dashboards and insights that drive real decisions. Currently building my skills in Power BI, DAX, and Python-based EDA."*

---

<div align="center">

## 🧰 Skills & Tools

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=plotly&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)

`Exploratory Data Analysis` · `Data Cleaning` · `Data Visualization` · `Statistical Correlation Analysis` · `Customer Segmentation`

</div>

---

## 📊 Project 1 — Customer Shopping Behavior Dashboard

<table>
<tr>
<td width="55%" valign="top">

**Power BI &nbsp;|&nbsp; Retail Analytics &nbsp;|&nbsp; Customer Segmentation**

An interactive Power BI dashboard analyzing **3,900 retail transactions** to uncover revenue drivers, customer segments, and category performance trends. Built for stakeholders who need to move from a full customer base to an actionable, filtered segment in a few clicks.

**What it does:**
- Consolidates purchasing patterns across **product category, demographics, subscription status, and shipping preferences**
- KPI cards for **Total Revenue, Total Customers, and Average Order Value**
- Category performance via clustered column charts (revenue *and* transaction volume)
- Payment method and seasonal breakdowns via bar charts
- Four cross-filtering slicers: **Gender, Category, Subscription Status, Shipping Type**

</td>
<td width="45%" valign="top">

<img src="Screenshot 2026-08-12 172008.png" width="100%" alt="Customer Shopping Behavior Dashboard" />

<sub>Dashboard filtered to male, subscribed customers — 1,053 customers generating $62.65K in revenue.</sub>

</td>
</tr>
</table>

**💡 Key insight from the segment analysis**

Filtering to male + subscribed customers reveals that **AOV stays flat** ($59.49 vs. $59.76 overall) — meaning subscription revenue is driven by *volume and retention*, not bigger baskets. Category rankings (Clothing → Accessories → Footwear → Outerwear) and seasonality (Fall/Summer strongest) stay consistent across segments, but **payment method mix shifts** — a thread worth digging into further.

**DAX highlights:**
```DAX
Total Revenue = SUM(customer_shopping_behavior[Purchase Amount (USD)])
Average Order Value = DIVIDE([Total Revenue], [Total Transactions])
Revenue per Customer = DIVIDE([Total Revenue], [Total Customers])
```
Plus supporting measures for discount/promo impact, loyalty & repeat-purchase behavior, satisfaction scoring, and demographic breakdowns.

**Planned next steps:** a Loyalty & Satisfaction page, a geographic revenue view, calendar-ordered seasonality, and expanded slicers (Payment Method, Discount Applied).

<div align="center">

[![View Repository](https://img.shields.io/badge/View_Full_Project-181717?style=for-the-badge&logo=github)](https://github.com/Logic-m/customer-behavior-power-bi)

</div>

---

## 🏘️ Project 2 — Boston Housing: EDA & Data Visualization

**Python &nbsp;|&nbsp; pandas · matplotlib · seaborn &nbsp;|&nbsp; Codveda Data Analytics Internship**

A full exploratory data analysis of the classic **Boston Housing dataset**, covering data cleaning, statistical exploration, and visual storytelling to identify what actually drives median home value (`MEDV`).

### 🧹 Data Cleaning
Loaded the raw dataset, handled missing values, removed duplicates, and standardized formats → produced `cleaned_house_data.csv`.

### 🔍 Exploratory Data Analysis

<table>
<tr>
<td width="50%" align="center">
<img src="eda_histograms.png" width="100%" alt="Histograms of All Features" />
<sub>Most features are right-skewed (CRIM, LSTAT); RM and MEDV are near-normal</sub>
</td>
<td width="50%" align="center">
<img src="eda_boxplot_medv.png" width="100%" alt="Boxplot of MEDV" />
<sub>Median home value clusters around $21–22K, with high-value outliers above $37K</sub>
</td>
</tr>
</table>

<div align="center">
<img src="eda_correlation_heatmap.png" width="70%" alt="Correlation Heatmap" />
</div>

**Strongest correlations with house price (MEDV):**

| Feature | Correlation | Interpretation |
|:---:|:---:|---|
| `RM` (rooms) | **+0.70** | More rooms → higher price |
| `LSTAT` (% lower status) | **−0.74** | Higher % lower-status population → lower price |
| `PTRATIO` | −0.51 | Higher pupil-teacher ratio → lower price |
| `INDUS` | −0.48 | More industrial land → lower price |
| `TAX` | −0.47 | Higher tax rate → lower price |
| `NOX` | −0.43 | More pollution → lower price |

<div align="center">
<img src="eda_scatter_rm_medv.png" width="60%" alt="RM vs MEDV Scatter" />
<br><sub>Clear positive linear relationship between room count and home value.</sub>
</div>

### 📈 Visualization Deep Dives

<table>
<tr>
<td width="33%" align="center">
<img src="viz_barplot_chas_medv.png" width="100%" alt="CHAS Barplot" />
<br><sub><b>Charles River proximity:</b> Riverside homes average ~$28K vs. ~$22K for others.</sub>
</td>
<td width="33%" align="center">
<img src="viz_scatter_tax_medv.png" width="100%" alt="TAX vs MEDV Scatter" />
<br><sub><b>Property tax vs. price:</b> High-tax cluster (TAX≈666) spans a wide, often lower, price range.</sub>
</td>
<td width="33%" align="center">
<img src="viz_linechart_lstat_medv.png" width="100%" alt="LSTAT vs MEDV Line Chart" />
<br><sub><b>Socioeconomic trend:</b> Prices fall sharply as % lower-status population rises.</sub>
</td>
</tr>
</table>

**Key takeaways:** Room count and neighborhood socioeconomic status are the strongest predictors of price; river-adjacent location adds a premium; crime, tax, industrial density, and pupil-teacher ratio all correlate with lower values. The cleaned dataset is ready for predictive modeling (regression) in later project stages.

<div align="center">

[![View Repository](https://img.shields.io/badge/View_Full_Project-181717?style=for-the-badge&logo=github)](https://github.com/Logic-m/stock-Analytics)

</div>

---

<div align="center">

## 📬 Let's Connect

If any of these projects are relevant to a role or collaboration you have in mind, I'd love to hear from you.

[![Email](https://img.shields.io/badge/Email-your.email@example.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:your.email@example.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect_with_me-0A66C2?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/yourprofile)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github)](https://github.com/Logic-m)

<sub>⭐ If you found these projects interesting, consider starring the repos!</sub>

</div>

---

> **Setup notes**
> 1. Replace `your-photo.jpg` at the top with your actual photo, placed in this repo's root (a square image ~400×400px works best).
> 2. Fill in your **name, bio, location, email, and social links** in the header and contact section above.
> 3. Make sure the chart/screenshot images (`Screenshot 2026-08-12 172008.png`, `eda_histograms.png`, `eda_boxplot_medv.png`, `eda_correlation_heatmap.png`, `eda_scatter_rm_medv.png`, `viz_barplot_chas_medv.png`, `viz_scatter_tax_medv.png`, `viz_linechart_lstat_medv.png`) are in this repo's root, or update the paths if you place them in an `/images` folder.
> 4. GitHub does not render `<style>` blocks or custom CSS in READMEs — this layout uses supported HTML tags (`<div align>`, `<table>`, `<img width>`) and [shields.io](https://shields.io) badges to achieve a styled look that works reliably.
