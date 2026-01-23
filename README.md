# AtliQ Hospitality Performance Analysis

## Project Overview
This project analyzes hotel performance data for AtliQ Hospitality to understand revenue drivers, occupancy trends, pricing efficiency, and booking behavior. The analysis is built using a star-schema data model and visualized in Power BI with structured reporting and business recommendations.

## Business Objective
AtliQ Hospitality aims to optimize revenue, pricing strategy, and operational efficiency by analyzing:
- Revenue performance
- Occupancy and demand trends
- Pricing effectiveness (ADR, RevPAR)
- Booking channel realization
- Property-level benchmarking

## Dataset Description
The dataset follows a data warehouse star schema:

### Dimension Tables
- `dim_date` – Date attributes
- `dim_hotels` – Hotel and city information
- `dim_rooms` – Room category and capacity

### Fact Tables
- `fact_bookings` – Individual booking records
- `fact_aggregated_bookings` – Aggregated performance metrics

## Key KPIs
- Revenue  
- RevPAR (Revenue per Available Room)  
- ADR (Average Daily Rate)  
- Occupancy Percentage  
- Realisation Percentage  
- DSRN, DURN, DBRN  
- Cancellation Rate  
- Customer Ratings  

## Key Insights
- Luxury category contributes ~61.6% of total revenue, indicating premium segment dominance.
- Weekends show higher occupancy and RevPAR compared to weekdays.
- Certain properties outperform others in revenue and ratings, highlighting benchmarking opportunities.
- Booking platforms show variation in ADR and realisation, impacting net revenue.
- Occupancy fluctuates across weeks, suggesting demand-driven pricing opportunities.

## Business Recommendations
- Expand premium (Luxury) segment offerings and optimize pricing strategies.
- Introduce weekday promotions to improve occupancy.
- Benchmark underperforming properties against top-performing hotels.
- Optimize booking channel mix to improve realisation.
- Implement dynamic pricing during high-demand periods.

## Tools Used
- Power BI  
- Microsoft Excel  
- CSV datasets (Data Warehouse Model)

## Files
- Dashboard
- Report
- Dataset
