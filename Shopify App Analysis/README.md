# Shopify App - Business Analytics Project

Welcome to the Shopify App Business Analytics Project!  
This project focuses on turning raw event logs into actionable business metrics, including a **conversion funnel** and **cohort retention analysis**.  
It was completed as part of a junior analyst onboarding exercise at an e-commerce company.

---

## 📊 Project Overview

The dataset provided contained raw user activity logs, capturing interactions like product views, cart opens, and purchases.

The analysis was divided into four main parts:
1. **Conversion Funnel Creation** - Tracking how users move from viewing a product to purchasing.
2. **Cohort Analysis Preparation** - Filtering and preparing data based on users' first purchase months.
3. **Retention Rate Calculation** - Understanding customer retention over a 4-month period post-first purchase.
4. **Spreadsheet Organization and Documentation** - Ensuring clarity, polish, and professionalism for executive presentation.

---

## 🛠️ Tools Used

- Google Sheets
- Pivot Tables
- Functions: `VLOOKUP()`, `TEXT()`, `DATEDIF()`, logical formulas
- Spreadsheet formatting best practices

---

## 📈 Key Results

### Conversion Funnel
- Built a 3-stage funnel: **Product View → Cart Open → Purchase**
- Calculated:
  - Total Conversion Rate
  - Step-by-Step Conversion Rates

### Retention Analysis
- Created 6 cohorts based on first purchase month
- Tracked user retention over the next 4 months
- Calculated retention rates for each cohort

---

## 📋 Dataset Description

| Column Name | Description |
|-------------|-------------|
| `user_id` | Unique identifier for each customer |
| `event_type` | Activity type: product view, cart open, or purchase |
| `category_code` | Product category |
| `brand` | Product brand |
| `price` | Product price (USD) |
| `event_date` | Activity date (YYYY-MM-DD) |

- Focused mainly on **purchase** events for cohort analysis.
- Dataset spanned multiple years, requiring `YYYY-MM` formatting for months.

---

## 🔍 Methodology

- **Conversion Rates**: Counted unique users at each funnel stage, then calculated overall and stepwise conversion percentages.
- **Cohorts**: Grouped users by **first purchase month**.
- **Retention**: Calculated percentage of retained users per cohort across 4 months post-initial purchase.

---

## 🗂️ Final Deliverables

| Sheet Name | Description |
|------------|-------------|
| `Table of Contents` | Organized index of all sheets |
| `Executive Summary` | Synopsis of results and analysis descriptions |
| `conversion_funnel` | Pivot table of funnel stages and conversion rates |
| `retention_rates` | Cohort-based user retention table |
| `cohort_analysis` | Pivot table counting unique users by cohort age |
| `purchase_activity` | Filtered dataset with purchases only, additional columns for cohorting |
| `first_purchase` | Pivot table with first purchase dates |
| `raw_user_activity` | Original raw event log data |

---

## 📚 Learnings and Assumptions

- Assumed unique `user_id` activity reflects individual users.
- Event logs were assumed reliable with no missing timestamps.
- For cohort analysis, users were assigned to cohorts based on the month of their first purchase.
- Retention calculations excluded month 0 (first purchase month) and started from month 1.

---

## ✨ Final Thoughts

This project sharpened skills in real-world data cleaning, cohort segmentation, conversion tracking, and executive reporting, all essential for a business analyst role.

---

> **Note**: Feel free to reach out if you'd like to collaborate on future analytics projects!


