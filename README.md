# Automated Financial Data Pipeline and Analysis

![Dashboard Screenshot](./docs/dashboards_screenshots/growth_&_margins.png)

## Project Overview
This project provides a comprehensive financial analysis framework for evaluating companies with market capitalizations under €10 billion (excluding Financials and Real Estate sectors). The goal is to identify investment candidates based on solid fundamentals, ROIC, and Free Cash Flow generation.

The project follows an **ELT (Extract, Load, Transform)** paradigm, utilizing **Google BigQuery** for data warehousing and **Power BI** for interactive visualization.

## Visualizations
Check out the interactive dashboards:
- [Growth & Margins](./docs/dashboards_screenshots/growth_&_margins.png)
- [ROIC & Capital Management](./docs/dashboards_screenshots/roic_&_capital_management.png)
- [Costs & Debt](./docs/dashboards_screenshots/costs_&_debt.png)

## 📊 Detailed Documentation & Analysis
For a deep dive into the technical implementation (SQL queries, data cleaning) and the investment insights derived from the dashboards, please refer to the Jupyter Notebook:

👉 **[View Detailed Analysis in Colab/GitHub](https://github.com/carlosmorenaorellana/Automated_Financial_Data_Pipeline_and_Analysis/blob/main/Analysis_Final.ipynb)**

## Conclusion & Recommendations
Based on the quantitative analysis, three companies have been identified for further qualitative investigation based on their growth, valuation, and capital allocation strategies:
- **RAA.DE** (Industrials): High ROIC, high valuation.
- **BZU.MI** (Materials): Zero debt, high cash return.
- **LOTB.BR** (Staples): Rising ROIC, extreme valuation.

---
*Disclaimer: This project is for educational purposes only and does not constitute financial advice.*
