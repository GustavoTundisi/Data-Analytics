# 🚚 Delivery Performance Monitoring

![Project Cover](images/print_principal.png)

## 💼 The Business Problem

The company managed a high volume of operations (54k deliveries) but lacked visibility into punctuality by region and channel. The difficulty in identifying specific bottlenecks (underperforming cities or salespeople) hindered agile decision-making to reduce delays and improve service levels.

## 🎯 Objective

Develop a management dashboard to monitor delivery status and team performance, allowing a detailed view of deadline offenders and logistics distribution efficiency.

## 🛠️ Technologies Used

* **Power BI:** Visualization and interactivity.
* **Power Query:** Data cleaning and transformation (ETL).
* **DAX:** Calculations for status categorization (Early/Late) and aggregated counts.
* **Data Modeling:** Star Schema (Fact/Dimension).

## 📊 Main KPIs and Metrics

* **Total Delivery Volume:** Monitoring of total load and monthly seasonality.
* **On-Time Deliveries:** Absolute total of deliveries that met the Service Level Agreement (47k).
* **Delivery Status:** Percentage breakdown between Early (70%), On Time, and Late.
* **Performance by Channel/Team:** Comparison of volume delivered by sales channels and geographic regions.

## 🚀 Results and Insights

1.  **SLA Optimization:** It was identified that **70.7%** of deliveries are early, indicating an opportunity to adjust the delivery promise to the customer and make shipping more competitive.
2.  **Focus on Bottlenecks:** Mapping of critical cities (e.g., City 79 with the highest absolute volume of delays) for direct management action.
3.  **Seasonal Analysis:** Clear visualization of volume variation in September, allowing investigation of operational causes.

---
*This project was developed as part of the Data Science Academy Power BI course.*
