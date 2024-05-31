# Business Insights 360 Project Overview

## Company Background
AtliQ Hardware, a rapidly growing company specializing in computer and computer accessories, has expanded globally through three sales channels: Retailers, Direct Sales, and Distributors. Despite recent setbacks from a poorly executed expansion into the American market, the company aims to leverage data analytics for informed decision-making to remain competitive.

## Project Objective
The goal of the Business Insights 360 project is to implement data analytics using PowerBI to address stakeholders' questions across various domains including finance, sales, marketing, and supply chain. This will enable AtliQ Hardware to make data-driven decisions and maintain a competitive edge in the market.

## Tech Stack
- **SQL**
- **PowerBI Desktop**
- **Excel**
- **DAX Language**
- **DAX Studio** (for report optimization)

## Project Charter
- **Live Report Link**
- **Project Charter File**

## PowerBI Techniques Learned
1. **Pre-Project Questions**: Identifying the objectives, success metrics, deadlines, stakeholder expectations, potential challenges, required data/resources, and design inputs.
2. **Calculated Columns & Measures**: Creating calculated columns and measures using DAX language.
3. **Data Modeling**: Implementing good practices, specifically the Snowflake data modeling method.
4. **Bookmarks & Page Navigation**: Utilizing bookmarks to switch visuals and buttons for page navigation.
5. **Dynamic Elements**: Creating dynamic titles based on filters and using KPIs.
6. **Conditional Formatting**: Applying icons or background colors for conditional formatting.
7. **Error Prevention**: Using the divide function to prevent zero division errors.
8. **Date Tables**: Creating date tables using M language.
9. **Data Validation**: Implementing validation techniques.
10. **PowerBI Services**: Publishing reports, setting up auto-refresh, creating PowerBI apps, and managing collaboration, workspace, and access permissions.

## Dataset Understanding
### Dimension Tables
- **dim_customer**: Customer details, including market (27 distinct), customer count (75), platforms (Brick & Mortar, E-commerce), and sales channels (Retailer, Direct, Distributors).
- **dim_market**: Market details, including sub-zones and regions (APAC, EU, LATAM).
- **dim_product**: Product details, including divisions (P&A, N&S) and categories (14 types).

### Fact Tables
- **fact_forecast_monthly**: Monthly forecasted customer needs to enhance satisfaction and reduce warehouse costs.
- **fact_sales_monthly**: Monthly sales data, similar to forecast table but with sold quantities.

### Additional Tables
- **freight_cost**: Travel and other costs per market with fiscal year data.
- **gross_price**: Product gross prices by product code.
- **manufacturing_cost**: Manufacturing costs by product code with year.
- **pre_invoice_deductions**: Pre-invoice deduction percentages per customer with year.
- **post_invoice_deductions**: Post-invoice deduction details.

  ## Key Business Terms
- **Gross Price**
- **Pre-Invoice Deductions**
- **Post-Invoice Deductions**
- **Net Invoice Sale**
- **Gross Margin**
- **Net Sales**
- **Net Profit**
- **COGS** (Cost of Goods Sold)
- **YTD** (Year to Date)
- **YTG** (Year to Go)
- **Direct, Retailer, Distributors, Consumer**

## Importing Data
Datasets from a MySQL database were imported into PowerBI using database access credentials.

## Data Model
* Data modeling is critical, serving as the foundation for the report. 
* Following best practices ensures optimal performance.
* The Snowflake method was employed for data modeling in this project.
 ![## Data model * *](https://github.com/priyanshi3100/BI-360/blob/e1a0570849f6f88ddd5e8846921a95b7e55cb523/Resources/Data%20Model%20-BI360.png)


 ## Dashboard designing
*Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required

## Home view
In Home view, all the views button will be available. User will land on specific view page by clicking the button

Info
Finance View
Sales View
Marketing View
Supply chain View
Executive View


  ## Finance View ![Alt text](https://your-repository-url/path-to-your-image.png)
## Sales View ![Alt text](https://your-repository-url/path-to-your-image.png)
## Marketing View ![Alt text](https://your-repository-url/path-to-your-image.png)
##Supply Chain View ![Alt text](https://your-repository-url/path-to-your-image.png)
#Executive View ![Alt text](https://your-repository-url/path-to-your-image.png)


## GitHub
### Managing Large Files
- **GitHub LFS**: For uploading large files and tracking specific file extensions.

- ### FULL REPORT FILE AVAILABLE ;

## Questions to Ask Before Starting the Dashboard
1. What is the objective of building this PowerBI dashboard?
2. How will the success of this project be measured?
3. What is the project deadline?
4. Are stakeholders expecting a preview before the actual release?
5. What are stakeholders' hopes and fears regarding this project?
6. Who will use this dashboard and for what purpose?
7. What are stakeholders' expectations upon project completion?
8. What can go wrong during the project?
9. What resources/data are needed?
10. Are there any design or view inputs from stakeholders?

    


By addressing these questions and following the structured approach outlined above, AtliQ Hardware can successfully implement data analytics using PowerBI to make informed decisions and enhance their market position.
