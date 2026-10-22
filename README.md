Zepto Python Analytics 📊

Overview

A Python-based data analytics project exploring Zepto product data to identify insights into pricing, discounts, product availability, and inventory.

Analyses Performed

- Data exploration and cleaning
- Category-wise pricing and discount analysis
- Stock availability analysis
- Inventory value estimation
- Outlier detection using the IQR method
- Correlation analysis
- Product performance scorecard
- Data visualization using Matplotlib

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Project layout

- `data/raw/` — source datasets
- `data/processed/` — generated summary tables
- `notebooks/` — exploratory analysis notebook
- `visualizations/` — visualization scripts

Key Objective

To demonstrate practical Python data analysis skills and derive actionable insights from product pricing, discount, and inventory data.

Future Improvements

- Build an interactive dashboard using Power BI or Streamlit.
- Perform deeper sales analysis using transaction-level data.
- Automate data cleaning and reporting.

Note: Inventory value represents estimated stock value, not actual revenue or profit.



## Notebook

Open `notebooks/zepto_analysis.ipynb` in VS Code and select the project Python environment. The notebook reads `data/raw/zepto_v2.csv` and writes `data/processed/category_dashboard_summary.csv`.
