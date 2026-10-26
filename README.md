# Uber-Trip-Analysis

# Project Overview

This project explores Uber trip data for **June 1–30, 2024**, using Microsoft Power BI to analyze booking trends, revenue, trip distances, vehicle preferences, pickup and drop-off locations, and demand patterns across different hours and days of the week.

The goal is to transform raw trip records into actionable business insights that can help improve operational efficiency, support data-driven decision-making, and identify opportunities to enhance the customer experience.

The project features three interactive dashboard pages: **Overview Analysis, Time Analysis, and Details**, allowing users to examine performance at both summary and transaction levels.

# Business Objectives

The key objectives of this analysis are to:

- Evaluate overall booking performance and booking value.
- Identify peak booking hours and high-demand days.
- Analyze revenue contributions across payment methods and trip types.
- Compare booking volume, revenue, and distance across vehicle categories.
- Identify frequently used pickup and drop-off locations.
- Explore trip patterns to support resource allocation and operational planning.

# Tools and Technologies

- **Microsoft Power BI** — Dashboard development and interactive visualizations.
- **Power Query** — Data cleaning and transformation.
- **DAX** — Measures, calculated metrics, and KPI calculations.
- **Data Visualization** — Charts, tables, KPI cards, and time-based analysis.

# Dashboard Features

### 1. Overview Analysis

The overview page provides a high-level picture of Uber's performance during the reporting period.

Key metrics include:
- Total bookings
- Total booking value
- Average booking value
- Average trip distance
- Total trip distance
- Average trip time

The page also explores payment methods, day and night trip revenue, vehicle performance, daily booking trends, and popular pickup and drop-off locations.

### 2. Time Analysis

The time analysis page examines how booking demand changes throughout the day and week.

It includes:
- Bookings by pickup time.
- Bookings by day of the week.
- Hour-by-day booking heatmap.
- Hourly distribution of booking activity.
- Interactive date and city filters.

These visuals help identify periods of high demand and potential opportunities to improve driver availability and fleet allocation.

### 3. Trip Details

The details page provides a transaction-level view of the data, including:

- Trip ID and pickup date.
- Pickup time and vehicle category.
- Payment type and passenger count.
- Trip distance and booking value.
- Pickup location and booking count.

This page supports detailed exploration and helps users investigate individual trips behind the aggregated dashboard metrics.

## Key Performance Indicators

The dashboard displays the following overall metrics:

| KPI | Dashboard Value |
|---|---:|
| Total Bookings | 103.7K |
| Total Booking Value | Approximately $1.6M |
| Average Booking Value | $15.00 |
| Average Trip Distance | 3 miles |
| Total Trip Distance | Approximately 349K miles |
| Average Trip Time | 16 minutes |

*Figures are rounded as displayed on the dashboard.*

## Key Insights

### 1. Booking demand varies significantly throughout the day

The hourly trend shows that booking activity is relatively low during the early morning hours, rises considerably after approximately 6:00 AM, and remains elevated through much of the afternoon.

**Business implication:** Driver availability and fleet deployment should reflect hourly demand rather than remain constant throughout the day.

### 2. Weekends record the highest booking volumes

Sunday recorded approximately **19.2K bookings**, followed by Saturday at **18.7K**. Friday recorded the lowest displayed daily total, at approximately **9.3K bookings**.

**Business implication:** Weekend demand may require additional driver availability, especially around popular pickup areas.

### 3. UberX dominates booking volume

UberX recorded approximately **38.7K bookings**, making it the leading vehicle category in the dashboard. It also generated approximately **$583.9K in booking value**.

**Business implication:** Maintaining adequate UberX availability could be important for meeting customer demand. Other vehicle categories should also be evaluated for their profitability and customer segments.

### 4. Uber Pay is the leading payment method

Uber Pay contributed approximately **$1.10M**, or **70.74%**, of the displayed booking value. Cash contributed around **$443K**, or **28.54%**, while the remaining payment methods accounted for a relatively small share.

**Business implication:** Digital payments represent a major part of booking value. Reliable payment processing and a smooth digital payment experience should remain operational priorities.

### 5. Night trips contribute more booking value than day trips

Night trips generated approximately **$940K (60.5%)** of booking value, compared with approximately **$614K (39.5%)** for day trips.

**Business implication:** Night operations are commercially important and should be considered when planning driver availability, customer support, and safety measures.

### 6. Certain pickup and drop-off locations appear frequently

Penn Station/Madison Square West was identified as the most frequent pickup point, while Upper East Side North was identified as the most frequent drop-off point.

**Business implication:** Frequently used locations could be considered when planning driver positioning and evaluating demand hotspots. These locations should be assessed alongside trip timing and driver supply before operational changes are made.

## Recommendations

Based on the dashboard findings, the following actions are recommended:

1. **Optimize driver allocation:** Use hourly and daily booking patterns to position drivers in areas and time periods with stronger demand.

2. **Prepare for weekend demand:** Review driver supply and booking performance on Saturdays and Sundays to reduce potential waiting times and missed bookings.

3. **Prioritize core vehicle availability:** Monitor UberX demand while evaluating the performance of UberXL, Uber Comfort, Uber Black, and Uber Green across booking volume and revenue.

4. **Strengthen digital payment reliability:** Maintain a seamless Uber Pay experience while ensuring that other payment options remain accessible to customers.

5. **Improve location-based planning:** Analyze high-frequency pickup and drop-off locations alongside time-of-day patterns to identify opportunities for more efficient driver positioning.

6. **Evaluate night-time operations:** Since night trips account for a larger share of booking value, assess driver coverage, safety procedures, and support availability during these periods.

7. **Monitor performance continuously:** Track booking volume, booking value, trip duration, distance, and vehicle performance over time to identify changes in customer demand and operational efficiency.

## Conclusion

This project demonstrates how Power BI can turn trip-level data into a structured business intelligence solution. By combining KPI cards, time-series analysis, vehicle comparisons, payment analysis, location insights, and transaction details, the dashboard provides a clearer understanding of Uber's booking activity during June 2024.

The analysis highlights the importance of demand-based driver allocation, weekend planning, digital payment reliability, and location-aware operations. These insights provide a foundation for further investigation into service efficiency, customer experience, and revenue performance.

## Repository Contents

Suggested repository structure:

```text
Uber-Trip-Analysis/
├── README.md
├── data/
│   └── dataset.zip
├── dashboard/
│   └── Uber_Trip_Analysis.pbix
└── screenshots/
    ├── overview-analysis.png
    ├── time-analysis.png
    └── trip-details.png
```


## About This Project

This is a data analytics portfolio project focused on business intelligence, exploratory data analysis, and interactive dashboard development using Power BI.

**Skills demonstrated:** Data cleaning, data modeling, DAX, KPI development, data visualization, trend analysis, and business insight communication.
