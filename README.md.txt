# Superstore Sales & Profitability Analysis

# Project Overview
This project analyzes sales data from a global superstore to identify drivers of profitability, segment customers, and forecast inventory requirements. The goal is to provide actionable insights to the sales and operations teams to optimize discount strategies and regional focus.

# Business Problem
The Superstore has seen increasing revenue but stagnating profits. This analysis seeks to answer:
1. Which regions and categories are most profitable?
2. **Hypothesis:** Are aggressive discounting strategies hurting overall profitability?
3. Can we forecast sales trends to improve inventory management?

# Key Insights
* **Discount Strategy:** A T-test confirmed that discounts >20% lead to a statistically significant drop in profitability. Recommendation: Cap discretionary discounts at 15%.
* **Regional Performance:** The West Region outperforms all others, while the South requires a marketing intervention.
* **Forecasting:** 3-Month Moving Average indicates a seasonal spike in Q4, suggesting inventory should be increased by 15% in October.

# Tech Stack
* **Python:** Pandas (Data Cleaning), NumPy, SciPy (Hypothesis Testing)
* **Visualization:** Matplotlib, Seaborn
* **SQL:** Window Functions, CTEs (See `sql/` folder for query logic)

# Project Structure
* `notebooks/`: Contains the Jupyter Notebook with full EDA and Time Series analysis.
* `sql/`: Contains raw SQL queries demonstrating how data was extracted and ranked.
* `data/`: Raw dataset (Source: Kaggle).

# How to Run
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Launch Jupyter Notebook: `jupyter notebook notebooks/analysis.ipynb`