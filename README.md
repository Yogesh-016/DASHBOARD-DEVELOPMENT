# 📊 Superstore – Sales & Profit Analysis Dashboard (Power BI)

---

## 🏢 Internship Details

| Field | Details |
|---|---|
| **Company** | CODTECH IT SOLUTIONS |
| **Name** | Yogesh S |
| **Intern ID** | CTIS3967 |
| **Domain** | Data Analysis |
| **Duration** | 4 Weeks |
| **Mentor** | Neela Santosh |

---

## 📌 Project Overview

This project focuses on analyzing **sales performance**, **profitability**, **customer segments**, and **regional trends** using the Sample Superstore dataset. The dashboard is designed as a **single-page interactive Power BI report** to provide quick and meaningful business insights.

---

## 📂 Dataset

- **Source:** Sample Superstore Dataset
- **Records:** Order-level sales data

### Key Fields

| Field | Description |
|---|---|
| Order Date / Ship Date | Temporal order information |
| Category / Sub-Category / Product | Product hierarchy |
| Region / State | Geographic data |
| Sales / Profit / Quantity / Discount | Financial metrics |

---

## 🎯 Objectives

- Analyze overall sales and profit performance
- Identify top-performing categories and sub-categories
- Understand customer segment contribution
- Analyze regional and state-wise sales
- Track monthly sales trends

---

## 📊 Key KPIs

| KPI | Description |
|---|---|
| 📦 Total Orders | Count of distinct orders |
| 💰 Total Sales | Sum of all sales |
| 📈 Total Profit | Sum of all profit |
| 🧮 Profit Margin | Profit as a % of sales |
| 🔢 Total Quantity Sold | Sum of all quantities |

---

## 📈 Dashboard Features

- **Sales by Category** – Compare major product categories
- **Sales by Sub-Category** – Identify top and low-performing products
- **Sales by Segment** – Consumer, Corporate, Home Office analysis
- **Monthly Sales Trend** – Time-based performance analysis
- **State-wise Sales Map** – Geographic distribution of sales
- **Interactive Slicers** – Region and Segment filters

---

## 🧮 DAX Measures Used

```dax
Total Sales    = SUM('Sample Superstore'[Sales])
Total Profit   = SUM('Sample Superstore'[Profit])
Total Quantity = SUM('Sample Superstore'[Quantity])
Total Orders   = DISTINCTCOUNT('Sample Superstore'[Order ID])
Profit Margin  = DIVIDE([Total Profit], [Total Sales])
```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard creation & visualization |
| DAX | Custom measures and calculations |
| Power Query | Data transformation & cleaning |
| Excel / CSV | Dataset source |

---

## 📌 Key Insights

- 💻 **Technology** category contributes the highest sales
- 👥 **Consumer** segment generates the largest revenue share
- ⚠️ Certain sub-categories show **high sales but low profit**
- 📆 Sales show a **noticeable increase towards year-end**
- 🗺️ Regional performance **varies significantly** across states

---

## 📷 Dashboard Preview

![Dashboard Preview](https://github.com/user-attachments/assets/7f2d63b2-9eac-41f7-ad3e-fb0ce286f320)

---

## 🚀 Conclusion

This dashboard provides a **clear, data-driven overview** of business performance and helps stakeholders make informed decisions related to:

- Sales strategy
- Product focus
- Regional planning

---

## 👤 Author

**Yogesh S**  
Aspiring Data Analyst | Power BI | Data Analytics

---

> 📝 *This project was completed as part of a Data Analysis internship at CODTECH IT SOLUTIONS.*
