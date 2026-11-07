# Bike Sharing Interactive Data Analytics Platform

In urban mobility and micro-mobility ecosystems, understanding micro-climate sensitivities, seasonal demand shifts, and commuter behavioral patterns is critical for fleet balancing and operational optimization. Quantifying the actual utilization drivers—specifically the multi-variable data slicers, hourly demand variations across seasons, and statistical correlations—requires structured dimensional modeling, robust metrics, and an executive-grade dashboard UI/UX.

I designed and developed this end-to-end interactive data analytics platform (analyzing 731 days, 17,379 hours, and 16 operational variables) to evaluate macro-rental trends, environmental correlations, and user category distributions.

## Executive Summary & Performance Overview

The platform's primary view consolidates top-level operational metrics to provide an immediate health check of total rental volume, daily averages, peak commuting hours, and user split ratios.

* **Macro Operational KPIs:** Tracks Total Rentals (3.29M), Daily Average (4,504 rentals/day), Peak Hour (5:00 PM / 17:00 at 468 rentals/hr), and a +14.2% annual growth benchmark.
* **Live Data Slicers:** Empowers dynamic filtering across 5 multi-variable dimensions (Seasons, Weather Conditions, Day Types, User Categories, and Outliers Exclusion).
* **User Segmentation Split:** Highlights that registered commuters account for 81.2% of total volume, while casual riders make up 18.8%.

## Key Dashboards Included

### 1. Executive KPI & Live Data Slicers Dashboard
![Executive KPI & Live Data Slicers Dashboard](Executive%20KPI%20&%20Live%20Data%20Slicers%20Dashboard.jpg)

Consolidates top-level operational metrics (3.29M total rentals, 4,504 daily average, 5:00 PM peak hour), powered by an interactive multi-variable data slicer for seasons, weather conditions, and user categories.

### 2. Interactive Visual Analytics & Correlation Matrix
![Interactive Visual Analytics & Correlation Matrix](Interactive%20Visual%20Analytics%20&%20Correlation%20Matrix.jpg)

Deconstructs hourly demand patterns across seasons, seasonal environmental correlations (Pearson r), and comparative peak-hour behavior between commuters and leisure users.

### 3. Comprehensive Data Dictionary & Operational Matrix
![Comprehensive Data Dictionary & Operational Matrix](Comprehensive%20Data%20Dictionary%20&%20Operational%20Matrix.jpg)

Documents all 16 operational variables within the Bike Sharing dataset, detailing data types, value ranges, and deep analytical interpretations for each metric.

## Strategic Business & Operational Insights

* **Dynamic Fleet Rebalancing:** Recommends redistributing bikes to business district stations between 7:00 AM and 7:45 AM to handle commuter peaks, and restocking leisure stations on weekend mornings.
* **Dynamic Pricing for Casual Riders:** Proposes targeted promotional discounts during spring and high-humidity days to boost non-registered engagement outside peak hours.
* **Seasonal Maintenance Scheduling:** Focuses comprehensive fleet maintenance during winter or rainy weather days (Sit 3 & 4) to ensure 100% fleet readiness during peak summer and fall.

## Data Architecture & Statistical Notes

To maintain strict data integrity while ensuring enterprise scalability, the underlying analytical model incorporates rigorous practices:
* **Statistical Handling (Simpson's Paradox):** Accounts for multi-modal vs. uni-modal shifts when disaggregating working days from holidays.
* **Environmental Normalization:** Standardizes continuous variables (temperature, apparent temperature, humidity, and windspeed) to capture non-linear behavioral drop-offs.
* **Outlier Management:** Isolates extreme weather events (heavy rain/snow) to prevent distortion of standard operational forecasting models.
