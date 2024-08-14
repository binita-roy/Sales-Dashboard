# 📊 Sales Dashboard Using Power BI

Welcome to the Sales Dashboard project! This repository showcases a Power BI project that visualizes global sales data using an interactive dashboard. The dataset used is from the Global Superstore, and the objective was to derive meaningful insights and present them in a user-friendly manner.

## 🛠️ Project Overview

In this project, I have created an interactive Power BI Sales Dashboard based on Global Super Store sales data. The dashboard provides a comprehensive view of sales performance across various dimensions, such as region, category, and customer segment. The dashboard also includes a drill-through feature that allows users to navigate from a high-level summary to detailed product-level insights.

![Sales Dashboard Overview](https://github.com/binita-roy/Sales-Dashboard/blob/main/Sales_Dashboard_Overview.PNG)

### 🔍 Key Insights

- **Total Sales:** $3M, with a total of 38K units sold across different regions and categories.
- **Top Performing Segment:** Consumer segment leads with $1.46M in sales.
- **Top Product by Profit:** Fellowes PB dominates with the highest profit.
- **Return Orders:** There were 1,079 return orders, which could indicate areas for improvement in product quality or customer service.

### 🔗 Drill-Through Feature

- **Seamless Navigation:** Easily navigate from summary charts to detailed product information.
- **Product Analysis:** Dive deep into specific products to analyze performance across different years.

## 🔄 ETL Process

To build this dashboard, an ETL (Extract, Transform, Load) process was implemented to prepare the data:

1. **🧹 Data Cleaning and Transformation:** Power Query was used to clean and transform the data according to the project requirements.
2. **📊 Calculated Measures and Columns:** DAX (Data Analysis Expressions) was employed to create calculated measures and columns for deeper analysis and more dynamic visualizations.

## 📈 Visualizations and Report Creation

The report is designed with various visualizations, including cards, charts, and slicers, to facilitate easy understanding and provide meaningful insights to the end-user. The main features of the dashboard include:

- **💡 Total Sales Overview:** A summary of total sales, quantity, average delivery days, and return orders.
- **📊 Sales Breakdown:** Pie charts displaying sales by segment and category.
- **🌍 Regional Sales:** A map visualizing sales distribution across different regions.
- **🏆 Top and Bottom Performers:** Bar charts listing the top 10 customers by profit and top/bottom 5 products by profit.
- **🔮 Forecasting:** Line charts predicting trends in profits, sales, quantity, and shipping costs over time.

![Forecasting](https://github.com/binita-roy/Sales-Dashboard/blob/main/Forecasting.PNG)

## 🔗 Drill-through Overview and Navigation

The dashboard allows for drill-through capabilities, enabling users to explore detailed product-level data from high-level summaries. Here's how the navigation works:

1. **Navigating from Summary to Product Details:**
   - Users can click on any segment, category, or product in the summary charts.
   - This action will trigger a drill-through that takes the user to a detailed Product Details page, where specific information about the selected product is displayed.

2. **Product Details Page:**
   - The Product Details page provides granular data for the selected product, including profit, quantity, sales, shipping cost, and the year of the transaction.
   - Users can analyze trends and compare performance across different years directly from this page.

3. **Returning to the Summary:**
   - Users can easily return to the main summary dashboard by using the navigation buttons or breadcrumb links, maintaining a seamless exploration experience.

![Product Details](https://github.com/binita-roy/Sales-Dashboard/blob/main/Product_Details.PNG)

## 🛠️ Tools and Technology Used

- **Microsoft Power BI:** For creating the interactive dashboard and reports.
- **MS Excel:** For initial data exploration and preparation.

## 🗂️ Data Source

The dataset used in this project is available on Kaggle: [Global Superstore Dataset](https://www.kaggle.com/datasets/tahir1413/global-superstore-2016).

### 📥 Download Images

You can download the images used in this project by clicking the links below:

- [Sales Dashboard Overview](https://github.com/binita-roy/Sales-Dashboard/blob/main/Sales_Dashboard_Overview.PNG)
- [Forecasting](https://github.com/binita-roy/Sales-Dashboard/blob/main/Forecasting.PNG)
- [Product Details](https://github.com/binita-roy/Sales-Dashboard/blob/main/Product_Details.PNG)
