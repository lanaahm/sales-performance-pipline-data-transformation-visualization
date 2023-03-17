## 1. Overview

Analysis of sales performance is important because it can provide an understanding of how the business can run. By identifying trends and patterns in sales, understanding customer preferences, and can more easily make better decisions to manage a business. In today's digital era, sales performance analysis can also help optimize marketing strategies and improve customer experience.

This project aims to analyze sales performance by utilizing the process of analyzing and transforming data and displaying data visualizations so that they are easy to understand. Data will be processed using a data pipeline process to clean, format, and prepare it before being transformed into a form that can be further. This information will be displayed in a visualization dashboard using Power BI which displays important information about sales performance, sales trends, and product sales. Data used in this project includes the following attributes.

| Attribute  | Description                        |
| ---------- | ---------------------------------- |
| Order Date | contains date of order             |
| Region     | contains orders by region          |
| Person     | contains customer name             |
| Item       | contains product name              |
| unit       | contains product sales unit        |
| Unit Cost  | contains unit price of the product |
| Amount     | contains revenue per transaction   |

## 2. Transformation

1. Extract

- [ Create Folder ] => Create a new folder if it doesn't exists
- [ Extract Raw Data ] => Extract new raw data from the current source

2. Transfrom

- [ Lowercase ] => Lowercase string fields
- [ Ingeter ] => Transform float fields to integer
- [ Update Date ] => Update date format (e.g. from DD/MM/YYYY to YYYY-MM-DD)

3. Load

- [ Load ] => Insert data from raw table into clean table and check data in clean table to raw table

## 3. Visualization

Dashboard visualization is created using Power BI so that users can easily view and understand important information from sales transaction data visually.

[Dashboard Visualization](https://app.powerbi.com/view?r=eyJrIjoiNThhNDMwMDEtNDQ1MC00ZWE5LTllM2ItYzRjOTQwODEyYjJjIiwidCI6IjE1ZDA3NjUyLWQ4NzgtNGIwOS05MjJhLWE5ZTlkOTQwZjMxYSIsImMiOjEwfQ%3D%3D)

![Screenshot Power BI](https://user-images.githubusercontent.com/57904007/225780132-4e4d5f2f-beeb-452a-bf7b-1db38d9055b1.png)
