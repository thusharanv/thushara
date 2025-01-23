# Traffic Collision Analysis Dashboard

This Project contains an **interactive Excel dashboard** that visualizes traffic collision data. The dashboard allows users to explore various aspects of traffic accidents, including the number of injuries and fatalities, contributing factors, and trends across different boroughs and times of the day.

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
The dashboard is organized with the following sections:
   - **Charts**: Various visualizations showing traffic collision trends.
   - **Slicers**: Interactive filters for deeper analysis.

### Data Structure:
The workbook includes the following sheets:
1. **Dashboard**: The final interactive dashboard where charts, pivot tables, and slicers are displayed.
2. **Raw Data**: The raw traffic collision data used to populate the dashboard. This sheet contains details such as date, time, borough, contributing factors, and the number of people injured or killed etc. The missing data for Borough is changed for Unknown and Time and Date fields are further extracted for efficient analysis.
3. **Calculations**: Intermediate calculations that help create the pivot tables and charts.

**Note**: Only the **Dashboard** sheet is intended for user interaction, while the other sheets support data preparation.

## About the Project:
This dashboard was created as part of an analysis project to explore traffic collision patterns. It uses **pivot tables** and **Pivot charts** to provide insights based on real-world data. The goal is to help users analyze the causes of traffic collisions and identify patterns that could inform safety initiatives or urban planning decisions.
High-Level Summary of the Traffic Collision Data
This dataset contains detailed information about traffic collisions, including incidents involving pedestrians, cyclists, and motorists. The data is used to analyze patterns and trends in traffic accidents, injuries, and fatalities across different boroughs and time periods.

Key Data Features:
Collision Date and Time:
Crash Date (crash_date): The date when the collision occurred.
Crash Time (crash_time): The time when the collision took place.
Location Information:
Borough (borough): The borough where the collision occurred (e.g., Manhattan, Brooklyn, Queens, etc.).
Zip Code (zip_code): The postal code of the incident location.
Latitude & Longitude (latitude, longitude): Coordinates that pinpoint the exact location of the collision.
Collision Details:
On Street Name (on_street_name): The street where the collision occurred.
Cross Street Name (off_street_name): The nearest cross street to the collision.
Off Street Name (cross_street_name): Additional street name information if applicable.
Casualties:
Number of Persons Injured (number_of_persons_injured): The total number of people injured in the collision.
Number of Persons Killed (number_of_persons_killed): The total number of fatalities resulting from the collision.
Number of Pedestrians Injured (number_of_pedestrians_injured): The number of pedestrians injured.
Number of Pedestrians Killed (number_of_pedestrians_killed): The number of pedestrian fatalities.
Number of Cyclists Injured (number_of_cyclist_injured): The number of cyclists injured.
Number of Cyclists Killed (number_of_cyclist_killed): The number of cyclist fatalities.
Number of Motorists Injured (number_of_motorist_injured): The number of vehicle occupants injured.
Number of Motorists Killed (number_of_motorist_killed): The number of vehicle occupant fatalities.
Vehicle Information:
Vehicle Type Code: Categorization of the type of vehicle involved (e.g., car, motorcycle, bicycle, truck).
Contributing Factors: Factors identified for each vehicle contributing to the collision (e.g., speeding, distracted driving, failure to yield).
Key Insights:
This dataset allows users to explore trends in traffic collisions over time, identify high-risk locations, and examine the types of vehicles and contributing factors involved in accidents.
Users can filter and analyze the data by borough, contributing factor, and time of day to identify patterns and inform safety strategies.
The data can help local authorities, urban planners, and safety advocates focus on high-priority areas for traffic safety improvements.


