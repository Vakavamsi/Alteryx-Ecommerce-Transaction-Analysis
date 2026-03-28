# 🛒 E-Commerce Transaction Analysis Using Alteryx

This project reflects two things I'm proud of:

- ⚡ **Quick Adaptability** — I can pick up new tools fast, which is a real advantage in any workplace.
- 🎯 **Hands-On Execution** — I didn't just learn the tool; I applied it to real business problems and documented everything thoroughly so others can learn too.

---

## 📌 What This Project Is About

This is a guided walkthrough of an Alteryx-based project aimed at **improving e-commerce operations**. It moves through three key stages:

1. Cleaning the data
2. Running a cohort analysis
3. Generating business insights

All working toward smarter, revenue-focused decisions.

---

## 1. Dataset

📥 **[Download the Dataset](https://github.com/SQLicious/Alteryx-Project-Ecommerce-Transaction-Cohort-Analysis/blob/main/1.%20Inputs/transaction_dataset.csv)**

The dataset used here is `transaction_dataset.csv`  
It covers customer transaction records across **20,000 rows** and **13 columns**, including:

| Column | Description |
|---|---|
| Transaction ID | Unique identifier for each transaction |
| Product ID | Unique identifier for each product |
| Customer ID | Unique identifier for each customer |
| Transaction Date | Date of the transaction |
| Online Order | Whether the order was online (Yes/No) |
| Order Status | Approved or Unapproved |
| Brand | Product brand |
| Product Line | Product category |
| List Price | Listed selling price |
| Standard Cost | Cost of the product |
| Product First Sold Date | Date the product was first sold |

---

## 2. Phase 1 — Data Cleanup

Before any analysis, the raw data was cleaned using the following steps:

- ✅ **Removed unnecessary columns** like `product_class` and `product_size` using the **Select** tool
- ✅ **Fixed data types** to make all fields analysis-ready
- ✅ **Renamed columns** for better readability
- ✅ **Verified data quality** using the **Browse** tool

---

## 3. Phase 2 — Cohort Analysis

With clean data in hand, customers were grouped and studied:

- 👥 **Customer Segmentation** — Grouped customers into cohorts based on purchasing behavior
- 📊 **Key Metrics Calculated** — Retention rates and average spend per cohort
- 📋 **Tabular Output** — Cohort retention table generated for easy comparison

> 📂 Full workflow details available in the `.yxmd` Alteryx workflow file.

---

## 4. Phase 3 — Insights Generation

The final stage focused on answering **12 real business questions**:

| # | Business Question |
|---|---|
| 1 | How many distinct brands exist in the dataset? |
| 2 | How many unique customers made purchases? |
| 3 | What's the split between approved and unapproved orders? |
| 4 | Which product lines have the highest average list price? |
| 5 | What are the top 5 most profitable products? |
| 6 | How much do customers spend, and what's their average profit per transaction? |
| 7 | Which product lines generate the most revenue? |
| 8 | What's the total sales figure per brand? |
| 9 | Which 5 products have the highest profit margins? |
| 10 | Per customer: total transactions, total spend, and average profit |
| 11 | Which product lines drive the highest % of overall revenue? |
| 12 | Which customers have engaged with the full range of products? |

> 📂 Full workflow details available in the `.yxmd` Alteryx workflow file.

---

## 5. What Inspired This

This project was inspired by an exercise that originally recommended using **Python + SQL**.  
I rebuilt it entirely in **Alteryx Designer** — no code required — to demonstrate that low-code tools can be just as powerful and far more accessible to non-technical users.

---

## 6. How It Was Built

All the work was done using **Alteryx Designer**, drawing on skills from the Core Certification and four additional microcredentials.

### 🛠️ Tools Used

| Category | Tools |
|---|---|
| **Input / Output** | Input, Output |
| **Preparation** | Data Cleansing, Filter, Formula, Multi-Field, Sample, Select, Sort, Unique |
| **Join** | Append, Join |
| **Transform** | Cross-Tab, Summarize |

### ⏱️ Time Saved

> The same work using **SQL + Python** would have taken roughly **3 weeks (120 hours)**.  
> With Alteryx, it was completed in **just 3 days**. 🚀

---

## 7. What's Coming Next

- 📄 **Automated PDF Report** — Combining cohort analysis and 12 business insights, sent automatically to a list of recipients
- 📊 **Tableau Integration** — Exploring the Tableau Output tool to visualize cohort data externally

---

## 👤 Author

**Vamsi Vaka**  
