# Fetch - Take Home Assessment

## Overview
This repository contains my submission for the **Fetch Take Home Assessment**. The exercise demonstrates my ability to analyze data, write SQL queries, and communicate findings to non-technical stakeholders. Below is a breakdown of the approach, analysis, and findings.

## Repository Structure
```
📂 fetch-data-analyst-takehome
 ├── 📄 Exploring Data Analysis.pdf       # Exploratory Data Analysis (EDA) findings
 ├── 📄 SQL Analysis.pdf                  # SQL queries and results
 ├── 📄 Email.pdf                         # Stakeholder communication
 ├── 📄 README.md                         # This file
```

## 1️⃣ Exploratory Data Analysis (EDA)
The **Exploring Data Analysis.pdf** document details the initial investigation of the provided datasets. Key findings include:
- **Data Quality Issues:**
  - Missing values in key fields across datasets (e.g., `CATEGORY_4`, `MANUFACTURER`, `FINAL_SALE`, `GENDER`).
  - Duplicates in the `PRODUCTS`, `TRANSACTIONS`, and `USER` datasets.
  - Extreme values in user age (e.g., ages exceeding 100 years).
  
- **Challenging Fields:**
  - The `FINAL_QUANTITY` field contained non-numeric values (e.g., "zero" instead of `0`).
  - `FINAL_SALE` had many missing or invalid values, potentially impacting revenue analysis.

## 2️⃣ SQL Queries & Analysis
The **SQL Analysis.pdf** document provides solutions to six business-related questions using SQL queries:

Here are three examples of them.

### **Closed-ended Question**
**Q: What are the top 5 brands by receipts scanned among users 21 and over?**
- SQL query filters users who are 21+ and counts receipts per brand.
- **Top brands:** COCA-COLA, ANNIE'S HOMEGROWN GROCERY, DOVE, BAREFOOT, ORIBE.

### **Open-ended Question**
**Q: Who are Fetch’s power users?**
- Power users are defined as users who have scanned the highest number of receipts.
- SQL query returns the top 10 users based on receipt count.

**Q: What percentage of sales in the Health & Wellness category comes from each generation?**
- SQL query classifies users into generational groups based on birth year.
- **Findings:** Millennials contribute the highest percentage of Health & Wellness sales.

## 3️⃣ Stakeholder Communication
The **Email.pdf** file includes a business-oriented summary of findings. Key points:
- **Main data quality concerns** affecting sales analysis and user demographics.
- **Interesting trends**, such as Millennials driving the Health & Wellness market.
- **Request for action** on clarifying missing `FINAL_SALE` values, handling duplicate records, and verifying extreme age values.

## 🔗 Submission
This repository serves as my submission for the Fetch Take Home Assessment. If you have any questions, feel free to reach out.

---
📩 **Contact:** yunhong@bu.edu



