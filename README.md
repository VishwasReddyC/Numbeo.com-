# Munich Cost of Living – BI Dashboard

## Overview
This project uses **Selenium** to scrape real-time cost of living data for Munich from [Numbeo.com](https://www.numbeo.com), then cleans and visualizes it with Pandas and Matplotlib. It demonstrates a complete BI pipeline: data collection → transformation → dashboard.

## Files
- `Numbeo.com_.ipynb` – Jupyter notebook with the full Selenium scraping and analysis code.

## Key Features
- ✅ Automated browser automation with Selenium (headless mode supported)
- ✅ Extracts 55+ cost categories (rent, groceries, transport, etc.)
- ✅ Generates three BI charts:
  - Average cost by category (bar chart)
  - Top 10 most expensive items (horizontal bar chart)
  - Cost breakdown by category (pie chart)
- ✅ Calculates KPIs: total monthly cost, rent-to-salary ratio, etc.

## How to Run
1. Install dependencies:  
   `pip install selenium pandas matplotlib webdriver-manager`
2. Run the notebook cell by cell, or execute as a script.


