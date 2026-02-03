# 🎯 Customer Profile & Marketing Effectiveness Analysis

![Project Cover](images/print_principal.png)

## 💼 The Business Problem
The marketing team was sending generalized campaigns to the entire customer base, resulting in high costs and low conversion rates. The company lacked clarity on the Ideal Customer Profile (ICP): it was unknown exactly how income, education, or family structure (children at home) impacted purchasing decisions, making strategic segmentation difficult.

## 🎯 Objective
Develop a Business Intelligence dashboard to segment the consumer base, identify demographic patterns of the most profitable customers, and evaluate the real effectiveness of past campaigns to direct future actions with greater assertiveness.

## 🛠️ Technologies Used
* **Power BI:** Data visualization and storytelling.
* **Power Query:** Data treatment for salary range categorization and record cleaning.
* **DAX:** Measures for Average Ticket, Global Conversion Rate, and dynamic segmentation.
* **Modeling:** Relationship between transactional and demographic data.

## 📊 Analysis Structure (Navigation)

The project was divided into 4 strategic views to answer different questions:

### 1. Overview
* **Macro Metrics:** Total customers, Average Annual Salary (52k), and purchase distribution by channel (Web, Store, Catalog).
* **Demographics:** Base analysis by education level (Predominance of Higher Education) and Marital Status.

### 2. Purchase Behavior
* **Influence Factors:** Crossing Income vs. Spending, proving the positive correlation between salary and purchase volume.
* **Family Impact:** Crucial analysis showing how the number of children and teenagers at home drastically reduces the customer's average ticket.
* **Decomposition Tree:** Exploration of which profiles generate the highest total spending (Single > Married).

### 3. Campaign Performance
* **Conversion:** Global campaign acceptance rate (16.01%).
* **Buyer Profile:** Direct comparison showing that those who accepted the offer have a higher average salary (59k) than those who refused (51k).
* **Detailing:** Matrix table crossing purchase status with education and marital status.

### 4. Geographic and Temporal Patterns
* **Main Markets:** Spending ranking by country, highlighting the absolute leadership of the USA, followed by Spain.
* **Trend:** Evolution of annual revenue (2018-2023) by country, allowing identification of growth or stagnation in specific markets.

## 🚀 Results and Business Insights

1.  **The Consumption "Villain":** It was identified that customers without children spend substantially more than those with 1 or more children. *Recommendation: Create offers focused on childless couples and singles.*
2.  **Income Sensitivity:** The campaign had higher adherence in the audience with an average annual income above 59k. *Action: Segment mailing lists focusing on this income range to optimize ROI.*
3.  **Geographic Dominance:** The USA represents the largest share of revenue and constant growth. Markets like Brazil and Chile present residual volume, suggesting a need for strategy localization or discontinuation.
4.  **Omnichannel:** Despite the digital focus, Physical Stores (12k purchases) still outperform the Web (8k), indicating that the strategy cannot be purely online.

---
*This project was developed as part of the Data Science Academy Power BI course.*
