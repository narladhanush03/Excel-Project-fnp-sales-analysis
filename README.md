# FNP Sales Analysis Dashboard (Microsoft Excel)

This repository hosts a comprehensive, interactive sales analysis dashboard developed in Microsoft Excel. The project is designed to provide quick, data-driven insights into sales performance for FNP (Flowers N Petals) data, focusing on key performance indicators (KPIs), trend analysis, and customer segmentation.

---

## Key Features and Analysis Components

The dashboard leverages advanced Excel capabilities to offer dynamic data visualization:

| Component | Analytical Purpose | Excel Feature |
| :--- | :--- | :--- |
| **KPI Cards** | Provides high-level visibility on critical metrics: Total Orders, Total Products Sold, and Total Revenue. | Formulas and Custom Number Formatting |
| **Slicers** | Enables instantaneous data filtration across all visuals based on `ordered_day` (day of the week) and `Gender`. | Slicers connected to Pivot Tables |
| **Timeline** | Offers flexible filtering of data by specific time periods, including Year, Quarter, Month, and Day. | Timeline connected to Pivot Tables |
| **Revenue by Occasion** | Visualizes sales distribution and performance across major festivals and holidays. | Pivot Charts (Bar Chart) |
| **Top 10 Cities by Orders** | Highlights the top-performing geographical locations based on order volume. | Pivot Charts (Donut Chart) |
| **Revenue by Months** | Tracks sales trends throughout the year to identify seasonality and monthly peaks/troughs. | Pivot Charts (Line Chart) |

---

## Dashboard Preview

A static image of the complete dashboard layout is provided below:

![FNP Sales Analysis Dashboard Preview](https://github.com/narladhanush03/fnp-sales-analysis-excel-dashboard-/blob/f3242f8fcce6ef81ef2112afd5ae9a5544feaf72/Screenshot%202025-10-20%20133553.png)

*(Note: The full interactive experience, including active slicers and timelines, is only functional when the file is downloaded and viewed in Microsoft Excel.)*

---

## Instructions for Use

Since this dashboard relies on proprietary Excel features, direct interaction within the browser is not supported. Please follow these steps to access and use the dashboard:

1.  **Download the File:** Locate and download the `fnp.xlsx` file from this repository.
2.  **Open in Excel:** Open the downloaded file using a compatible version of Microsoft Excel (2013 or newer is recommended).
3.  **Enable Content:** When Excel opens the file, you will likely see a security warning bar due to the file being downloaded from the internet.
    * Click **"Enable Editing"** and then, if prompted, **"Enable Content"** to ensure all Pivot Tables, Slicers, and Timelines are fully activated.
4.  **Interact:** Once enabled, you can utilize the Slicers and the Timeline control on the right-hand side of the dashboard to dynamically filter the data and gain real-time insights.

---

## Data Structure Overview

The workbook is systematically organized to separate raw data from presentation:

* **Dashboard:** Contains the final, user-facing visualization.
* **Data:** Houses the cleaned, raw transactional dataset used as the source for the analysis.
* **Pivot\_Tables (Hidden):** Contains all the necessary Pivot Tables that link the raw data to the charts and slicers. This sheet is hidden to provide a clean user experience.

---

## Contact

Created by **[narladhanush03]**

