#  Manhattan Airbnb Vacation Rental Market Analysis

##  Project Overview

This project analyzes the **Manhattan Airbnb vacation rental market** to help guide investment decisions on **neighborhoods** and **property sizes** (number of bedrooms).  

Using real NYC Airbnb data, the analysis answers:
- **Which neighborhoods and property sizes are most attractive for vacation rentals?**
- **How much money did the most attractive listings generate?**

The project includes **data cleaning**, **pivot table analysis**, **revenue estimation**, and **data visualization** — all documented in an Excel workbook.

---

##  Project Files

| File Name | Description |
| :--- | :--- |
| `nyc_airbnb_data_v2_Sprint 1_PROJECT.xlsx` | Full analysis workbook including raw data, cleaned data, pivot tables, charts, and documentation. |

---

##  Requirements

- **Software**: Microsoft Excel (2016 or newer) or Google Sheets
- **Skills Needed**:
  - Data Cleaning (basic formula usage like `IF`, `SUMIF`)
  - Pivot Table creation
  - Chart building (bar charts)
  - Analytical thinking
  - Clear documentation practices

---

##  Data Cleaning Process

All data cleaning steps are documented in the `Change Log` sheet.

- **Neighborhood Cleaning**: Standardized capitalization and removed trailing spaces. Saved into `neighborhood_clean`.
- **Bedrooms Cleaning**: Empty bedroom values (representing studios) replaced with `0`. Saved into `bedrooms_clean`.
- **Top Listing Identification**: Created a `top_listing` column. Listings with:
  - Top 10 neighborhoods by review count
  - Most popular bedroom size per neighborhood
  - were flagged as top listings (`top_listing = 1`).
- **Revenue Calculation**:
  - In `calendar` sheet: created `revenue_earned` column.
  - Only days marked "available = f" (rented) were included.
  - In `listings` sheet: used `SUMIF()` to bring 30-day revenue.

---

##  Analysis Overview

### 1. Most Attractive Neighborhoods
- **Top 3**:  
  - Harlem
  - Lower East Side
  - Hell's Kitchen

- **Top 10 Neighborhoods** identified using `number_of_reviews_ltm`.

-  **Bar chart** created showing the number of reviews for top 10 neighborhoods.

---

### 2. Most Popular Property Sizes
- **Top Property Sizes**:
  - Studio apartments
  - 1-bedrooms
  - 2-bedrooms

- Pivot tables identified which bedroom sizes are most preferred overall and by neighborhood.

- Example:  
  - In **Harlem**, the most popular size is **1-bedroom** apartments.

---

### 3. Revenue Analysis
- **Revenue Calculation**:
  - Summed `adjusted_price` over 30 days.
  - Projected annual revenue by multiplying by 12.

- **Top-Earning Listing**:
  - **Listing ID**: `49946551`
  - **30-Day Revenue**: `$29,940`
  - **Estimated Annual Revenue**: `$359,280`

---

## Assumptions
- Data only reflects the various fields influencing the Manhattan vacation rental market 
- Data was collected from NYC AirBnB
- Reviews are used as a proxy for rental frequency.
- Missing bedroom data represents studio apartments (0 bedrooms).
- Rental prices are assumed stable across the year (no seasonality adjustment).

---

## Reproduction of the Project

1. Clean the `neighborhood` and `bedrooms` columns.
2. Create pivot tables:
   - Top 10 neighborhoods by reviews.
   - Most popular property sizes.
   - Neighborhood-specific size preferences.
3. Identify top listings.
4. Calculate nightly and 30-day revenue.
5. Estimate annual revenues.
6. Create visualizations for key insights.
7. Document assumptions and steps in a Change Log.

---

## Final Deliverables
- Clean, formatted Excel workbook:
  - Pivot tables and charts.
  - Top listings revenue table.
  - Executive Summary & Table of Contents.
  - Assumption & Change Log documenting all cleaning steps.
- Consistent styling: fonts, borders, colors, and formatting.

---
