# SuperStore Sales Analysis — Power BI PR1

A Power BI report created for **Practical Report 1 (PR1)** at **Red & White Skill Education**. The project uses the Sample Superstore dataset 
to explore sales performance, profitability, product categories, regional results, and order-level details.

## Table of Contents

- [Project Overview](#-project-overview)
- [Objectives](#-objectives)
- [Tools and Technologies](#-tools-and-technologies)
- [Dataset](#-dataset)
- [Report Pages](#-report-pages)
- [Dashboard Screenshots](#-dashboard-screenshots)
- [Data Preparation](#-data-preparation)
- [Dashboard Features](#-dashboard-features)
- [How to Open the Project](#-how-to-open-the-project)
- [Repository Structure](#-repository-structure)
- [Video Demonstration](#-video-demonstration)
- [Project Status](#-project-status)
- [Author](#-author)

## Project Overview

This project presents an interactive Superstore sales report built in Microsoft Power BI Desktop. 
It includes a sales dashboard with KPI cards and charts, along with a separate order-details page for reviewing transaction-level information.

## Objectives

- Prepare and transform sales data using Power Query Editor.
- Summarize key metrics with KPI cards.
- Compare sales across product categories and sub-categories.
- Analyze profit by region.
- Explore the report using slicers, filters, and visual interactions.
- Present detailed order information in a table.
- Document the project and its screenshots in GitHub.

## Tools and Technologies

| Tool | Purpose |
| Microsoft Power BI Desktop | Report creation and data visualization |
| Power Query Editor | Data inspection and transformation |
| Sample Superstore dataset | Source data |
| GitHub | Project documentation and version control |

## Dataset

**Dataset:** Sample Superstore Sales Dataset  
**Source:** Kaggle  
**Dataset page:** [Sample Superstore Sales Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

The dataset may include fields such as Order ID, Order Date, Ship Date, Ship Mode, Segment, Region, Category, Sub-Category, Sales, 
Quantity, Discount, and Profit. Available columns depend on the version downloaded.

## Report Pages

### 1. Sales Dashboard

The Sales Dashboard includes:

- KPI cards for Total Sales, Total Profit, Total Quantity, and Average Discount.
- A **Sales by Product Category** chart.
- A **Total Profit by Region** chart.
- A **Top 5 Sub-Categories by Sales** chart.
- Region slicers.
- A page-level Ship Mode filter intended to retain Standard Class and Second Class.
- A light-grey canvas with red and charcoal visual styling.

### 2. Order Details

The Order Details page contains a table with transaction-level fields, including:

- Order ID
- Order Date
- Ship Mode
- Segment
- Region
- Category
- Sub-Category
- Sales
- Quantity
- Profit

The visible columns and totals are based on the current report configuration.

## Data Preparation

Use Power Query Editor to verify the required transformations before submission.

- [ ] Connect to the Sample Superstore dataset.
- [ ] Review the Queries pane, Data Preview, Applied Steps, and Formula Bar.
- [ ] Inspect Column Quality, Column Distribution, and Column Profile.
- [ ] Rename at least three columns, as required by the assignment.
- [ ] Set appropriate data types:
  - Order Date → Date
  - Sales → Decimal Number
  - Quantity → Whole Number
  - Discount → Decimal Number
  - Profit → Decimal Number
- [ ] Check Sales and Profit for null values and handle any found according to the assignment.
- [ ] Filter Segment to retain Consumer and Corporate, excluding Home Office, if required.
- [ ] Split Order ID using the hyphen (`-`) delimiter, as required.
- [ ] Remove Row ID, Country, and Postal Code, if required.
- [ ] Confirm the required Applied Steps are present.
- [ ] Select **Close & Apply** and confirm that the data loads successfully.

## Dashboard Features

- **KPI cards:** Summarize total sales, total profit, total quantity, and average discount.
- **Sales by Category:** Compares sales across product categories.
- **Profit by Region:** Compares profit across geographical regions.
- **Top 5 Sub-Categories:** Highlights the leading sub-categories by sales when the Top N filter is configured.
- **Slicers and filters:** Allow users to explore data by region, category, and shipping mode.
- **Order Details table:** Provides a more detailed view of individual order records.

## Formatting Reference

| Element | Intended setting |
|---|---|
| Canvas background | Light grey (`#F5F5F5`) |
| Primary colour | Red (`#CC0000`) |
| Secondary colour | Charcoal (`#4A4A4A`) |
| Page layout | 16:9 widescreen, if required by the assignment |
| Chart titles | Clear and descriptive |
| Data labels | Enabled where appropriate |
| Theme | Built-in Power BI theme, as required |

## How to Open the Project

1. Install and open Microsoft Power BI Desktop.
2. Download or clone this repository.
3. Open the `.pbix` report file included in the repository.
4. If a data-source error appears, update the source path to the downloaded CSV or Excel file.
5. Select **Refresh** and check that the visuals load correctly.
6. Review the **Sales Dashboard** and **Order Details** pages.
7. Test slicers, filters, and visual interactions.
8. Save the report after making any required corrections.

## Repository Structure

SuperStore-PR1/
├── README.md
├── SuperStore-PR1.pbix
└── screenshots/
    ├── sales-dashboard.png
    └── order-details.png


The structure above shows the README and screenshots prepared for this project. Add the `.pbix` file to the repository using its actual filename. Optional dataset, theme, or video-link files should be included only if they exist and are permitted to be shared.

## Video Demonstration

**Video link:** Add your shared Google Drive or unlisted YouTube link here.

The PR1 brief requests a **5–10 minute recording** with your face and the Power BI screen visible. The demonstration should explain the dataset, Power Query transformations, KPI cards, charts, slicers, filters, theme, report pages, and visual interactions. Make sure the link is accessible to your instructor.

## 📝 Suggested Git Commit Messages

Use commit messages that describe changes actually made. Examples:

Add SuperStore Power BI report
Add dashboard and order details screenshots
Document project setup and report features

## ✅ Project Status

The README and screenshot files document the report pages. Before submission, verify the data transformations, final formatting, slicers and filters, Top 5 filter, visual interactions, refresh status, video link, and repository contents against the PR1 brief.
