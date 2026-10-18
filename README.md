
# Fraud Analysis Dashboard | Power BI

## Project Overview
This project uses Microsoft Power BI to analyse fraud-related data and present insights through interactive dashboards. It focuses on exploring fraud patterns in card transactions, analysing relevant metrics, and communicating findings through data visualisation. The report also includes a state-wise view of reported bank frauds in India.

## Objectives
* Analyse fraud-related data to identify patterns and trends.
* Explore key metrics associated with fraud, such as fraud rate, fraud amount and recovery rate.
* Present insights through interactive dashboards and visualisations.
* Make fraud-related information easier to interpret through data-driven reporting.

## Tools and Technologies
* Microsoft Power BI
* Power Query for data transformation
* DAX for calculated measures

## Dataset
* **Pages 1 and 2:** Synthetic card transaction dataset from Kaggle (250K records, Jan 2023 to Aug 2026). It does not represent verified real-world fraud incidents.
* **Page 3:** RBI bank fraud data as published in a Lok Sabha reply (Ministry of Finance), FY 2020-21 to 2024-25.

## Dashboard Features
* **Transaction Fraud:** KPI cards for total transactions, total amount, fraud amount and fraud rate; fraud amount by fraud type; fraud rate by payment method; a decomposition tree; and domestic vs. international fraud rate.
* **Fraud Patterns:** fraud rate and case count by income band and card limit band; fraud amount by occupation and age group; and fraud amount by merchant category.
* **State-wise Analysis:** a map of frauds by state, total frauds, amount not recovered, and loss vs. recovery rate by year.

## Key Insights
* Fraud was 5.39% of transactions but about 25% of total transaction value (1.05bn of 4.15bn).
* The international fraud rate (19.69%) was over 4x the domestic rate (4.63%).
* Fraud rate was nearly flat across payment methods (5.3% to 5.5%) but rose sharply in higher card-limit bands.

## Project Files
* `Fraud_Analysis_Dashboard.pbix`: Power BI report file.
* `/screenshots`: visual previews of the three report pages.

## Disclaimer
This project is intended for educational and portfolio purposes. Insights derived from the synthetic dataset (pages 1 and 2) should not be interpreted as actual real-world fraud statistics. Page 3 is based on publicly reported RBI figures.
```

