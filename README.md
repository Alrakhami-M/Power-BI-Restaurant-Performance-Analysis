# Restaurant Sales & Performance Analysis Dashboard

## Project Overview

This project is an interactive **Restaurant Sales and Performance
Analysis** dashboard developed with Microsoft Power BI. It analyzes
restaurant orders, sales, profitability, customer feedback, and
operational indicators across multiple cities in Saudi Arabia.

The report is organized into three pages:

-   **Executive Dashboard** --- a summary of sales, profit, order
    volume, customer metrics, and performance trends.
-   **Sales & Product Analysis** --- analysis of sales by food category
    and product, including best-selling and higher-profit items and
    target comparisons.
-   **Customer & Operations** --- customer feedback, payment methods,
    order types, and operational measures such as preparation time.

## Project Objectives

-   Track restaurant sales, profit, and order performance.
-   Compare performance across cities and food categories.
-   Identify products and categories contributing to sales and profit.
-   Explore customer ratings and satisfaction indicators.
-   Understand order channels, payment methods, and operational
    patterns.
-   Present key information in an interactive report for business
    review.

## Dataset

The supplied Excel workbook contains **630 order records** and **28
columns**. The data includes information related to orders, customers,
products, prices, discounts, payment methods, ratings, and operational
details.

The dataset represents activity across **10 cities in Saudi Arabia**,
covering the period from **January to June 2025**.

## Dashboard Highlights

The report displays the following headline indicators (as shown in the
supplied dashboard):

  KPI                         Displayed Value
  ------------------------- -----------------
  Total Sales                         \$6.96K
  Total Profit                        \$3.28K
  Total Orders                            630
  Sales Growth                         17.45%
  Total Customers                         175
  Average Customer Rating                2.93

The displayed currency and KPI definitions should be interpreted
according to the report's underlying data model and measure definitions.

## Tools & Technologies

-   **Microsoft Power BI Desktop** --- report development and
    visualization.
-   **Power Query** --- data preparation and transformation.
-   **DAX** --- measures and KPI calculations.
-   **Microsoft Excel** --- source dataset.

## Analysis Workflow

1.  Import the restaurant orders workbook into Power BI.
2.  Review and prepare order, customer, product, and operational fields.
3.  Create the calculations required for sales, profit, growth, and
    customer metrics.
4.  Build interactive report pages and visual comparisons.
5.  Explore performance by time, city, food category, customer, and
    order characteristics.

## Key Analysis Areas

-   Sales, profit, and order volume.
-   Sales trends and growth.
-   Performance by city and food category.
-   Best-selling and higher-profit products.
-   Customer ratings and satisfaction indicators.
-   Order types and payment methods.
-   Order status and preparation-time information.

## Repository Structure

``` text
Power-BI-Restaurant-Performance-Analysis/
├── Dashboard/
│   └── Restaurant-Performance-Analysis.pbix
├── Dataset/
│   └── Restaurant-Orders.xlsx
├── Screenshots/
│   ├── Executive-Dashboard.jpg
│   ├── Sales-and-Product.jpg
│   └── Customer-and-Operations.jpg
└── README.md
```

*The folder and file names above are a suggested repository structure.
Adjust them to match the names you upload.*

## How to Use

1.  Download or clone this repository.
2.  Open the `.pbix` file using Microsoft Power BI Desktop.
3.  If prompted, update the source path to the Excel workbook in the
    `Dataset` folder.
4.  Refresh the data to load the report.

## Data Considerations

-   The supplied dashboard displays financial values with a dollar
    symbol. Confirm the intended reporting currency and source-data
    units before interpreting or relabeling these values.
-   The dataset includes different order statuses and missing values in
    some fields. Review how the report's measures handle cancelled,
    pending, or incomplete orders before using the KPIs for operational
    decisions.
-   Customer satisfaction indicators should be interpreted according to
    their actual DAX definitions and the treatment of missing ratings.

## Author

**\[Moahmmed Al-Rakhami]**

Data Analytics \| Power BI

------------------------------------------------------------------------

*This project is part of a data analytics portfolio and demonstrates an
applied restaurant reporting and analysis workflow using Power BI.*
