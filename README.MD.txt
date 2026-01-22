# Swiggy Sales Performance Analysis (2025)

## Project Overview
This project provides a comprehensive data-driven analysis of **Swiggy’s sales performance**, focusing on key business metrics, regional revenue distribution, and consumer behavior trends. Using Python, this analysis transforms raw order data into actionable insights for strategic decision-making in the food delivery sector.

## Business Problem
The objective of this project was to evaluate Swiggy's operational health by tracking high-level **Key Performance Indicators (KPIs)** and visualizing sales trends across different timeframes, food categories, and geographic locations.

**Key Objectives:**
* **Revenue Monitoring:** Track total sales and average order values.
* **Customer Satisfaction:** Analyze rating distributions and review counts.
* **Growth Trends:** Identify peak sales periods through monthly, weekly, and daily trend analysis.
* **Market Distribution:** Map revenue by state and city to identify top-performing regions.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy (Data Manipulation), Matplotlib, Seaborn, Plotly Express (Data Visualization)
* **Tools:** Jupyter Notebook

## Key Performance Indicators (KPIs)
Based on the analysis of **197,430 orders** from January to August 2025, the following metrics were identified:

| Metric | Value |
| :--- | :--- |
| **Total Sales (Revenue)** | ₹53,012,505.77 |
| **Total Orders** | 197,430 |
| **Average Order Value (AOV)** | ₹268.51 |
| **Average Rating** | 4.3 / 5.0 |
| **Total Ratings Count** | 5,591,574 |

## Key Insights & Findings

### 1. Revenue Trends
* **Monthly Sales:** The analysis reveals fluctuations throughout the year, with a significant dip in February before recovering in the following months.
* **Quarterly Growth:** Q2 (Apr–Jun) showed the strongest performance with ₹19.90M in revenue and 74,163 orders.

### 2. Consumer Preferences
* **Veg vs. Non-Veg:** Vegetarian dishes contribute the majority of the revenue at **62.9%**, while Non-Vegetarian items account for **37.1%**.

### 3. Geographic Performance
* **Top State:** **Karnataka** leads as the highest revenue-generating state.
* **Top 5 Cities:** The leading cities contributing to revenue include **Bengaluru, Lucknow, Hyderabad, Mumbai, and New Delhi.**

## Strategic Recommendations & Future Work

To further capitalize on these findings, the following strategies are recommended:

### Revenue Growth Strategies
* **Vegetarian Market Dominance:** Since 63% of revenue is driven by vegetarian options, Swiggy could implement "Green Days" or exclusive partnerships with high-rated pure-veg restaurants to consolidate this lead.
* **Tier-1 Market Deep-Dive:** While Bengaluru is the leader, Lucknow’s high performance suggests a massive appetite in Northern hubs. Targeted marketing spend in these high-growth cities could yield higher ROI than in saturated markets.
* **AOV Optimization:** With an Average Order Value of ₹268, introducing "Combo Upsells" or "Free Delivery over ₹300" thresholds could effectively push the AOV higher.

### Future Technical Enhancements
* **Predictive Analytics:** Use the historical time-series data to build a Machine Learning model (like ARIMA or Prophet) to forecast demand for the upcoming holiday seasons.
* **Sentiment Analysis:** Integrate NLP on the text-based reviews to understand *why* certain restaurants maintain a 4.3+ rating while others lag.
* **Churn Prediction:** Identify customers who haven't ordered in the last 30 days and create a personalized re-engagement discount strategy.

## Project Structure
* `Swiggy Sales Analysis.ipynb`: Complete data cleaning and analysis code.
* `Swiggy PPT.pdf`: Presentation summarizing the findings for stakeholders.
* `data/swiggy_data.xlsx`: Raw dataset containing order history.

***

### 🚀 How to Run this Project
1. Clone the repository.
2. Install dependencies: `pip install pandas numpy matplotlib seaborn plotly`.
3. Open `Swiggy Sales Analysis.ipynb` in Jupyter Notebook and run all cells.