# 🛒 SUPERMART GROCERY SALES ANALYSIS

This repository presents a **comprehensive data analysis and visualization of Supermart grocery sales** using **Python, Pandas, Matplotlib, and Seaborn**.  
The project uncovers insights about **city-wise performance, category trends, year-over-year growth, and profitability**.  

🔗 [Project Repository](https://github.com/SainiBimal/Supermart-Analysis)

---

## 📊 Dashboard & Visuals

![Dashboard](https://github.com/user-attachments/assets/your-dashboard-image.png)

---

## 📌 Project Overview

- Dataset: **9,994 transactions** across **11 features** (`Order ID, Customer Name, Category, Sub-Category, City, Order Date, Region, Sales, Discount, Profit, State`)  
- Timeframe: **2015 – 2018**  
- Goal: Analyze **sales, profit distribution, category contribution, and city-level trends** to identify **growth drivers and customer behavior**.  

---

## 🔍 Key Analyses & Insights

### 📈 Univariate Analysis
- **Sales Distribution**: Right-skewed with most sales < ₹2000.  
- **Profit Distribution**: Majority clustered between ₹0–₹500, few high-profit outliers.  

### 📊 Bivariate Analysis
- **Region vs Sales**: Northern & Western regions showed higher median sales.  
- **City-wise Sales**: Top contributors: **Kanyakumari, Vellore, Bodi, Tirunelveli**.  
- **City & Category Sales**: Category mix varied by city (e.g., Kanyakumari dominated in *Oil & Masala*).  

### 🥦 Category Insights
- **Top Categories by Sales**:
  - 🥇 Eggs, Meat & Fish – ₹2.26M  
  - 🥈 Snacks – ₹2.23M  
  - 🥉 Food Grains – ₹2.11M  
- Visualization: Pie chart for % contribution across 7 categories.  

### 📅 Time-Series Trends
- **Yearly Growth**:
  - 2015: ₹2.97M  
  - 2016: ₹3.13M  
  - 2017: ₹3.87M  
  - 2018: ₹4.97M 🚀  
- **Monthly Trends**: Seasonal spikes in November–December.  
- **Profit Trends**: Closely aligned with sales peaks, with highest profits in 2018.  

### 📊 Advanced Analysis
- **Outliers**: Sales above ₹4979 detected as high-value outliers.  
- **Quintile Segmentation**:
  - Customers grouped into Q1–Q5 by Sales & Profit.  
  - Cross-tab heatmap shows correlation between high Sales & high Profit clusters.  
- **Heatmaps**:
  - Category vs Profit/Sales matrix.  
  - Monthly-Year Sales pivot comparison.  

---

## 📁 Repository Files

| File | Description |
|------|-------------|
| `Supermart.ipynb` | Main Jupyter Notebook with full analysis |
| `Supermart Grocery Sales Analysis.pdf` | Final Presentation |
| `supermart.csv` | Dataset used for analysis |
| `README.md` | Project documentation (this file) |

---

## 🚀 Tools & Technologies

- **Python**: Data processing & visualization  
- **Pandas / NumPy**: Data wrangling, feature engineering  
- **Matplotlib / Seaborn**: Plots & heatmaps  
- **Google Colab**: Development environment  

---

## 📌 Business Insights

- 📍 **Kanyakumari, Vellore, Bodi** emerged as **top sales cities**.  
- 🥩 **Eggs, Meat & Fish** & 🍪 **Snacks** drive maximum revenue.  
- 📈 Consistent **year-on-year sales growth** from 2015–2018.  
- 🔍 **High discounting regions** showed lower profits despite higher sales.  
- 🏷️ Outlier analysis helped segment premium customers (Q5 group).  

---

## 🔮 Future Scope

- Predictive modeling for **sales forecasting**.  
- Customer segmentation using **clustering (K-Means)**.  
- Building a **Power BI / Tableau dashboard** for business users.  
- Integrating SQL queries for faster aggregation.  

---

![Visitor Count](https://komarev.com/ghpvc/?username=SainiBimal&style=flat-square)

---

## 🙌 Author

**BIMAL KUMAR SAINI**  
Data Analyst Intern  
📧 bimalsaini333@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/bimalsaini333/) | [GitHub](https://github.com/SainiBimal)
