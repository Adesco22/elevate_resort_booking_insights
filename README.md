# Elevate Resort – Booking & Revenue Insights Dashboard (Power BI)

## Overview
This Power BI dashboard analyzes booking and revenue data from Elevate Resort, a global hospitality brand. The company experienced stagnation in revenue growth and wanted to identify data-driven strategies using historical booking data.

## Business Objectives
- Identify booking and consultation trends over time
- Pinpoint top-performing countries by booking volume
- Understand revenue contributions by market segments and customer types
- Analyze cancellation patterns in relation to lead time and payment mode
- Calculate total revenue and losses due to cancellations

## Dataset
The project uses three key tables:
- `HotelBookings`: Core dataset with booking dates, prices, status
- `GeoData`: Location and country information
- `DataDictionary`: Metadata reference for understanding the columns

## Data Preparation
Custom columns and metrics created using DAX:
- `Revenue`
- `Average Daily Rate (ADR)`
- `Real Revenue` (Revenue from non-cancelled bookings)
- `Revenue Lost` (from cancelled bookings)
- `ConsiderOtherFactors` (Cancellation flag)

## Key Insights
- Peak bookings occur between June and August
- USA, UK, and France are the top countries for bookings
- Online bookings have higher cancellations than direct bookings
- Long lead times are more likely to result in cancellations
- Corporate and direct market segments provide more stable revenue

## Tools Used
- Power BI Desktop
- DAX
- Data Modeling
- Insight Visualization

## Dashboard Highlights
- KPI cards for Total Bookings, Revenue, Cancellations, and ADR
- Line and bar charts for trends and segmentation
- Geo-map for country insights
- Slicers for interactivity (Booking Status, Year, Country, Segment)

## Screenshots
![Dashboard Preview](/dashboard-preview_.jpeg)

---

## Author
Emmanuel – Data Analyst | Educator | Power BI Enthusiast
