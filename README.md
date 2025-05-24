# Airline_Data_Management_and_Analysis_Using_Power_BI
# Power BI Project – Airline Data Management & Analysis

## About the Project

This Power BI project focuses on managing and analyzing airline data using interactive dashboards. The main goal was to work with multiple datasets (Flights, Passengers, Tickets) and turn them into meaningful insights through data cleaning, modeling, DAX calculations, and effective visualization.

The project includes building a comprehensive dashboard with filters, drill-down capabilities, and scheduled data refresh, making it ready for real-world business use.

## Datasets Used

- Flight Information
- Passenger Information
- Ticket Information

These datasets were imported into Power BI and prepared using Power Query.

## Project Workflow

### 1. Data Preparation and Cleaning
- Used Power Query to load and transform the data.
- Removed duplicates, handled missing values, and ensured correct formatting of columns (like dates, integers, etc.).
- Ensured data consistency across all three tables.

### 2. Data Modeling
- Created relationships using `FlightID` as the key.
- Established one-to-many and many-to-one relationships between the datasets.
- Ensured proper cardinality and referential integrity.

### 3. Enhanced Data Insights
- Added a conditional column to classify flights as either **“Best”** or **“To Be Improved”** based on their status.
- Used "Column from Examples" to extract the flight number from the `FlightNumber` column for a cleaner representation.

### 4. DAX Calculations
- Created DAX measures for:
  - Total passengers per flight.
  - Total tickets booked.
  - A filtered table showing only the "Best" flights.

### 5. Visualizations
- **Passenger Count by Airline** (Clustered Column Chart)
- **Ticket Booking Status** (Pie Chart)
- **Flights by Airline and Destination** (Stacked Bar Chart)

Each visualization was designed to give a clear overview of operational and booking performance.

### 6. Interactive Features
- Added slicers for Airline and Destination to dynamically filter visuals.
- Created Quick View buttons using bookmarks for easier navigation between key insights.
- Built dedicated pages for each airline to allow detailed drill-down.

### 7. Final Dashboard & Deployment
- Designed a clean, user-friendly dashboard that highlights key metrics and trends.
- Set up **Row-Level Security (RLS)** so users from "Airline A" can only access their own data.
- Configured **daily scheduled refresh** at 5 PM to keep the dashboard updated with the latest data.

## Tools Used

- Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- Power BI Service (for publishing, RLS, and scheduled refresh)

## What I Learned

This project helped me strengthen my understanding of the end-to-end Power BI workflow — from data preparation and modeling to creating interactive dashboards and deploying them with security settings. It also gave me hands-on experience in using DAX and building reports that are both insightful and user-friendly.

