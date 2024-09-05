# Employee Attrition Analysis Project

![Project Banner](ProjectBanner.png)

Analyzing Amazon Sales data from 2010 to 2017 using Excel and Power BI. This Project includes ETL Processes, Data Modeling, and Insights into Product and Regional Sales Trends.

## Table of Contents
- [Introduction](#introduction)
- [Objective](#objective)
- [Data Overview](#data-overview)
- [Data Preparation](#data-preparation)
- [Data Modeling](#data-modeling)
- [Dashboard Overview](#dashboard-overview)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
In an era of increasing competition and evolving market dynamics, understanding sales performance is crucial for strategic decision-making. This project focuses on analyzing Amazon's sales data using Excel and Power BI to uncover key trends, metrics, and relationships. By transforming raw data into actionable insights, this analysis aims to guide effective sales strategies, optimize distribution methods, and enhance overall profitability.

## Objective
The primary objective of this project is to perform a comprehensive analysis of Amazon's sales data to derive actionable insights that can inform strategic decision-making. The specific goals are as follows:
- **Analyze Sales Trends**: Examine monthly and yearly sales patterns to identify significant trends and seasonal variations.
- **Key Metrics Identification**: Highlight crucial performance indicators such as Total Revenue, Total Profit, Units Sold, Profit Margin, and Average Shipping Time.
- **Relationship Exploration**: Investigate the relationships between various attributes, including region, product, sales channel, and order priority.
- **Strategic Recommendations**: Provide actionable recommendations based on the insights to improve sales strategies, optimize distribution methods, and increase profitability.
- **Interactive Dashboard Creation**: Develop an interactive Power BI dashboard to visualize key insights and facilitate dynamic data exploration by stakeholders.

## Data Overview
The dataset used in this analysis consists of sales data from Amazon for the years 2010 to 2017. The data includes the following columns:
- Order ID
- Order Date
- Ship Date
- Units Sold
- Unit Price
- Unit Cost
- Total Revenue
- Total Cost
- Total Profit
- Region
- Product
- Sales Channel
- Order Priority

## Data Preparation
1. **Data Extraction**: The dataset was obtained from a provided link, with Order ID used as the primary key for sequential arrangement.
2. **Data Cleaning**: Standardized inconsistent date formats, identified and removed duplicate values, and saved the cleaned data for further processing in Power BI.
3. **Data Transformation**: Converted relevant columns into normalized format, auto-detected and corrected data types, merged queries, and sorted data. Created dimension tables with unique IDs.
4. **Data Loading**: Loaded the transformed data into Power BI for visualization and analysis.

## Data Modeling
The data model consists of:
- **Amazon Sales Data**: The central fact table containing detailed transaction records.
- **Country Data**: Contains country and region details, providing geographical insights into sales data.
- **Order Priority Data**: Includes the classification of order priorities, allowing analysis by order priority.
- **Product Data**: Provides details about the product type, enabling product-based analysis.
- **Sales Channel Data**: Holds information about the sales channels, offering insights into sales performance by channel.
- **Measure Table**: A special table used to store calculated measures used in the dashboard.

## Dashboard Overview
The Power BI dashboard provides a comprehensive view of Amazon's sales performance, leveraging a variety of components to facilitate in-depth analysis and data-driven decision-making:
- **KPIs**: Present essential metrics such as Total Revenue, Total Profit, Units Sold, Profit Margin, and Average Shipping Time.
- **Slicers**: Enhance interactivity and allow users to filter data dynamically.
- **Charts**: Visualize trends, profit distribution, geographic performance, and channel-specific insights.

## Key Insights
- A total of 513,000 units were sold, generating $137.35 million in revenue with a profit margin of 32.16%.
- Cosmetics lead with $15 million in sales, followed by office supplies ($8 million) and household products ($7 million).
- Sub-Saharan Africa is the top region with $12.2 million in sales.
- The top countries include Djibouti ($2.43 million) and Pakistan ($1.72 million).
- A significant rise in online sales from 2012 to 2017.
- The average shipping time is 23 days.

## Recommendations
- **Expand High-Demand Categories**: Increase the product range in cosmetics, office supplies, and household products.
- **Reassess Underperforming Categories**: Consider replacing low-demand items with more popular products.
- **Target Low-Sales Regions**: Boost marketing efforts in North America and Central America.
- **Strengthen High-Sales Regions**: Enhance product availability and promotions in Sub-Saharan Africa and Europe.
- **Invest in Online Platforms**: Continue to grow online sales by improving digital marketing and user experience.
- **Reduce Shipping Time**: Streamline logistics to lower the average shipping time.
- **Align Stock with Demand**: Optimize inventory to match order priorities and prevent stockouts or overstocking.
- **Leverage Top Markets**: Focus on high-performing countries with localized strategies.

## Conclusion
The analysis reveals both strengths and areas for improvement in Amazon's sales performance. Key findings include robust sales in categories such as cosmetics and office supplies, strong regional performance in Sub-Saharan Africa and Europe, and a trend towards increased online sales. The implications for strategic planning include focusing on high-demand products, targeting regions with lower sales, optimizing sales channels, and improving supply chain efficiency.

## Installation
To run this project locally, you need to have the following software installed:
- [Microsoft Excel](https://www.microsoft.com/en-us/microsoft-365/excel)
- [Power BI](https://powerbi.microsoft.com/)

## Usage
1. **Amazon Dataset.csv**: This CSV file contains the raw sales data.
2. **Amazon Sales Analysis Dashboard.pbix**: Open this file in Power BI to view the interactive dashboard.
3. **Amazon Sales Report.pdf**: This PDF contains a summary report of the analysis.

### Steps to Analyze Data:
- Open the `Amazon Dataset.csv` in Excel to inspect and clean the data.
- Transform and load the dataset into Power BI.
- Explore the interactive visualizations and insights in the dashboard.

## Contributing
Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
