# Coffee Shop Sales Analysis 

## 📊 Project Overview

This project presents a comprehensive sales analysis for a retail business. The primary goal is to uncover sales trends, track key performance indicators (KPIs), and provide actionable insights through interactive dashboards. The analysis is conducted using Python for Exploratory Data Analysis (EDA) and Microsoft Power BI for creating dynamic and insightful visualizations.

This repository contains the Python scripts used for data cleaning and analysis, the Power BI project file, and the dataset used.

**Motto:** "Converting raw data into valuable insights."

---

## 🎯 Problem Statement & Objectives

The core objective is to analyze the sales data to answer key business questions and build a dashboard that visualizes performance across various dimensions.

### Key Analysis Areas:

1.  **Total Sales Analysis:**
    * Calculate total sales for each respective month.
    * Determine the month-on-month (MoM) percentage increase or decrease in sales.
    * Calculate the absolute difference in sales between a selected month and the previous month.

2.  **Total Orders Analysis:**
    * Calculate the total number of orders for each month.
    * Determine the MoM percentage increase or decrease in the number of orders.
    * Calculate the absolute difference in orders between a selected month and the previous month.

3.  **Total Quantity Sold Analysis:**
    * Calculate the total quantity of products sold each month.
    * Determine the MoM percentage increase or decrease in quantity sold.
    * Calculate the absolute difference in quantity sold between a selected month and the previous month.

---

## 📈 Dashboard & Chart Requirements

The Power BI dashboard was designed to meet the following visualization requirements:

1.  **Calendar Heat Map:**
    * Dynamically adjusts based on a selected month from a slicer.
    * Days are color-coded to represent sales volume (darker shades for higher sales).
    * Tooltips display detailed metrics (Sales, Orders, Quantity) on hover.

2.  **Sales Analysis by Weekdays and Weekends:**
    * Segments sales data to analyze performance variations between weekdays and weekends.
    * Provides insights into differing sales patterns.

3.  **Sales Analysis by Store Location:**
    * Visualizes sales data for different store locations.
    * Includes MoM difference metrics based on the slicer selection.
    * Highlights MoM sales increase or decrease for each location to identify trends.

4.  **Daily Sales Analysis with Average Line:**
    * Displays daily sales for the selected month in a line chart.
    * Incorporates an average line to represent the average daily sales.
    * Highlights bars exceeding or falling below the average to identify exceptional sales days.

5.  **Sales Analysis by Product Category:**
    * Analyzes sales performance across different product categories.
    * Provides insights into which categories contribute most to overall sales.

6.  **Top 10 Products by Sales:**
    * Identifies and displays the top 10 products based on sales volume.
    * Allows for quick visualization of best-performing products.

7.  **Sales Analysis by Days and Hours:**
    * Utilizes a heat map to visualize sales patterns by days and hours.
    * Implements tooltips to display detailed metrics (Sales, Orders, Quantity) for each specific day-hour block.

---

## 🛠️ Tools and Technologies

* **Data Cleaning & EDA:** Python
    * **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Data Visualization & Dashboarding:** Microsoft Power BI
* **IDE/Editor:** Jupyter Notebook, VS Code

---

## 📂 Project Structure

```
.
├── 📂 data
│   └── coffee_shop_sales.csv         # Raw and cleaned dataset
├── 📂 notebooks
│   └── eda.ipynb              # Jupyter Notebook for Exploratory Data Analysis
├── 📂 powerbi
│   └── coffee_shop_dashboard.pbix   # Power BI project file
├── 📜 README.md                # Project README file
```

---

## 👨‍💻 Author

**Abhay Tiwari**
* LinkedIn: [[LinkedIn](https://www.linkedin.com/in/thekushak/)]
* GitHub: [[GitHub](https://github.com/thekushak0003)]
* Portfolio: [[Portfolio](https://github.com/thekushak0003/Abhay-Tiwari)]

---


This project is licensed under the MIT License. See the `LICENSE` file for details.
