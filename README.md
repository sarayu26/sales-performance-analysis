# Sales Performance Dashboard

## Project Overview

This project presents an interactive sales performance dashboard built entirely in Microsoft Excel. It provides key insights into sales and profit trends, regional performance, category contributions, and top-selling products, enabling quick analysis and informed decision-making.

The dashboard is designed for easy navigation and allows users to filter data dynamically using interactive slicers.

## Key Features

* **Interactive Dashboard:** A single, clean sheet (`Dashboard`) consolidates all key visualizations and metrics.
* **Key Performance Indicators (KPIs):** Prominent display of `Total Sales` and `Total Profit` for immediate high-level overview. These values update dynamically with filters.
* **Sales by Region & Category Chart:** A clustered column chart visualizing sales and profit distribution across different geographic regions and product categories.
* **Monthly Sales Trend Chart:** A line chart depicting the historical trend of sales and profit over time, grouped by year and month.
* **Top Products by Sales Chart:** A pie chart showcasing the contribution of the top 5 best-selling products to overall sales.
* **Dynamic Slicers:** Interactive filters for `Region`, `Category`, and `Order Year` allow users to drill down into specific segments of the data.
* **Clean Design:** Hidden gridlines and headers provide a polished, report-like appearance.

## Dashboard Components

The Excel workbook contains the following sheets, organized for clarity and maintainability:

* **`Dashboard`**: The main interactive dashboard sheet, featuring charts, KPIs, and slicers.
* **` Sales Data`**: The raw, cleaned dataset used as the source for all PivotTables.
* **`Sales by Region PT`**: PivotTable generating data for the 'Sales by Region & Category' chart.
* **`Monthly Trend PT`**: PivotTable generating data for the 'Monthly Sales Trend' chart.
* **` Top Products PT`**: PivotTable generating data for the 'Top Products by Sales' chart.
* **` KPI Calculations`**: (Optional - if you put your GETPIVOTDATA cells on a separate sheet from PTs) Sheet containing the `GETPIVOTDATA` formulas for the KPI values displayed on the dashboard.

## How to Use the Dashboard

1.  **Download the file:** Download `Sales_Performance_Dashboard.xlsx` from this repository.
2.  **Open in Excel:** Open the file using Microsoft Excel (Excel 2016 or newer recommended).
3.  **Navigate to the `Dashboard` sheet.**
4.  **Interact with Slicers:** Use the `Region`, `Category`, and `Years` slicers to filter the data. All charts and KPIs will update automatically based on your selections.
5.  **Explore Charts:** Hover over chart elements for more details.

## Data Source

The dashboard uses a sample sales dataset, including fields such as `Order Date`, `Region`, `Category`, `Product Name`, `Sales`, and `Profit`.

## Tools Used

* Microsoft Excel (for data cleaning, PivotTables, PivotCharts, Slicers, and dashboard design)

## Setup

No special setup or software installation is required beyond Microsoft Excel. Simply open the `.xlsx` file.

## Possible Enhancements (Future Work)

* Add more KPIs (e.g., Number of Orders, Average Order Value).
* Incorporate additional slicers (e.g., Customer Segment).
* Implement conditional formatting for KPIs (e.g., color-coding profit based on target).
* Expand data for more years to observe longer-term trends.
* (Self-correction for year slicer issue if it persists): Refine the `Order Date` data cleaning process to eliminate any remaining non-standard date entries that might affect slicer filters.
