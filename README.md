# pizza-s-sales-dashboard

# Overview

The **Pizza Sales Dashboard** is a business intelligence tool developed using **Power BI** to visualize and analyze pizza sales data. It offers a detailed view of sales performance, trends, customer preferences, and inventory management, providing valuable insights for decision-making in a pizza restaurant.

The dashboard is designed for easy navigation, allowing users to drill down into key metrics, view sales trends, and analyze specific aspects of the business in a visual and interactive format.

# Features

- Sales Overview: Displays total sales, number of orders, and average order value over time.
- Top-Selling Pizzas: A list of best-selling pizzas, with visuals showing total revenue and the number of units sold.
- Sales Trends: Line charts depicting sales growth over time, showing peak hours, days, or seasons.
- Inventory Insights: Monitoring of stock levels for pizza ingredients to manage inventory and avoid shortages.

# Requirements

- **Power BI Desktop** (Free version or Power BI Pro if sharing and collaboration are required).
- **Sales data** in a supported format (CSV, Excel, or direct database connection). The dataset should include:
  - Order date
  - Pizza type or category
  - Sales value (price per order)
 
## Installation

# 1. Clone or Download the Power BI Project
- Clone or download the Power BI file (.pbix) from the repository:
  ```bash
  git clone https://github.com/your-username/pizza's-sales-dashboard.git
  ```
  Alternatively, you can download the .pbix file directly.

# 2. Open the Dashboard in Power BI Desktop
- Launch **Power BI Desktop**.
- Open the downloaded `.pbix` file using **File > Open** in Power BI Desktop.
  
# 3. Data Connection
- If you're using external data sources like a database or online data service, configure the data connection within Power BI by navigating to **Home > Get Data** and selecting your data source (e.g., SQL Server, Excel, Web).
  
  For local CSV or Excel files:
  - Click **Get Data > File > Excel** or **CSV**, and select your file.
  - Load the data into the dashboard.

### 4. Refresh Data
- Ensure your data is up-to-date by refreshing it under **Home > Refresh**.

# Features in the Power BI Dashboard

# 1.Sales Overview Page
- Provides key metrics like **Total Sales**, **Number of Orders**, and **Average Order Value**.
- The user can filter the view by date range or store location.

# 2. Top-Selling Pizzas
- Displays a **bar chart** or **pie chart** to show the top-selling pizzas, their revenue, and quantities sold.
- Drill through options available to analyze individual pizza types.

# 3. **Sales Trends**
- A **line chart** to display sales trends over time, enabling users to identify peak sales periods (hourly, daily, weekly).

# 4. **Inventory Insights**
- Uses **gauge charts** or **bar charts** to display the status of pizza ingredient inventory.
- Helps to track ingredients that need restocking based on sales.

# Customizing the Dashboard

- Filters: Use the slicers to filter by date, pizza type, location, or customer segment.
- Themes: Customize the dashboard's color theme and layout using Power BI's formatting options under **View > Themes**.
- Data Source: Connect to your own database or spreadsheet by configuring the **Get Data** function to load your specific pizza sales data.

# Publishing and Sharing

1. Publish to Power BI Service:
   - Once you’ve configured the dashboard and are satisfied with it, you can publish it to **Power BI Service** for online access.
   - Click **File > Publish > To Power BI** and select your workspace.
   
2. Sharing:
   - If using **Power BI Pro**, you can share the dashboard with others by selecting **File > Publish to web** or sharing directly through the Power BI Service.

# Troubleshooting

- Data Not Showing: Ensure that the data is correctly loaded by checking the data source settings under **Transform Data**.
- Slow Dashboard Performance: Optimize data queries and visuals. Reduce the number of visuals on a single page or aggregate data to improve performance.
- Missing Data: Double-check the data source for any missing or inconsistent data. Ensure all required columns (e.g., pizza type, sales value) are present.
  
# Acknowledgments

- Power BI for creating an easy-to-use data visualization platform.
- Open-source contributors and community resources for inspiration and solutions.
  
