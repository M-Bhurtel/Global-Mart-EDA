# Global Superstore - Sales and Profitability Analysis

### [View My LinkedIn Profile](https://www.linkedin.com/in/mohanibhurtel/)

---

### Project Overview

This project is an in-depth exploratory data analysis (EDA) of the Global Superstore dataset. The primary objective was to identify key drivers of sales and profitability to provide actionable, data-backed insights for business improvement. By analyzing trends across regions, product categories, and customer segments, this analysis uncovers critical areas for strategic focus.

---

### Problem Statement

The goal was to answer key business questions, including:
* What are the main drivers of the store's profitability?
* Which product categories and sub-categories are the most and least profitable?
* How does our discount strategy impact profitability, and is there a "tipping point" where discounts become unprofitable?
* Are there significant seasonal trends or regional differences in sales and profit performance?

---

### Data Source

The data used for this analysis is the "Global Superstore" dataset, sourced from Kaggle. It contains transactional data for a global retail company, including order details, customer information, and product specifications.

---

### Tools Used

* **Python:** For data analysis and manipulation.
* **Pandas:** For data cleaning, wrangling, and aggregation.
* **Matplotlib & Seaborn:** For data visualization and creating insightful charts.
* **Statsmodels:** For time-series seasonal decomposition.
* **Jupyter Notebook:** As the environment for the analysis.

---

### Key Findings & Actionable Insights

My analysis revealed several critical insights:

* **The Discount Trap:** There is a strong **negative correlation (-0.51)** between discount rates and profit. The analysis identified a clear "tipping point," showing that discounts **above 20% consistently lead to a net loss**.
* **Profitability vs. Sales:** While the **Technology** category has the highest sales, the **Office Supplies** category is the most efficient profit engine, containing sub-categories like "Fasteners" and "Paper" with **over 40% profit margins**.
* **Regional Imbalance:** **Eastern Asia** is the most profitable region, leveraging a low-discount strategy effectively. In contrast, regions like **Western Europe** have high sales but lower profitability due to higher average discounts.
* **Seasonal Sales Spike:** There is a sharp increase in sales during **Q4**, driven primarily by the **Consumer** segment and **Technology** products, indicating a strong holiday shopping trend.

---

### Key Visualizations

Here is a look at the "discount tipping point," which clearly shows profitability dropping into negative territory as discounts increase.
![Profit vs Discount](https://github.com/user-attachments/assets/79b69ab2-5181-482a-8bf7-61a9c47d0ab1)



---

### Strategic Recommendations

Based on the analysis, I recommend the following actions:

1.  **Revise Discount Strategy & Cap at 20%:** Implement a new company-wide policy where discounts above 20% require managerial approval.
2.  **Prioritize High-Margin Categories:** Reallocate marketing resources to promote high-margin Office Supplies sub-categories.
3.  **Leverage Best Practices from High-Performing Regions:** Pilot the low-discount, high-profitability model of Eastern Asia in other high-sales regions.
4.  **Plan Strategically for Q4 Seasonality:** Increase inventory of key products in Q3 and launch targeted marketing campaigns to the Consumer segment for the end-of-year rush.
