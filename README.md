# Sales Report Dashboard

## Overview
This repository contains a Power BI dashboard project titled **Sales Report Dashboard**. The dashboard provides insights into sales data, offering visualizations and analytics to support decision-making processes.

## Files and Components
The repository includes the following key files and components:

1. **`Sales Report_Dashboard.pbix`**: The main Power BI report file, containing visuals, data models, and connections.
2. **Supporting Data Files**:
   - **DIM_Calendar.csv**: Dimension table with calendar details (1,096 rows, 8 columns).
   - **DIM_Customers.csv**: Dimension table with customer information (18,484 rows, 7 columns).
   - **DIM_Products.csv**: Dimension table with product details (606 rows, 11 columns).
   - **FACT_InternetSales.csv**: Fact table containing sales transactions (58,168 rows, 7 columns).
   - **SalesBudget.xlsx**: Excel file containing sales budget data (18 rows, 2 columns).
3. **SQL Scripts**:
   - SQL scripts for generating or managing dimension and fact tables:
     - `DIM_Calendar.sql`
     - `DIM_Customers.sql`
     - `DIM_Products.sql`
     - `FACT_InternetSales.sql`

### Extracted Components
The PBIX file contains the following internal components:

- **Version**: Indicates the Power BI version used.
- **`[Content_Types].xml`**: Specifies the types of content included in the report.
- **DiagramLayout**: Contains layout configurations for visual elements.
- **Report**: Defines the main report structure, including visuals and pages.
- **Settings**: Includes configuration settings for the report.
- **Metadata**: Provides metadata about the data model and report.
- **Connections**: Details data sources and connections.
- **SecurityBindings**: Configures security settings.
- **DataModel**: Contains the dataset and its relationships.

## Features
- **Data Analysis**: Visualizations and metrics to track sales performance.
- **Interactive Dashboard**: Enables dynamic filtering and exploration of data.
- **Custom Visuals**: Incorporates tailored visualizations to address specific business needs.
- **Data Connections**: Seamless integration with data sources for real-time updates.

## Requirements
To view or edit the dashboard, you need:
- **Power BI Desktop** (latest version recommended)
- Access to the necessary data sources (as configured in the `Connections` file)

## Usage
1. Open the `Sales Report_Dashboard.pbix` file in Power BI Desktop.
2. Refresh the data to ensure the visuals are up-to-date.
3. Explore the dashboard pages to analyze sales trends and performance metrics.



