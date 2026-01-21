# AdventureWorks-PowerBI-Business-Intelligence-Dashboard
Interactive Power BI dashboard analyzing sales, profit, returns, and customer trends for AdventureWorks Cycles (Maven Analytics Udemy course project).
------------------------------------------------------------------------------------------------------------------------------------------------------

# AdventureWorks Sales & Performance Dashboard

[![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-F2C811?style=for-the-badge&logo=powerbi&logoColor=white)](https://powerbi.microsoft.com/)
[![Maven Analytics](https://img.shields.io/badge/Udemy-Maven%20Analytics-blue?style=for-the-badge)](https://www.udemy.com/course/microsoft-power-bi-up-running-with-power-bi-desktop/)

An interactive **Power BI business intelligence dashboard** built for **AdventureWorks Cycles** — a fictional global manufacturer of cycling equipment and accessories. This project analyzes sales performance, revenue trends, profit margins, product returns, customer behavior, and regional insights from 2020–2022 data.

Created as the capstone project for the **Microsoft Power BI Desktop for Business Intelligence** course by Maven Analytics on Udemy.

## Key Features & Insights

- **Executive Overview**: High-level KPIs (Revenue $24.9M, Profit $10.5M, Orders 25.2K, Return Rate 2.2%)
- **Product Analysis**: Top performers (e.g., Accessories dominate orders; Bikes drive most profit)
- **Customer Segmentation**: Orders by income, occupation, and demographics
- **Geographic Performance**: Sales map across North America, Europe, and Pacific regions
- **Trends & Comparisons**: Monthly/weekly orders, revenue vs. targets, profit adjustments
- **Advanced Visuals**: Decomposition tree, key influencers, tooltips, and slicers for interactivity

## Dashboard Pages

| Page                  | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| My Dashboard          | Executive summary with KPIs, trends, and top products                     |
| Map Page              | Global sales distribution by country/region                               |
| Customer Page         | Customer demographics, top customers, revenue per customer                |
| Category Tooltip      | Category-level breakdowns                                                 |
| Product Page          | Detailed product metrics (orders, revenue, profit vs. targets)            |
| Decomposition Tree    | Drill-down analysis of key drivers                                        |
| Key Influencers       | Statistical insights into factors affecting ownership, pricing, etc.      |
| Q&A                   | Natural language query exploration                                        |

## Tools & Technologies

- **Power BI Desktop** (latest version)
- **DAX** for custom measures (e.g., YoY growth, adjusted profit)
- **Power Query** for data cleaning and transformation
- **Data Modeling** (star schema, relationships, hierarchies)

## Project Files

- `AdventureWorks Report.pbix` — Main Power BI file (or .pbip folder for source control)
- `/Data/` — Raw CSV files (Sales, Products, Customers, Returns, etc.)
- `/Screenshots/` — High-res images of all dashboard pages
- `/Exports/` — PDF export of the full report

## How to View the Dashboard

1. Download and open `AdventureWorks Report.pbix` in **Power BI Desktop**.
2. Refresh the data if needed (all sources are embedded/local).
3. Interact with slicers, drill-downs, and tooltips!

## Screenshots

![Executive Dashboard](Screenshots/executive-overview.png)
*Executive Overview*

![Product Page](Screenshots/product-page.png)
*Product Details*

![Map Page](Screenshots/map-page.png)
*Geographic Sales Map*

(Add more screenshots here — upload them to the repo!)

## Acknowledgments

- Dataset & guidance: **Maven Analytics** (Udemy course by Chris Dutton & team)
- Data source: Microsoft AdventureWorks sample database

## About Me

Data enthusiast passionate about turning raw data into actionable insights.  
This project demonstrates my skills in data modeling, DAX, visualization, and storytelling.

Feel free to ⭐ the repo or fork it! Questions? Open an issue or reach out.

Happy analyzing! 🚀
