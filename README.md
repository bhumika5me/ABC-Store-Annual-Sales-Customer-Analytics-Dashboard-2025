# ABC-Store-Annual-Sales-Customer-Analytics-Dashboard-2025
# ABC Store -- Annual Sales & Customer Analytics Dashboard 2025

## Project Overview

**ABC Store -- Annual Sales & Customer Analytics Dashboard 2025** is an
Excel-based e-commerce sales and customer analytics project. The
dashboard analyzes annual transaction data to understand sales
performance, customer behavior, product performance, order status, sales
channels, geographic performance, age groups, gender, and B2B vs. B2C
sales.

The project is designed as a portfolio/data-analyst practice project
demonstrating the use of **Microsoft Excel, PivotTables, PivotCharts,
Slicers, formulas, and dashboard reporting**.

## Objective

The main objectives of this project are to:

-   Analyze annual sales and revenue performance.
-   Track orders, quantity sold, and average order value.
-   Understand customer demographics such as age group and gender.
-   Identify top-performing product categories.
-   Compare sales performance across online channels.
-   Analyze sales by geographic region/state.
-   Monitor order and delivery status.
-   Compare B2B and B2C sales.
-   Present the findings in an interactive Excel dashboard.

## Dataset

-   **Records:** 50 transactions
-   **Period:** January 2025 -- December 2025
-   **Country:** Nepal
-   **Customers:** 50 unique customers
-   **Orders:** 50 unique orders
-   **Products/SKUs:** 50 unique SKUs
-   **Categories:** 8
-   **Sales Channels:** 5
-   **Provinces/States:** 5

### Main Data Fields

  Field              Description
  ------------------ -----------------------------------
  Index              Transaction record number
  Order ID           Unique order identifier
  Cust ID            Customer identifier
  Gender             Customer gender
  Age                Customer age
  Age group          Teenager, Adult, or Senior
  Date               Order date
  Months             Month derived from the order date
  Status             Order status
  Channel            Sales channel
  SKU                Product/SKU identifier
  Categories         Product category
  Size               Product size
  Qty                Quantity purchased
  Current            Unit/current price
  Amount             Total transaction amount
  Ship-City          Shipping city
  Ship-State         Shipping province/state
  Ship-Status        Shipping status
  Ship-Postal Code   Postal code
  Ship-Country       Shipping country
  B2B                B2B or B2C indicator

## Key KPIs

  KPI                       Result
  --------------------- ----------
  Total Revenue            204,323
  Total Orders                  50
  Total Quantity Sold           77
  Average Order Value     4,086.46
  Delivered Orders              25
  Pending Orders                 6
  Returned Orders                5
  Cancelled Orders               4

> Currency is displayed as a numeric sales amount in the workbook. The
> dataset does not explicitly label the currency, so this README avoids
> assuming a specific currency symbol.

## Dashboard Sections

The workbook contains the following main analysis areas:

### 1. Monthly Sales & Orders

Compares monthly revenue with the number of orders/customers.

-   Highest monthly revenue: **October -- 34,491**
-   Lowest monthly revenue: **November -- 8,194**

### 2. Female vs. Male Sales

Compares revenue contribution by gender.

-   Male sales: **119,659 (58.6%)**
-   Female sales: **84,664 (41.4%)**

### 3. Order Status

Shows the distribution of orders by status.

-   Delivered: 25
-   Shipped: 10
-   Pending: 6
-   Returned: 5
-   Cancelled: 4

### 4. Top 3 States/Provinces

Identifies the highest-revenue geographic areas.

1.  **Bagmati Province -- 96,464**
2.  **Koshi Province -- 43,484**
3.  **Gandaki Province -- 29,488**

### 5. Age vs. Gender

Analyzes revenue contribution across customer age groups and gender.

Overall revenue by age group:

-   Adult: **130,755 (64.0%)**
-   Teenager: **59,373 (29.1%)**
-   Senior: **14,195 (6.9%)**

### 6. Sales Channel

Compares the number of orders across sales channels.

  Channel       Orders   Revenue
  ----------- -------- ---------
  Website           14    61,075
  Daraz             10    41,986
  Amazon             9    44,487
  Facebook           9    31,787
  Instagram          8    24,988

