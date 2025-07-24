# 🧹 Data Cleaning & Sales Insight Generation

**Author:** Mac-John Sindio-Apaun  
**Date:** June 17, 2025  
**Tools Used:** SQL, Power BI  

---

## 🧾 Overview

This project focused on performing deep data cleaning and uncovering sales insights from a messy retail dataset using SQL for transformation and Power BI for visualization. Key business questions included identifying top-performing product categories, optimal discount ranges, and monthly revenue patterns.

---

## 📁 Files Included

- `General_Cleaning_and_Insight_Generation.pdf` – Full project report including SQL steps, charts, and recommendations
- `images/` – Visual charts extracted from Power BI (optional screenshots)

---

## 🔍 Key Cleaning Tasks (in SQL)

- Cloned the dataset to preserve the original using `CREATE TABLE ... LIKE`
- Replaced missing values:
  - Emails → `not_provided@email.com`
  - Discounts → `0%`
  - Phone Numbers → `"Unknown"`
- Removed duplicates (e.g., multiple entries like "John Doe")
- Standardized various date formats (including Excel serial dates) to `YYYY-MM-DD`

---

## 📊 Exploratory Insights

### 🪑 Revenue by Product Category
- **Furniture**: $17,500 (Highest)
- **Electronics**: $12,300
- **Clothing**: $3,850  
✅ Furniture generated nearly **50%** of all revenue.

### 💸 Discount Effectiveness
- Discounts between **10–15%** yielded the highest revenue.
- Discounts above 20% showed **diminishing returns**.
- Smart discounting increases sales efficiency — especially in high-ticket categories.

### 📆 Monthly Trends
- **February 2024** had the highest revenue ($8,000) — likely due to Valentine promotions or stock clearance.
- **May 2024** had the lowest performance ($650) — possibly due to “spending fatigue.”

---

## 📊 Power BI Visuals (Included in PDF)

- 📌 **Heat Map**: Product Category vs. Month
- 🎯 **Scatter Plot**: Discount (%) vs. Revenue
- 📊 **Histogram**: Distribution of Order Sizes

---

## ✅ Strategic Recommendations

1. Prioritize **Furniture** in marketing and bundling efforts.
2. Stick to discount ranges of **10–15%** for optimal returns.
3. Run special campaigns during low months like **May**.
4. Re-evaluate **Clothing** as a category (marketing or strategic pivot).
5. Promote **bundle offers** and premium tiers to increase average order size.

---

## 🔐 Ethics

- No sensitive personal data used
- All customer identifiers anonymized
- SQL transformations preserved raw data integrity

---

## 🔗 View on GitHub

[![🔍 View Project on GitHub](https://img.shields.io/badge/View_Repo-GitHub-blue?style=for-the-badge&logo=github)](https://github.com/Mac-John/sales-insight-sql-powerbi)

---

## 👋 Connect with Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://linkedin.com/in/macjohnsindioapaun)  
📫 Email: sindioapaunmacjohn@gmail.com  
🌐 Portfolio: [mac-john.github.io](https://mac-john.github.io)

---
