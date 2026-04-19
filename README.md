# Ride Demand & Revenue Optimization Analytics (Uber-like System)

## Project Overview

This project focuses on analyzing ride-hailing data to uncover demand patterns, pricing behavior, and operational efficiency. An interactive Power BI dashboard is developed alongside a machine learning model to predict ride fares.

The goal is to enable **data-driven decision-making** for optimizing pricing, improving demand management, and enhancing operational efficiency.

---

## Objective

To analyze ride data and extract meaningful insights using data analytics and machine learning techniques, while building an interactive dashboard for visualization and decision support.

---

## 🧩 Key Components

### 1. Dashboard Development (Power BI)

* Designed a **multi-page interactive dashboard**:

  * Dashboard Overview
  * Demand Analysis
  * Revenue & Efficiency

* Key KPIs:

  * Total Rides
  * Total Revenue
  * Average Fare
  * Revenue per KM

* Features:

  * Interactive slicers (Day of Week, Pickup Location)
  * Clean dark-themed UI for better visualization
  * Insight boxes highlighting key findings

---

### 2. Demand Analysis

* Built a **heatmap** to analyze ride demand by:

  * Day of week
  * Hour of day

* Created **time bucket analysis**:

  * Morning
  * Afternoon
  * Evening
  * Night

📌 **Key Insight:**
Ride demand peaks during **evening commute hours (5–7 PM)**.

---

### 3. Revenue & Pricing Analysis

* Analyzed:

  * Average fare vs trip distance
  * Fare variation by hour
  * Fare distribution

📌 **Key Insights:**

* Fares increase with trip distance
* Higher fares observed during low-supply hours (early morning/night)
* Most rides are short-distance trips

---

### 4. Operational Efficiency

* Studied relationship between:

  * Trip distance and duration
* Identified:

  * Underutilized time periods
  * Demand-supply imbalance

---

### 5. Machine Learning (Fare Prediction)

* Built regression models:

  * Linear Regression
  * Random Forest Regressor

* Features used:

  * Trip distance
  * Trip duration
  * Pickup hour
  * Passenger count

📊 **Model Performance:**

* R² Score ≈ **0.95**
* MAE ≈ **1**
* RMSE ≈ **3.4**

📌 **Conclusion:**
Random Forest performed slightly better, capturing non-linear relationships in pricing.

---

## Key Insights

* Peak demand occurs during evening commute hours
* Higher pricing observed during low-demand hours
* Most trips are short-distance
* Strong correlation between distance and fare

---

## 📁 Files

* `Ride_Dashboard.pbix` → Power BI dashboard
* `Fare_Prediction.ipynb` → ML model (Colab)

---

## 🛠️ Tools & Technologies

* Power BI
* Python (Pandas, Scikit-learn, Matplotlib)
* Google Colab

---
