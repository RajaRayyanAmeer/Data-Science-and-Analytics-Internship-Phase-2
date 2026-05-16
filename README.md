# 🛒 Global SuperStore — Interactive Business Dashboard

An interactive Streamlit dashboard for analyzing sales, profit, and segment performance.

## Setup & Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Features
- **Filters:** Region, Category, Sub-Category, Year Range
- **KPIs:** Total Sales, Profit, Profit Margin, Orders, Units Sold
- **Charts:**
  - Monthly Sales & Profit trend
  - Sales by Category (donut)
  - Top 5 Customers by Sales
  - Profit by Segment
  - Sales by Region
  - Sub-Category Sales vs Profit scatter
  - Discount vs Profit impact
- **Raw Data Table** with all filters applied

## Files
| File | Description |
|------|-------------|
| `app.py` | Streamlit dashboard |
| `SuperStore_Analysis.ipynb` | Jupyter notebook (EDA + insights) |
| `SuperStore.csv` | Dataset |
| `requirements.txt` | Python dependencies |
