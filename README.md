# Dynamic Retail Dashboard in Excel

## Table of Contents
- [Objective](#objective)
- [Significance](#significance)
- [Data Sources](#data-sources)
- [Steps to Create the Dashboard](#steps-to-create-the-dashboard)
- [Dashboard Features](#dashboard-features)
- [Future Enhancements](#future-enhancements)
- [Conclusion](#conclusion)

## Objective

The objective of this project is to develop a dynamic retail dashboard using Microsoft Excel that provides insightful visualizations and analysis for a retail business. This dashboard uses three tables — Orders, Returns, and People — to offer a comprehensive view of key business metrics. It allows users to quickly identify trends, track performance indicators (KPIs), and analyze sales and returns across various segments, categories, and regions.

## Significance

Retail businesses generate massive volumes of data that contain crucial insights into sales trends, customer behavior, and product performance. However, without an efficient reporting tool, it can be challenging to analyze and derive actionable insights from this data. This dynamic dashboard:
- Provides a user-friendly interface to analyze and visualize key metrics.
- Facilitates better decision-making by offering a quick view of top and bottom performers.
- Empowers users with interactive filters for real-time data slicing and dicing, enabling more targeted analysis.

## Data Sources

1. **Orders Table**: Contains detailed order information, including order ID, dates, customer information, product details, sales, quantity, discounts, and profitability.
2. **Returns Table**: Shows information on returned orders, helping analyze and mitigate return-related losses.
3. **People Table**: Provides region-wise information about employees or managers in charge of specific regions.

### Sample Data

#### Orders Table
| Order ID       | Order Date  | Ship Date   | Ship Mode   | Customer ID | Customer Name | Segment    | City          | State         | Country     | Postal Code | Market | Region | Product ID    | Category   | Sub-Category | Product Name                                         | Sales  | Quantity | Discount | Profit   | Shipping Cost | Order Priority |
|----------------|-------------|-------------|-------------|-------------|---------------|------------|---------------|---------------|-------------|-------------|--------|--------|----------------|------------|--------------|-----------------------------------------------------|--------|----------|----------|----------|---------------|----------------|
| CA-2012-124891 | 31-07-2020  | 31-07-2020  | Same Day    | RH-19495    | Rick Hansen   | Consumer   | New York City | New York      | United States | 10024       | US     | East   | TEC-AC-10003033 | Technology | Accessories  | Plantronics CS510 - Over-the-Head Wireless Headset | 2309.65| 7        | 0        | 762.1845 | 933.57        | Critical       |

#### Returns Table
| Returned | Order ID       | Market       |
|----------|----------------|--------------|
| Yes      | MX-2013-168137 | LATAM        |
| Yes      | US-2011-165316 | LATAM        |

#### People Table
| Person         | Region      |
|----------------|-------------|
| Anna Andreadi  | Central     |
| Chuck Magee    | South       |

## Steps to Create the Dashboard

To recreate this dynamic retail dashboard in Excel, follow these steps:

### 1. **Data Preparation**
   - Import the data tables (Orders, Returns, People) into Excel.
   - Clean the data by ensuring consistency in format and removing duplicates or unnecessary rows.

### 2. **Create KPI Table**
   - Define key performance indicators (KPIs) relevant to retail metrics, such as Total Sales, Total Profit, and Profitability.
   - Set up a separate KPI table that summarizes these metrics, using formulas for aggregation:
     - **Total Sales**: `SUM(Sales)`
     - **Total Profit**: `SUM(Profit)`
     - **Profitability**: `SUM(Profit)/SUM(Sales)`
     - **Average Discount**: `AVERAGE(Discount)`

### 3. **Build Pivot Tables**
   - Create pivot tables for each area of analysis (Segment, Category, Market, Region).
   - Use these pivot tables to support different visualizations by categorizing and summarizing data by metrics like Sales, Quantity, and Profit.

### 4. **Design Charts**
   - **KPI Charts**: Add charts to visually represent each KPI. For instance, use bar charts for top/bottom 5 analysis (Sales, Profit, Quantity).
   - **Segment, Category, and Market Analysis**: Use pie charts or stacked bar charts to show segment performance across different categories and markets.
   - **Map Visualization**: For geographic analysis, use Excel's Map Chart to display sales by country or region.

### 5. **Add Interactive Filters**
   - Use slicers and filters for real-time interactivity, enabling users to slice data by Year, Market, Category, or Segment.

### 6. **Finalize the Dashboard Layout**
   - Organize the layout for a clean, user-friendly interface.
   - Ensure charts and tables are easily accessible and properly labeled.

## Dashboard Features

This dashboard provides the following insights and features:

- **Important KPIs**: Interactive KPI metrics, including Total Sales, Profit, Order Quantity, etc.
  ![image](https://github.com/user-attachments/assets/8eb077de-902b-445b-a7af-e5ffac8bf15e)

- **Segment, Category, and Market Analysis**: Visualizations that break down data by business segments, categories, and market regions.
  ![image](https://github.com/user-attachments/assets/00ffec13-8756-45a1-802d-a929014385d6)

- **Top 5 and Bottom 5**: Charts showcasing top and bottom 5 performers for Sales, Profit, and Order Quantity.
  ![image](https://github.com/user-attachments/assets/4cba251e-ab9e-4b25-9fa6-82470447068c)

- **Global Sales Map**: A world map highlighting the top 10 countries by sales volume.
  ![image](https://github.com/user-attachments/assets/46fe943c-eacd-460c-a5bf-1372a4d07d0b)
  
- **Yearly Sales Trend**: Line or area charts showing the trend of sales over the years.
  ![image](https://github.com/user-attachments/assets/aae5b8f3-10d5-4efd-96d8-9919e9aee3b4)
  ![image](https://github.com/user-attachments/assets/aa7fd1be-08b5-43dc-a002-e0ee2d41b685)


## Future Enhancements

Planned features for further analysis include:

- **Return Analysis**: In-depth look into returns to identify trends and reduce return rates.
- **Top and Bottom Customer Analysis**: Identifying top customers by sales and profitability and those with potential improvement areas.
- **Segment Analysis**: Detailed analysis of each customer segment to understand performance.
- **Market and Product Analysis**: Evaluation of market and product performance to identify high-performing regions and products.

## Conclusion

This dynamic retail dashboard enables comprehensive and interactive analysis of retail data, allowing users to identify trends and make data-driven decisions. By providing a blend of visualizations, KPIs, and interactive features, this dashboard serves as a powerful tool for stakeholders looking to improve sales performance, manage product offerings, and enhance customer satisfaction.

This project demonstrates the capabilities of Excel in business intelligence and showcases the effectiveness of pivot tables, charts, and dynamic filters to create a robust analytical tool. Future enhancements will further deepen the insights available from this dashboard, making it an essential asset for retail analytics.

![image](https://github.com/user-attachments/assets/58381e4c-e563-49ed-ab50-63f62437a5f6)

