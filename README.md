# Data-Driven Internet Sales Analysis & Strategic Planning

## Project Overview

This project focuses on transforming static internet sales reports into a dynamic, interactive Power BI dashboard. Developed in response to a direct business demand from the Sales Manager, Steven, this solution aims to provide enhanced visibility into sales performance, customer and product insights, and crucial comparisons against budget, enabling more effective strategic planning and sales force follow-ups.

## The Business Challenge

The Sales team, led by Steven, needed to move beyond traditional, static reports to a more agile and visual reporting system for internet sales. Key pain points included:
* Lack of clear, visual dashboards for understanding sales performance across products and clients.
* Difficulty in easily tracking individual sales representative performance across their unique product and customer portfolios.
* A critical need to accurately compare current sales figures against the 2021 budget, which was available in a separate spreadsheet.
* The desire for a historical view, analyzing sales data looking back two years.

## User Stories

To address these challenges, the dashboard was designed around the following user needs:

* **As a Sales Manager,** I want to get an overview of internet sales so that I can better follow which customers and products sell the best, and track sales over time against budget.
    * *Acceptance Criteria:* A Power BI dashboard updating data daily, with graphs and KPIs comparing against budget.
* **As a Sales Representative,** I want a detailed overview of internet sales per customer so that I can follow up on my top customers and identify opportunities for increased sales.
    * *Acceptance Criteria:* A Power BI dashboard allowing data to be filtered for each customer.
* **As a Sales Representative,** I want a detailed overview of internet sales per product so that I can follow up on my top-selling products.
    * *Acceptance Criteria:* A Power BI dashboard allowing data to be filtered for each product.

## Key Features & Dashboard Sections

The developed Power BI dashboard includes interactive sections designed to meet the business requirements:

* **Executive Sales Overview:** Provides a high-level view of overall internet sales performance, with daily data updates and key performance indicators (KPIs) compared against the budget.
* **Customer Performance Drill-Down:** Allows sales representatives to filter and analyze detailed internet sales data by individual customer, identifying top buyers and areas for growth.
* **Product Performance Drill-Down:** Enables sales representatives to filter and analyze detailed internet sales data by product, highlighting best-selling items and product trends.
* **Time-Series & Budget Analysis:** Visualizes sales trends over time (including two years of historical data) with direct comparisons against the 2021 budget, utilizing graphs and KPIs.

## Data Sources

The analysis integrates data from multiple sources:

* **Internet Sales Data:** Comprehensive historical data of internet sales transactions.
* **Budget Data:** Provided in an Excel spreadsheet, detailing sales targets for the year.

## Technologies Used

* **Power BI:** For end-to-end dashboard development, including data modeling, interactive visualizations, and report publishing.
* **SQL:** Utilized for efficient data extraction, transformation, and querying of raw sales data.
* **Microsoft Excel:** For managing and integrating the sales budget data.


## How to Use This Repository

1.  **Clone the Repository:**
    `git clone YOUR_GITHUB_REPO_URL`
2.  **Explore the Data:** Navigate to the `/Data` folder to view the raw CSV files.
3.  **Review SQL Scripts:** Check the `/SQL_Scripts` folder for the SQL queries used in data preparation.
4.  **Open the Power BI Dashboard:** Launch `myReport.pbix` (located in the `/PowerBI` folder) with Power BI Desktop to interact with the dashboard.
5.  **View Documentation:** Refer to the `/Documentation` folder for any detailed project reports or supporting materials.
