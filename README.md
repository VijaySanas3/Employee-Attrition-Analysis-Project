# Employee Attrition Analysis Project
Analyzing Employee Attrition Data to Uncover key factors driving turnover at XYZ Company using Power BI. This project includes ETL processes, Data Modeling, and Insights to Help Improve Retention Strategies and Employee Engagement.

![Project Banner](ProjectBanner1.png)

![Project Banner](ProjectBanner2.png)

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
Employee attrition is a significant challenge for companies looking to retain talent and maintain a productive workforce. This project focuses on analyzing employee attrition at XYZ Company to identify the main factors influencing turnover and provide actionable insights to improve retention strategies. Power BI were used to transform raw data into an interactive dashboard that HR teams can use for data-driven decision-making.
## Objective
The main objective of this project is to analyze employee data and provide insights to help XYZ Company reduce its 15% attrition rate. The specific goals are:
- **Identify Attrition Factors**: Analyze key metrics like job satisfaction, work-life balance, and tenure to identify patterns contributing to attrition.
- **Analyze Departmental and Role-Specific Trends**: Examine which departments and roles have the highest turnover rates.
- **Provide Strategic Recommendations**: Offer actionable recommendations to improve employee retention.
- **Interactive Dashboard**: Create a dynamic Power BI dashboard for visual exploration of insights.

## Data Overview
The dataset includes multiple attributes about employees such as:
- Employee ID
- Age
- Gender
- Marital Status
- Job Level
- Monthly Income
- Environment Satisfaction
- Job Satisfaction
- Work-Life Balance
- Years at Company
- Years Since Last Promotion

## Data Preparation
1. **Data Extraction**: The dataset was obtained from a provided link, with EmployeeID used as the primary key for sequential arrangement.
2. **Data Cleaning**: Missing values in columns like TotalWorkingYears, EnvironmentSatisfaction, JobSatisfaction, and WorkLifeBalance were handled by filling them with the median.
3. **Data Transformation**: The dataset was normalized and divided into multiple tables (Employee Details, Job Details, Travel Details, Education Details) connected by a primary key, EmployeeID.
4. **Data Loading**: Transformed data was loaded into Power BI for further analysis.

## Data Modeling
The data model uses a star schema, with the Attrition Fact Table at the center, connected to dimension tables:
- **Employee Details**
- **Job Details**
- **Education Details**
- **Travel Details**
- **Measure Table**

## Dashboard Overview
The Power BI dashboard provides an interactive overview of employee attrition with key metrics and visuals:
- **KPIs**: Attrition Rate, Total Employees, Attrited Employees, Current Employees
- **Slicers**: Gender, Marital Status, Department, Education Field
- **Charts**: Attrition by Age, Gender, Marital Status, Job Role, Business Travel, Job Satisfaction, Work-Life Balance
  
## Key Insights
- Employees aged 20-30 have a higher turnover rate.
- Sales and R&D departments show the highest attrition rates.
- Employees with low job satisfaction are more likely to leave.
- Poor work-life balance is a significant factor in attrition.

## Recommendations
- Offer professional development and feedback programs to boost satisfaction.
- Introduce flexible work options to reduce burnout.
- Provide clear career paths and regular promotions to retain talent.
- Focus retention efforts on high-turnover departments like Sales and R&D.
  
## Conclusion
The analysis highlights key areas contributing to employee attrition at XYZ Company. By implementing the recommended strategies, the company can foster a more engaging work environment and improve overall retention.

## Installation
To run this project locally, you need to have the following software installed:
- [Power BI](https://powerbi.microsoft.com/)

## Usage
1. **Amazon Dataset.csv**: This CSV file contains the raw sales data.
2. **Amazon Sales Analysis Dashboard.pbix**: Open this file in Power BI to view the interactive dashboard.
3. **Amazon Sales Report.pdf**: This PDF contains a summary report of the analysis.

### Steps to Analyze Data:
- Open the Attrition Dataset.csv in Excel for data inspection and cleaning.
- Load the dataset into Power BI for transformation and analysis.
- Explore the interactive dashboard to gain insights into employee attrition.

## Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Commit your changes (git commit -m 'Add feature').
Push to the branch (git push origin feature-branch).
Open a Pull Request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
