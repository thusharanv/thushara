# Traffic Collision Analysis Dashboard

This repository contains an **interactive Excel dashboard** that visualizes traffic collision data. The dashboard allows users to explore various aspects of traffic accidents, including the number of injuries and fatalities, contributing factors, and trends across different boroughs and times of the day.

## Features:
- **Interactive slicers** to filter data by borough.
- **Charts and Pivot Tables** that show trends, injury statistics, and other key metrics related to traffic collisions.
- **Data-driven insights** that can be customized by the user through Excel's built-in functionality

## Data Source:
The data used in this dashboard comes from the NYC Opendata and is available in the raw format within the file. The dataset contains information on:
- **Collision details** (date, time, location)
- **Persons involved** (injured or killed)
- **Vehicle types and contributing factors**

> Note: The dataset in the Excel file might have been processed or cleaned for analysis purposes. Also, since the dataset is really large, used only data(193523 rows) from 12/18/22-01/13/2025 for the analysis.

## How to Use:
1. Download the Excel file: ## Download and Extract the Dashboard
You can download the Excel dashboard in a compressed format from 
After downloading, extract the ZIP file to access the dashboard.
2. Open the file in **Microsoft Excel** (desktop version is recommended for full functionality).
3. Use the **slicers** to filter data by borough, the slicers will dynamically update the charts and pivot tables on the dashboard.
4. The dashboard is organized with the following sections:
   - **Overview**: A high-level summary of the data.
   - **Charts**: Various visualizations showing traffic collision trends.
   - **Slicers**: Interactive filters for deeper analysis.

### Data Structure:
The workbook includes the following sheets:
1. **Dashboard**: The final interactive dashboard where charts, pivot tables, and slicers are displayed.
2. **Raw Data**: The raw traffic collision data used to populate the dashboard. This sheet contains details such as date, time, borough, contributing factors, and the number of people injured or killed. The missing data for Borough is changed for Unknown and Time and Date fields are further extracted for efficient analysis.
3. **Calculations**: Intermediate calculations that help create the pivot tables and charts.

**Note**: Only the **Dashboard** sheet is intended for user interaction, while the other sheets support data preparation.

## About the Project:
This dashboard was created as part of an analysis project to explore traffic collision patterns. It uses **pivot tables** and **Pivot charts** to provide insights based on real-world data. The goal is to help users analyze the causes of traffic collisions and identify patterns that could inform safety initiatives or urban planning decisions.


