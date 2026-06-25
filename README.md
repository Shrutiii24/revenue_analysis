# Ride Demand & Revenue Optimization Analytics 

## Project Overview

This project analyzes ride-hailing data to uncover demand patterns, pricing behavior, operational efficiency, and revenue optimization opportunities. An interactive Power BI dashboard was developed to transform raw ride data into actionable business insights.

The dashboard goes beyond descriptive analytics by providing **driver allocation** and **pricing optimization** recommendations that can support operational decision-making for ride-hailing platforms.

---

# Objective

To analyze ride-hailing data and extract meaningful business insights using Power BI, enabling data-driven decisions for improving demand management, driver allocation, pricing strategy, and overall operational efficiency.

---

# Key Components

## 1. Dashboard Development (Power BI)

Designed a **5-page interactive dashboard** consisting of:

* Executive Overview
* Demand Analysis
* Revenue Analysis
* Driver Allocation Strategy
* Surge Pricing & Revenue Optimization

### Key KPIs

* Total Rides
* Total Revenue
* Average Fare
* Revenue per KM
* Peak Allocation Hour
* Peak Surge Hour

### Features

* Interactive slicers (Day of Week, Pickup Location)
* Clean dark-themed UI
* Dynamic KPI cards
* Conditional formatting and heatmaps
* Business insight & recommendation panels
* Operational strategy dashboards

---

## 2. Demand Analysis

Analyzed ride demand across:

* Day of Week
* Pickup Hour
* Time Buckets (Morning, Afternoon, Evening, Night)

### Key Insights

* Ride demand peaks during evening commute hours.
* Demand is highest between **2 PM–6 PM**, with **5 PM** showing the greatest driver allocation priority.
* Friday and Saturday evenings consistently experience the highest ride demand.

---

## 3. Revenue Analysis

Analyzed:

* Average Fare vs Trip Distance
* Average Fare by Hour
* Fare Distribution
* Trip Distance vs Duration

### Key Insights

* Fares increase with trip distance.
* Higher average fares occur during early-morning hours.
* Most rides are short-distance trips.
* Trip distance shows a strong positive relationship with fare amount.

---

## 4. Driver Allocation Strategy

Developed a demand-based driver allocation framework using custom DAX measures.

### Metrics Developed

* Demand Pressure Index
* Revenue Efficiency
* Normalized Revenue Efficiency
* Allocation Priority Score

### Objective

Prioritize driver deployment by considering both demand intensity and revenue opportunity rather than ride demand alone.

### Key Findings

* **Peak Allocation Hour:** 5 PM
* **Priority Allocation Window:** 2 PM–6 PM
* Friday and Saturday evenings require additional driver coverage.
* Early-morning trips generate higher revenue per ride but do not justify large-scale driver deployment due to lower demand.

### Recommendations

* Increase driver deployment during **2 PM–6 PM**.
* Prioritize **Friday & Saturday evenings**.
* Reduce excess driver supply during **2 AM–6 AM**.
* Use driver incentives before anticipated demand peaks.

---

## 5. Surge Pricing & Revenue Optimization

Since the dataset did not contain an actual surge multiplier, an **Estimated Surge Multiplier** was derived by comparing hourly average fare against the overall average fare. This serves as a pricing premium indicator for identifying potential surge pricing opportunities.

### Metrics Developed

* Estimated Surge Multiplier
* Revenue Opportunity Score

### Objective

Identify premium pricing windows and revenue optimization opportunities.

### Key Findings

* **Peak Surge Hour:** 5 AM
* **Peak Estimated Surge Multiplier:** 1.43×
* **Premium Pricing Window:** 5 AM–7 AM
* Early-morning rides generate higher revenue per ride despite lower ride demand.
* Evening hours generate the highest ride volume, while early mornings contribute premium fare revenue.

### Recommendations

* Apply moderate surge pricing during **5 AM–7 AM**.
* Increase driver supply during evening peaks instead of relying solely on surge pricing.
* Use dynamic pricing selectively where fare premiums persist despite lower demand.
* Monitor rider response to fare changes and adjust pricing dynamically.

---

# Key Business Insights

* Peak ride demand occurs during evening commute hours.
* Optimal driver deployment window is **2 PM–6 PM**.
* Friday and Saturday evenings require additional driver coverage.
* Premium pricing opportunities occur during **5 AM–7 AM**.
* Higher pricing is concentrated during low-demand, low-supply periods.
* Most rides are short-distance trips.
* Combining demand and revenue metrics provides more effective operational recommendations than analyzing either metric independently.

---

# 🛠️ Tools & Technologies

* Power BI
* DAX
* Power Query
* Microsoft Excel
* Data Visualization
* Business Analytics

---

# Business Impact

This project extends beyond traditional reporting by incorporating **prescriptive analytics**.

### Driver Allocation Strategy

Identifies **when additional drivers should be deployed** using a composite Allocation Priority Score based on demand and revenue efficiency.

### Pricing Optimization Strategy

Identifies **premium pricing windows** using an Estimated Surge Multiplier to support revenue optimization.

### Operational Decision Support

Provides actionable recommendations for balancing rider demand, driver availability, and pricing strategies to improve platform efficiency and revenue generation.
