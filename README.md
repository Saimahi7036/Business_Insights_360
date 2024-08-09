# Business_Insights_360

## Project Overview

AtliQ Hardware has been experiencing rapid growth in recent years. To maintain a competitive edge and make informed, data-driven decisions, the company decided to implement data analytics using Power BI for the first time. This project was initiated to answer stakeholders' questions across various aspects of the business, including finance, sales, marketing, and supply chain.

I worked on this project by following the Codebasics Power BI Course. [Link to the course](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project).

## Tech Stacks

- SQL
- Power BI Desktop
- Excel
- DAX language
- DAX Studio (for optimizing the report)
- Project charter file

## Power BI Techniques Learned

- Identifying key questions to ask before starting a project.
- Creating calculated columns and measures using DAX language.
- Data modeling using the Snowflake schema.
- Using Bookmarks to switch between visuals and Page navigation with buttons.
- Using the divide function to prevent zero division errors.
- Creating date tables using M language.
- Creating dynamic titles based on applied filters.
- Implementing KPI indicators and conditional formatting.
- Data validation techniques.
- Power BI services, including publishing reports, setting up a personal gateway for auto-refresh and creating Power BI Apps.
- Collaboration, workspace, and access permissions in Power BI services.

## GitHub

- Uploading large files using GitHub LFS.
- Tracking specific file extensions for LFS.

## Business-Related Terms

- Gross price
- Pre-invoice deductions
- Post-Invoice deductions
- Net Invoice sale
- Gross Margin
- Net sales
- Net profit
- COGS (Cost of Goods Sold)
- YTD (Year to Date)
- YTG (Year to Go)
- Direct
- Retailer
- Distributors
- Consumer

## Company’s Background

AtliQ Hardware is a company that has seen significant growth and has expanded its business globally. It specializes in selling computers and computer accessories through three channels:

- Retailers
- Direct
- Distributors

Recently, the company faced an unforeseen loss by opening a store in America based on surveys, intuition, and some Excel analysis. Additionally, the company’s competitors have well-established analytics teams that make data-driven decisions. Therefore, AtliQ Hardware decided to build its analytics team to derive data-driven insights and decisions for future success.

### Questions to Ask Before Starting the Dashboard

Before commencing the project, it was essential to clarify the following:

- What is the objective of building this Power BI dashboard?
- How will the success of this project be measured?
- What is the project deadline?
- Do the stakeholders expect a preview before the actual release?
- What are the stakeholders' hopes and fears regarding this project?
- Who will be using this dashboard, and for what purpose?
- What are the stakeholders' expectations upon completion of this project?
- What potential challenges could arise during the project?
- What resources or data are needed to build this dashboard?
- Are there any design inputs from stakeholders for the dashboard?

After the project kickoff meetings, the data engineering team provided the necessary data for the analytics team to explore.

### Dataset Understanding

A thorough understanding of the available data was crucial for effective analysis. Before diving into the analysis, I familiarized myself with the available data.

- **Dimension Table:** Contains static data like customer and product details.
- **Fact Table:** Contains transaction data.

**Example Tables:**

- **gdb041:**
    - *dim_customer:* Includes 27 distinct markets (e.g., India, USA, Spain), 75 distinct customers, and two types of platforms (Brick & Mortar and E-commerce).
    - *dim_market:* Includes 27 distinct markets, 7 sub-zones, and 4 regions (APAC, EU, NA, LATAM).
    - *dim_product:* Divides into categories such as Peripherals, Accessories, Notebook, Desktop, Networking, Storage.
    - *fact_forecast_monthly:* Used to forecast customer needs, helping in customer satisfaction and reducing warehouse costs.
    - *fact_sales_monthly:* Similar to fact_forecast_monthly, but with sold quantity instead of forecast value.
- **gdb056:**
    - *freight_cost:* Details of travel and other costs for each market with the fiscal year.
    - *gross_price:* Gross price details with product code.
    - *manufacturing_cost:* Manufacturing cost details with product code and year.
    - *Pre_invoice_deductions:* Details of pre-invoice deductions percentage for each customer.
    - *Post_invoice_deductions:* Post-invoice deductions and other deduction details.

## Importing Data into Power BI

Since the database is MySQL, the datasets were imported into Power BI by providing the necessary database access credentials.

## Data Model

Data modelling plays a crucial role and serves as the foundation of the report. All visuals are built upon the data model, and poor data modelling can adversely affect the report's overall performance. Following best practices in data modelling is essential. In this project, we followed the Snowflake schema for data modelling.

![Data Model](https://github.com/Saimahi7036/Business_Insights_360/blob/main/Data_model.png)

## Dashboard Designing

Based on the mockups received as requirements, the team began designing the visuals and creating measures as needed.

### Home View

In the Home view, all view buttons are available. Users can navigate to specific view pages by clicking the buttons:

- Info
- Finance View
- Sales View
- Marketing View
- Supply Chain View
- Executive View
- Products
- Support

## Overall Report

Unfortunately, the reports are not available at this time. Please refer to the images below for a visual summary of the project.

## Info Page

![Info Page](https://github.com/Saimahi7036/Business_Insights_360/blob/main/Info.gif)

## Finance View

![Finance View](https://github.com/Saimahi7036/Business_Insights_360/blob/main/Finace.gif)

## Sales View

![Sales View](https://github.com/Saimahi7036/Business_Insights_360/blob/main/Sales.gif)

## Marketing View

![Marketing View](https://github.com/Saimahi7036/Business_Insights_360/blob/main/Marketing.gif)

## Supply Chain View

![Supply Chain View](https://github.com/Saimahi7036/Business_Insights_360/blob/main/supply%20chain.gif)

## Executive View

![Executive View](https://github.com/Saimahi7036/Business_Insights_360/blob/main/Executive.gif)

## Products View

![Products View](https://github.com/Saimahi7036/Business_Insights_360/blob/main/Products%20View.gif)

## Key Insights and Project Outcome

By using this report, stakeholders can make data-driven decisions across various business areas. Some specific outcomes include:

- **Sales Optimization:** The report identified a decline in sales in the APAC region, leading to a reallocation of marketing resources to improve performance.
- **Cost Reduction:** Supply chain optimizations were implemented based on the analysis of freight costs, resulting in a 5% reduction in operational expenses.
- **Product Strategy:** The report helped in identifying which product categories had the highest gross margins, guiding product development and marketing strategies.

This project demonstrates the value of data-driven insights in driving business decisions, answering critical "why" questions, and improving overall company performance.
