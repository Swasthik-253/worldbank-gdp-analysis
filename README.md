# worldbank-gdp-analysis

This project analyzes World Bank GDP data (2000–2025) at both country and continent levels.
The goal is to extract global economic insights, identify growth trends, and design a Power BI dashboard that presents the data in a way that financial analysts and decision-makers can easily interpret.

The dataset was sourced from Kaggle.

🛠 Data Cleaning & Preparation

Data was cleaned and transformed using Power Query in Power BI:

Reshaped Data – Unpivoted year columns (2000–2025) into a single Year column.

Data Types Fixed – Converted GDP column to Fixed Decimal Number and Year to Whole Number.

Handled Missing Values – Replaced/removed NaNs for incomplete years (2024–2025).

Created Measures – DAX measures for growth %, CAGR, absolute growth, and forecasting.
