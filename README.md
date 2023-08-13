# Sales Analysis Dashboard

![Cover](https://github.com/nashaat29/Google-Play-Store-EDA/assets/138555343/0cb806c4-b58c-46c3-9a33-e3401c045e70)

Welcome to the Sales Analysis Dashboard repository! This project revolves around a comprehensive analysis of historical sales data from a company specializing in product sales and shipping. The analysis aims to identify optimal shipping methods and strategies for the future, based on an in-depth examination of the dataset.

## Dataset

![Dataset_SS](https://github.com/nashaat29/Google-Play-Store-EDA/assets/138555343/cadea80a-edce-4bf4-8c34-bdf6998125b8)

The dataset encompasses historical records spanning eight years, containing 1,000,000 rows and 13 columns. This comprehensive dataset serves as the cornerstone for our analysis, providing invaluable insights into the company's sales trends and patterns.

Dataset from 'NiveditaSureshK' Project: https://github.com/NiveditaSureshK/Sales-Analysis-DB-MSExcel/blob/main/Sales%20Dataset.xlsm

## Data Transformation and ETL

![PowerQuery_SS](https://github.com/nashaat29/Google-Play-Store-EDA/assets/138555343/62935a59-c3a1-4691-88f0-4f27d92e6bf8)

To ensure the data's quality and relevance, Power Query Editor within Power BI was utilized to execute Extract, Transform, Load (ETL) processes. The following steps were performed:

- Replaced values in the "Order Priority" column with standardized values: Low, Medium, High, and Critical.
- Removed the "OrderID" and "OrderDate" columns to streamline the dataset.
- Renamed the "ShipDate" column to "Date," making it the primary date column for analysis.
- Transformed and loaded the refined data into Power BI's tabular view for further analysis.

## DAX Calculations

![PowerBI_SS](https://github.com/nashaat29/Google-Play-Store-EDA/assets/138555343/cd05e3ff-33eb-4dd4-b913-528a9e2a1361)

To glean deeper insights from the data, key metrics were calculated using Data Analysis Expressions (DAX). The following columns and measures were created:

**Columns (Created with DAX):**
1. Total Revenue Column
2. Total Cost Column
3. Net Profit Column

**Measures (Created with DAX):**
1. Average Cost Price
2. Average Selling Price
3. Profit Margin (%)

## Dashboard Design

![Sales_Dashboard_image](https://github.com/nashaat29/Google-Play-Store-EDA/assets/138555343/6dae2490-96d5-4441-beeb-16c1693c38b7)

The resulting dashboard is a visual representation of the analysis, offering a user-friendly interface to explore critical insights from the sales data. The dashboard emphasizes the following key points:

1. **Profit Margin (%):** Visual representation of profit margins as a percentage.
2. **Total Revenue:** Illustration of total revenue generated.
3. **Total Cost:** Visualization of the overall costs incurred.
4. **Net Profit by Item Types:** Breakdown of net profit by different item types.
5. **Sales Channel Count:** Count of sales made through offline and online channels.
6. **Net Profit by Quarter:** Analysis of net profit per quarter.
7. **Average Selling Price:** Display of average selling prices.
8. **Average Cost Price:** Overview of average cost prices.
9. **Geographical Sales Data Map:** Representation of sales origins by country.

## Interaction and Insights

The dashboard's interactive nature empowers users to utilize any of the aforementioned visualizations as filters, alongside a dynamic year filter located at the top of the page. Notably, the map visualization influences only the profit margin display. This interactive design enables users to delve into specific areas of interest and gain a holistic understanding of the sales data's nuances.

## Learning and Takeaways

This project provided an invaluable learning opportunity in the realm of Power BI. Key takeaways include:

- **Layout Design:** Gained insights into effective layout design and the arrangement of visualizations for clarity.
- **Visualization Choice:** Developed skills in selecting appropriate visualizations and harmonizing their presentation through colors and formatting.
- **DAX Calculations:** Utilized basic DAX calculations to extract meaningful metrics from the dataset, supporting analytical processes.

Feel free to explore the dashboard, and should you have any questions or feedback, please don't hesitate to reach out. This project encapsulates the fusion of data analysis prowess with visualization finesse, culminating in a potent tool for deriving actionable insights from sales data.
