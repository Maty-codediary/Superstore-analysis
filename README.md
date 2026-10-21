# 🛒 Superstore Sales Analysis

**Author:** Maty Traoré  
**Dataset:** Kaggle Superstore Dataset (9,800 rows × 18 columns)  
**Tools:** Python, pandas, matplotlib

---

## Overview

Exploratory data analysis on a US retail superstore dataset covering orders from 2015 to 2018. The goal was to answer key business questions about product performance, seasonal trends, regional revenue, and order value, in order to practice a full data analysis workflow from cleaning to visualization.

---

## Dataset

| Feature | Detail |
|---|---|
| Source | [Kaggle — Sample Superstore](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) |
| Rows | 9,800 |
| Columns | 18 |
| Key columns | `Order Date`, `Region`, `Product Name`, `Sales`, `Category` |

---

## Notebook Structure

1. **Data Loading & Overview** — shape, dtypes, first look  
2. **Data Cleaning** — date conversion, missing values, duplicates, outlier check  
3. **Business Questions** — 5 targeted analyses using groupby aggregations  
4. **Visualizations** — horizontal bar charts for products, months, and regions  
5. **Key Findings & Conclusion**

---

## Business Questions Answered

1. Which products generate the most revenue?
2. Which months have the highest sales?
3. Which regions perform best?
4. What is the average order value?
5. Are there duplicate transactions or missing prices?

---

## Key Findings

- 🥇 **Canon imageCLASS 2200 Advanced Copier** is the top product at **$61,599** in total sales — nearly 2.5× the second-highest product
- 📅 **November and December** are the strongest sales months ($350k and $321k), driven by end-of-year purchasing
- 🗺️ The **West region** leads in revenue ($710k), with the South lagging at $389k
- 💰 Average order value is **$459**
- ✅ No missing Sales values, no duplicate rows — clean dataset overall

---

## How to Run

1. Clone the repo and open `super_store.ipynb` in Jupyter or VS Code  
2. Download the dataset from Kaggle and update the file path in the loading cell  
3. Run all cells in order

```bash
git clone https://github.com/Maty-codediary/superstore-sales-analysis.git
```

---

## Tech Stack

| Tool | Use |
|---|---|
| Python 3 | Core language |
| pandas | Data manipulation & analysis |
| matplotlib | Visualizations |

---

## Connect

LinkedIn: https://www.linkedin.com/in/traore-maty
