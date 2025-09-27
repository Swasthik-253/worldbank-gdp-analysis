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

📈 Business Questions & Insights

The dashboard answers the following key questions:

🌍 Global Trends

How has the world’s GDP evolved from 2000 to 2025?

Which years show major drops or spikes (e.g., 2008 financial crisis, 2020 pandemic)?

🏆 Top Performers

Which 5 countries had the highest GDP in 2023?

Which 5 countries grew the fastest (in % growth) from 2000 to 2023?

🌐 Continental Analysis

Which continent contributes the most to global GDP?

Which continent has shown the fastest growth rate over time?

🔮 Forecast & Patterns

Projected GDP growth for US, China, India, Germany, Brazil in 2025.

Identify countries with long-term upward or downward patterns.

📊 Power BI Dashboard

The dashboard contains:

Line Chart – Global GDP trend (2000–2025).

Column/Bar Charts – Top countries by GDP, fastest growing countries, growth by continent.

Forecast Visuals – GDP projections for 2025.
<img width="1285" height="738" alt="image" src="https://github.com/user-attachments/assets/cc9680d3-24dc-4cd6-a1e9-2404c677e542" />

🚀 Tools & Technologies

Power BI (Data Cleaning, DAX Measures, Visualization)

GitHub – Project Documentation



