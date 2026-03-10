# 🍽️ A Deep Dive into Zomato's Customer Segments

![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Customer%20Segmentation-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

## 📌 Project Overview

This project explores **customer segmentation for Zomato**, one of India's largest food delivery platforms, and analyzes how different customer demographics drive restaurant performance across regions. Using behavioral and demographic data, the analysis uncovers which customer segments are most valuable — and what Zomato can do to better engage and retain them.

🔗 **[View the Live Tableau Dashboard](https://public.tableau.com/views/FinalProject_17444682409450/ADeepDiveintoZomatosCustomerSegments?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**

---

## ❓ Problem Statement

Zomato faces challenges in identifying and targeting its most valuable customer segments. While some users — such as students — exhibit high spending despite lower income, others engage less frequently but spend more per transaction. Without clear behavioral and demographic segmentation, it is difficult to develop personalized marketing strategies that boost engagement and retention.

---

## 🎯 Objectives

- Identify which age groups and occupations drive the most revenue
- Uncover geographic hotspots with the highest order volume
- Analyze restaurant preferences by customer segment
- Deliver actionable recommendations to improve targeting and retention

---

## 📊 Dataset

The analysis was built on a **joined dataset** combining three data sources:

| Table | Description |
|---|---|
| `Users` | Customer demographics (age, occupation, city) |
| `Orders` | Transaction-level order data |
| `Restaurants` | Restaurant metadata and location info |

> ⚠️ *The full joined dataset is too large to upload to this repository. The Tableau Public link above connects to the published dashboard with the complete data.*

---

## 🔍 Key Findings

### 👥 Sales by Age Group
- The **18–25 age group** is the highest-spending segment, driven primarily by order **frequency**
- Ages **22–23** represent the peak spending years
- The **36+ group** spends more per transaction but orders less frequently

### 💼 Customer Occupation
- **Students** are the #1 spenders, totaling over **$516M** in spend — likely preferring budget-friendly fast food at high volumes
- **Employees** come in second, with professionals showing potential for **upselling** premium options
- Housewives represent the smallest spend segment

### 🗺️ Geographic Trends — Top 10 Cities
- **Tirupati**, **Electronic City (Bangalore)**, and **Baner (Pune)** dominate in order volume
- Smaller cities like **Raipur**, **Indirapuram (Delhi)**, and **Vastrapur (Ahmedabad)** show untapped growth opportunities

### 🍕 Restaurant Preferences by Age Group
- **Ages 18–25** gravitate toward trendy, affordable chains: Domino's Pizza, Pizza Hut, KFC, Baskin Robbins, The Biryani Life
- **Ages 26–35** show similar preferences with a slight lean toward higher-rated, traditional options like Behrouz Biryani

---

## 💡 Strategic Recommendations

| Strategy | Details |
|---|---|
| 🎓 **Value-Based Campaigns (18–25)** | Bundle deals, student discounts, and subscription savings (e.g., Zomato Student Pass) |
| 🏆 **Loyalty Programs** | Points-based rewards, cashback, and early access to deals for high-spend segments |
| 🏢 **Occupation-Aware Marketing** | "Midday Meal" offers for professionals, "Late-Night Cravings" for students, family combos for older groups |
| 📍 **City-Specific Strategy** | Regional challenges, referral programs, and app gamification (e.g., leaderboards for foodies in Mumbai) |
| 🍽️ **Age-Based Restaurant Personalization** | Curated homepage feeds and push notifications based on dining preferences — premium options for older adults |

---

## 🛠️ Tools & Technologies

- **Tableau Public** — Dashboard design & interactive visualization
- **Data Joins** — Users + Orders + Restaurant tables combined for analysis
- **Customer Segmentation** — Age, occupation, and geographic dimensions

---

## 📸 Dashboard Preview

| Overview | Sales by Age Group |
|---|---|
| ![Overview](dashboard_overview.png) | ![Age](dashboard_age.png) |

> *Screenshots from the Tableau dashboard. See live version for full interactivity.*

---

## 📁 Repository Structure

```
Zomato-Customer-Segmentation/
│
├── README.md                  # Project documentation (you are here)
├── Requirements.txt           # Project requirements and notes
└── dashboard_screenshots/     # Static images of Tableau views
```

---

## 👩🏾‍💻 Author

**Valerie Chimebele (Kanma)**
Data Analyst | BI Professional | Storyteller with Data

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/kikivalerie26)
[![Tableau Public](https://img.shields.io/badge/Tableau-Public%20Profile-orange?style=flat&logo=tableau)](https://public.tableau.com)
[![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black?style=flat&logo=github)](https://github.com/Kikivalerie26)

---

*This project was completed as part of the TripleTen Data Analytics curriculum.*
