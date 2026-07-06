# Sales Dashboard Analysis

An interactive Power BI dashboard for analyzing sales performance across regions, categories, and time. Built to give a quick, at-a-glance view of revenue, profit, and order trends.

## 📊 Overview

This dashboard (`Sales_Dashboard_Analysis.pbix`) consolidates raw sales data into a single-page report with KPI cards, trend lines, and breakdowns by region, category, and product — enabling fast, data-driven decision-making.

## ✨ Features

- **KPI Cards** – Total Revenue, Total Profit, Total Units, and Average Order Value at a glance
- **Revenue & Profit Trend** – Monthly line chart tracking revenue and profit over time
- **Regional Performance** – Clustered bar chart comparing revenue across regions
- **Category Breakdown** – Pie chart showing revenue share by product category
- **Product-Level Detail** – Table view of revenue by individual product
- **Region Filter** – Slicer to interactively filter the entire report by region

## 🗂️ Data Model

The report uses a simple two-table model:

| Table | Purpose |
|-------|---------|
| `Raw Data` | Core sales transactions (Region, Category, Product, etc.) |
| `DateTable` | Date/calendar table with time-intelligence measures (Total Revenue, Total Profit, Total Units, Avg Order Value, Month) |

## 🛠️ Tools & Technology

- **Power BI Desktop** – report design and data modeling
- **DAX** – calculated measures (Total Revenue, Total Profit, Avg Order Value, etc.)
- **Power Query** – data loading and transformation

## 📁 Repository Structure

```
sales-dashboard-analysis/
├── Sales_Dashboard_Analysis.pbix   # Power BI report file
└── README.md                       # Project documentation
└── Raw Data.xlsx

## 📌 Notes

- This is a `.pbix` file, so it can only be opened and edited using Power BI Desktop.
- If your dataset is large or sensitive, consider excluding raw data files from the repo (see `.gitignore` suggestions below) and only sharing the report structure.

## 📄 License

Feel free to add a license of your choice (e.g., MIT) if you'd like others to reuse this work.

## 🤝 Contributing

Suggestions and improvements are welcome — feel free to open an issue or submit a pull request.
