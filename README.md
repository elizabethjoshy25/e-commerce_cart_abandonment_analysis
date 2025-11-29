# Cart Abandonment Analysis

## Goal:
To analyze customer behaviour from cart creation to checkout and identify patterns or factors leading to cart abandonment - e.g product type, region, device or time.

## Visuals:
### 1) KPI cards
     -Cart Abandonment Rate (%)
     -Total Carts Created
     -Purchases Completed
     -Lost Revenue
### 2) Bar Charts
     -Cart Abandonment by Product Category
     -Cart Abandonment by Device Type
     -Cart Abandonment by Region/Country
### 3) Line Chart
     -Trend of Cart Abandonment over time(daily or monthly)
### 4) Funnel Chart
     -Stages : Product View -> Add to cart -> Purchase (shows where drop-offs occur)
### 5) Table 
     -Top 10 products with highest cart abandonment(product name, cart count, purchase count, abandonment %)

## Dashboard Layout:
  ### Top Section
      Title + Date filter + KPI cards
  ### Middle Section
      Funnel chart + Trend line over time
  ### Bottom Section
      Bar charts by category & region + Top 10 abandonment products table

  (-green for completed purchases, red/orange for abandoned carts
   -white or light gray background for clarity
   -blue for engagement, red for loss)

## Insights to Derive:
     -Which categories or products have the highest abandonment rates
     -Which time of the day or day of week sees most drop-offs
     -Whether price or brand influences cart completion
     -How overall abandonment rate changes over time

### 🔗 Live Dashboard
View the dashboard here: (https://lookerstudio.google.com/reporting/5754e6ae-a86e-4f3a-a597-de2852e9a065)


# Cart Abandonment Analysis

## Goal: 
Analyze the e-commerce purchase funnel(product view -> add to cart -> begin checkout -> complete purchase) to find where customers drop-off, which segments are most affected, and recoomend fixes that reduce lost revenue.

## Scope:
Session-level + event - level analysis using transaction/session logs. 
Focus dimensions: product category, region, device, traffic source, time(hour/day), and customer type (new vs returning).

## Problem Statement:
The business needs to understand when, who, and why users abandon carts so product, UX and marketing teams can reduce abandonment and recover revenue.

## Key Questions:
-At which funnel step is drop-off largest?
-Which product categories, devices, or regions have unusually high abandonment?
-Do time of day, session length or discounts affect abandonment?
-Which segments are high-value but highly-abandoned (worth targeted recovery)?

### 🔗 Live Dashboard
View the dashboard here: https://lookerstudio.google.com/reporting/0ef2a5c0-5964-4128-bae8-cd2134122eea 

## Dashboard Plan
### Section 1 : KPI Cards
  1. Total Sessions
  2. Total Add-to-Cart events
  3. Total Checkouts
  4. Total Purchases
  5. Cart Abandonment Rate
  6. Revenue
### Section 2 : Funnel (Core chart)
  7. E-commerce Conversion Funnel
### Section 3 : Time Series
  8. Daily Cart Abandonment Rate 
    -Line chart: Date -> Abandonment %
  9. Daily Add to Cart Rate
    -Optional: Lag helps identify UX issues
  10. Daily Revenue Trend
    -Line chart
### Section 4: Breakdown
  11. Cart Abandonment by Device 
    -Bar chart
  12. Cart Abandonment by Product Category
    -Bar chart
  13. Cart Abandonment by Region
    -Bar chart
  14. Cart Abandonment by Traffic Source 
    -Bar chart or heatmap
  15. Revenue by Product Category
    -Bar chart
  16. Conversions by User Type
    -Returning vs New
### Section 5: Behaviour Patterns
  17. Average Cart Value vs Abandonment Rate
    -Scatter plot
    -shows if higher cart value causes abandonment
  18. Session count by Hour of Day
    -Useful if timestamps are added later
  19. Product Category vs Device Heatmap
    -Which combination leads to the most abandonment?
### Section 6: Tables
  20. Cart Abandonment by Category + Region
    -Pivot Table
  21. High-Value Abandoned Carts (Top 50)
    -Shows potential revenue leakage
  22. Traffic Source Performance Table

### 🔗 Live Dashboard
View the dashboard here: https://lookerstudio.google.com/reporting/d27b3381-8660-4cea-8554-8e564a6b8ed3