### 7. Product Category Performance

  Category        Revenue
  ------------- ---------
  Shoes            45,092
  Dress            39,390
  Jacket           29,995
  Jeans            24,992
  Shirt            24,087
  Kurta            19,590
  T-Shirt          14,586
  Accessories       6,591

## Key Business Insights

1.  **Total revenue is 204,323 from 50 orders**, with an average order
    value of approximately **4,086.46**.
2.  **October is the strongest sales month**, contributing about 16.9%
    of annual revenue.
3.  **November is the weakest sales month**, contributing about 4.0% of
    annual revenue.
4.  **Male customers generate more revenue than female customers**,
    accounting for about 58.6% of total sales.
5.  **Adults are the largest revenue-generating age group**,
    contributing about 64% of total revenue.
6.  **Shoes are the top-performing product category**, generating 45,092
    in revenue.
7.  **The Website is the largest order channel**, with 14 orders and
    61,075 in revenue.
8.  **Bagmati Province is the strongest geographic market**,
    contributing 96,464 or about 47.2% of total revenue.
9.  **B2C contributes slightly more total revenue than B2B**, while B2B
    has a higher average transaction value in this sample.
10. Delivered orders account for 25 of the 50 transactions, while the
    remaining orders are distributed among shipped, pending, returned,
    and cancelled statuses.

## Tools & Excel Techniques

-   Microsoft Excel
-   Excel formulas
-   PivotTables
-   PivotCharts
-   Slicers
-   Dashboard design
-   Data organization and cleaning
-   Aggregation and KPI calculation
-   Basic business/data analysis
-   Power Query *(listed in the workbook project guide)*

## Workbook Structure

  -----------------------------------------------------------------------
  Sheet                               Purpose
  ----------------------------------- -----------------------------------
  `data`                              Main transaction dataset

  `Project_Guide`                     Project objective, scope, tools,
                                      and KPI description

  `Dashboard`                         Main interactive dashboard

  `order vs sales`                    Monthly sales and order analysis

  `female vs man`                     Gender-based sales analysis

  `oder status`                       Order-status analysis

  `Top 3 States`                      Top geographic sales analysis

  `Age Vs Gender`                     Age-group and gender analysis

  `channel`                           Sales-channel analysis
  -----------------------------------------------------------------------

## Data Quality Notes

The workbook is structurally consistent for the 50 transaction records:

-   No missing values were found in the main dataset.
-   All 50 Order IDs are unique.
-   All 50 Customer IDs are unique.
-   The `Amount` field correctly matches `Qty × Current` for all
    records.
-   Dates cover the full January--December 2025 period.
-   Customer ages range from 21 to 55.

A few documentation/labeling points should be cleaned up before using
this workbook as a polished portfolio project:

-   The `Project_Guide` lists **"In Transit"** as a key order status,
    while the main `Status` field uses **"Shipped"** instead. The
    dashboard should use one consistent terminology.
-   The workbook contains a separate `Ship-Status` field that includes
    both **"In Transit"** and **"Shipped"**, so `Status` and
    `Ship-Status` should be clearly distinguished.
-   The sheet name `oder status` could be renamed to `order status` for
    professionalism.
-   The dashboard print/export area appears to split the dashboard
    across multiple PDF pages. For portfolio sharing, the dashboard
    should ideally be configured to fit onto one page.
-   The currency is not explicitly identified in the source data, so the
    dashboard should add a clear currency label if the amounts represent
    a specific currency.

## Conclusion

This project demonstrates a practical Excel analytics workflow:

**Raw Transaction Data → Data Preparation → PivotTable Analysis → KPI
Calculation → PivotCharts → Interactive Dashboard → Business Insights**

The dashboard provides a compact view of sales performance and customer
behavior and can be used as a portfolio project to demonstrate
foundational **Excel data-analysis and dashboarding skills**.

## Suggested Portfolio Description

> **ABC Store -- Annual Sales & Customer Analytics Dashboard 2025**\
> Built an interactive Excel dashboard using 50 e-commerce transactions
> to analyze revenue, orders, product categories, customer demographics,
> sales channels, geographic performance, and order status. Used Excel
> formulas, PivotTables, PivotCharts, and Slicers to transform raw
> transaction data into business-focused KPIs and insights.
