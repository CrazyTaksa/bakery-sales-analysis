# Bakery Sales Analysis

## Business Problem
The goal of this analysis is to support the decision on where to look for new point and which products should be included at the opening based on sales demand patterns.

## Stakeholder
Bakery owner

## Data Overview
- Time period: 07.01.2026-13.02.2026
- Main attributes: date, time, district, total revenue, items sold, product categories

## Data Cleaning & Preparation
Validated time and data, splitting column date time into two and converted date and time formats. Changed name of districts to English and added field “Unknown” instead of NULL values. Cleaned outliers in total.

## Key Metrics
- Metric 1: Total revenue by district
- Metric 2: Average amount of items in the most popular districts by day of week
- Metric 3: Average consumption of different pastries per day

## Key Insights
1. Hupyeong-1-dong, Hupyeong-2-dong, Hupyeong-3-dong, and Mion-dong together bring 46% of revenue 
(images/Total revenue in different districts of Seoul.jpg)
2. Average sold amount of items in the city - 94 items per day when in this 4 districts its 150-313
(Images/Average amount of items sold in the city.jpg)
3. The most popular item - angbutter, average consumption per day - 13 when other items 1-5 
(Images/Average consumption of pastries.jpg)

## Recommendation
Based on the comparison of average item volume by day of week across the city and within the four selected districts that together generate 46% of total revenue, the analysis indicates more stable and consistently higher demand in these districts compared to the city average. This stability reduces operational risk related to inventory planning and staffing, supporting the recommendation to search for a new bakery location with strong infrastructure access to Hupyeong-1-dong, Hupyeong-2-dong, Hupyeong-3-dong, and Mion-dong.

## Limitations
Delivery time, distance, rent cost, exact geolocation

## Tools Used
- Google Sheets
