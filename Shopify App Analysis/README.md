# E-commerce Project - Business Analytics Project


This project focuses on analyzing raw transaction logs to build a **conversion funnel** and conduct **cohort retention analysis** for an e-commerce platform.  
It was completed as part of a junior analyst onboarding project.

---

##  Project Overview

The dataset provided captured user activities such as product views, cart interactions, and purchases from an e-commerce platform built on Shopify.

The project was divided into four main phases:
1. **Conversion Funnel Creation** - Understanding user flow from product views to purchases.
2. **Cohort Analysis Preparation** - Filtering and structuring data based on first purchase behavior.
3. **Retention Rate Calculation** - Measuring user retention over a 4-month window.
4. **Spreadsheet Organization and Documentation** - Preparing a professional and executive-ready deliverable.

---

##  Tools Used

- Google Sheets
- Pivot Tables
- Functions: `VLOOKUP()`, `TEXT()`, `DATEDIF()`
- Spreadsheet formatting best practices

---

##  Key Results

### Results Synopsis

| Analysis | Summary |
|----------|---------|
| **Conversion Funnel** | The conversion funnel gives an insight that the website is converting product page views into purchases as many users engage with the platform, but the drop-off rate between stages is significant. <br><br>**Findings:** <br>• 10,453 unique users viewed products. <br>• Only 29% (3,036 users) added items to their cart. <br>• Of those, 36% (1,081 users) completed a purchase. <br>• The overall conversion rate from product view to purchase is just **10%**. <br><br>**Insights:** <br>• Low view-to-cart rate (29%) suggests users may not find products compelling enough to add. <br>• Cart-to-purchase rate (36%) points to possible checkout friction (e.g., high shipping costs or complicated checkout process). <br><br>**Recommendations:** <br>• Improve product recommendations, add urgency with limited-time discounts, simplify checkout, and retarget cart abandoners with incentives. |
| **Retention Rates** | Customer retention analysis indicates a **declining retention trend** over time. <br><br>**Findings:** <br>• Highest retention was observed in September 2020 with **13%** after one month. <br>• Retention rates drop below 7% by the second month across most cohorts. <br>• By the third and fourth months, retention rates approach **0%**. <br>• January 2021 shows no retention beyond the first month. <br><br>**Insights:** <br>• The e-commerce platform struggles with maintaining repeat customers beyond the first purchase. <br><br>**Recommendations:** <br>• Implement loyalty programs, personalized offers, and stronger post-purchase engagement strategies to boost repeat purchases and reduce churn. |

---

##  Dataset Description

| Column Name | Description |
|-------------|-------------|
| `user_id` | Unique identifier for each customer |
| `event_type` | Type of event: product view, cart open, or purchase |
| `category_code` | Product category code |
| `brand` | Brand name of the product |
| `price` | Product price in USD |
| `event_date` | Date of user activity (YYYY-MM-DD) |

---

##  Analysis

| Section | Description |
|---------|-------------|
| **Raw Data** | The dataset represents user interactions with an e-commerce platform, capturing different event types related to product engagement. The key fields include `user_id`, `event_type`, `category_code`, `brand`, `price`, and `event_date`. The time range analyzed spans from **September 24, 2020 to September 28, 2021**. For meaningful insights, only relevant portions of the dataset — specifically `user_id`, `event_date`, and `event_type` — were used. |
| **Conversion Funnel** | To analyze how users interact with the website, the primary focus was on **purchase events** from the `event_type` field. It was assumed that all interactions were recorded without missing data. Each `user_id` represents a distinct individual, and multiple interactions are recorded as separate rows. |
| **Retention Rates** | To build cohorts and calculate monthly retention rates, the primary focus was on the `user_id`, `first_purchase_month`, and `cohort_age` attributes from the `purchase_activity` sheet. Due to incomplete data for **February 2021**, no retention rate was calculated for that cohort. |

---

##  Final Deliverables

| Sheet Name | Description |
|------------|-------------|
| `Table of Contents` | Organized index of all sheets and their purposes |
| `Executive Summary` | High-level summary of results and key insights |
| `conversion_funnel` | Pivot table showing user flow and conversion rates |
| `retention_rates` | Table with calculated cohort retention percentages |
| `cohort_analysis` | Pivot table with unique user counts per cohort age |
| `purchase_activity` | Filtered purchases dataset, with additional cohort columns |
| `first_purchase` | Pivot table displaying first purchase dates per user |
| `raw_user_activity` | Full original raw event logs from the Shopify App |

---

##  Learnings and Assumptions

- Each `user_id` was treated as a unique individual.
- Assumed all recorded interactions were accurate and complete.
- Focused only on relevant events to create a clean, meaningful analysis.
- First purchases determined cohort assignment.
- No retention calculated for cohorts impacted by missing/incomplete data (e.g., February 2021).

---

##  Final Thoughts

This project developed my skills in cleaning e-commerce datasets, building conversion funnels, segmenting user cohorts, and calculating retention — all essential capabilities for data-driven decision-making in an e-commerce environment.

