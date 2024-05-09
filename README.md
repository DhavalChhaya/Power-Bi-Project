# Voyage Line City Transit

## Overview
This Power BI project is designed to provide insightful visualizations for a Bus Transit System, helping stakeholders understand ridership patterns, bus utilization, and operational efficiency. The dashboard facilitates data-driven decisions, aiding transit managers, city planners, and operational teams to improve service and resource allocation.

## Objectives
- **Track and Analyze Ridership**: Evaluate the number of riders over different periods to identify trends and patterns.
- **Monitor Bus Utilization**: Assess how effectively the buses are utilized, pinpointing overused and underused resources.
- **Evaluate Operational Performance**: Analyze data to find peak and down hours of operation, optimizing bus schedules and routes.
- **Financial Insights**: Examine revenue through average trip fees across different routes and times.

## Data Sources
The dashboard utilizes data from the following tables:
- **Ridership**: Includes trip records like bus ID, date, time, number of riders, and rider IDs.
- **Buses**: Details each bus's ID, number, capacity, and assigned route ID.
- **Demographics**: Provides demographic data of riders such as age and gender.
- **Route**: Contains information about route names and fares.

## Key Metrics
- **Average Rides Per Trip**: Measures the average number of passengers per trip.
- **Average Trip Fee**: Calculates the average revenue per trip based on fares and ridership.
- **Busiest Route**: Identifies the route with the highest average ridership.
- **Least Busy Route**: Identifies the route with the lowest average ridership.
- **Peak and Down Hours of Operation**: Times when ridership is highest and lowest, respectively.
- **Year-over-Year (YoY) Change**: Compares ridership and revenue metrics across different years.

## Visualizations
- **Time Series Graphs**: Display trends over time for ridership and revenue.
- **Bar Charts**: Show bus utilization categories and distribution of riders by demographics.
- **Pie Charts**: Analyze demographic data or ridership by route.

## Interactive Elements
- **Date Slicers**: Allows users to filter data based on specific time frames.
- **Route Filters**: Enables viewing of data for specific bus routes.
- **Demographic Filters**: Filters metrics based on gender or age groups.

## Usage
1. Open the `.pbix` file in Power BI Desktop.
2. Refresh the data source connections if necessary.
3. Navigate through different pages and use slicers/filters to customize the view.

