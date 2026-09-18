# Databel Customer Churn Dashboard

<img width="1157" height="602" alt="image" src="https://github.com/user-attachments/assets/a870b897-23f6-499c-95e3-1ebeb6c39012" />

A comprehensive Power BI business intelligence solution designed to track subscriber metrics, evaluate customer churn drivers, analyze geographic distribution, and identify retention risk factors.

---

## 📂 Dashboard Overview & KPI Metrics

* **Summary KPI Cards**: 
  * **Total Customers**: 6,687 active and historical subscriber records.
  * **Total Charge**: $7M in total revenue billed.
  * **Churned**: 1,796 total departed customers.
  * **Average Monthly Charge**: $31 per subscriber.
  * **Overall Churn Rate**: 26.86% organizational churn indicator.

---

## 📊 Detailed Visualizations & Breakdowns

### 1. Churn Drivers & Categories
* **Top Churned Reasons**: Bar chart highlighting primary departure factors, led by competitor offers (303), better competitor devices (297), and support attitudes (203).
* **Number of Churn by Category**: Treemap segmenting churn volume across Competitor (805), Attitude (287), Dissatisfaction (286), Price (200), and Other (191).

### 2. Geographic & Behavioral Analysis
* **Churned Rate by State**: Interactive Bing map displaying geographic concentrations and churn distributions across the United States.
* **Churn Rate by Customer Service Calls**: Longitudinal trend line mapping escalation of churn probability relative to customer service call volume (from 8.90% at 0 calls up to 100% at 5+ calls).

### 3. Contracts, Demographics & Financials
* **Churn rate by contract type and Gender**: Comparative column chart breaking down churn across Month-to-Month, One Year, and Two Year agreements categorized by gender.
* **Average of Monthly Charge and Rate Churned by Number of Customers in Group**: Dual-axis analysis showing average monthly charges and churn rates across customer group sizes.
* **Total Customers and Rate Churned by Age (Bins)**: Age-bracket histogram paired with a trend line illustrating customer counts and escalating churn risk among older age cohorts.

---

## 🛠️ Global Filters & Navigation

* **Global Slicers**: Interactive sidebar filtering controls enabling real-time cross-filtering across the report by **State**, **Gender**, and **Group**.
* **Reset Filters**: Dedicated button widget to clear active slicer selections instantly.

---

## 🚀 Getting Started

1. **Prerequisites**: Ensure you have Power BI Desktop installed.
2. **Open Project**: Load the `.pbix` report file to initialize the underlying data model, relational schemas, and DAX measures.
3. **Explore**: Use the left-side global slicers to filter data dynamically by state, gender, and group dimensions.
