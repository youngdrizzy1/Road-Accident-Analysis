# ROAD ACCIDENT ANALYSIS

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Post-blue)](https://www.linkedin.com/posts/eromosele-itoya_dataanalysis-excel-roadsafety-activity-7362812907065077760-3Usm?utm_source=share&utm_medium=member_desktop&rcm=ACoAAEbDOGsBGINDr5uoWo3fkmNHZc_HI1Qst6k)

### Table of Contents
- [Project Overview](#Project-Overview)
- [Tools](#Tools)
- [Workflow](#Workflow)
- [Insights](#Insights)
- [Recommendations](#Recommendations)
- [Strategic Goals](#Strategic-Goals)
- [Dashboard](#Dashboard)


### Project Overview
This project analyzes road accident data from the UK (STATS19 dataset) for 2021 and 2022, focusing on casualties to uncover patterns and support safer road initiatives. With 255,864 total casualties examined (primarily in urban areas via dashboard filters), the analysis transforms raw data into interactive visualizations. It addresses client needs like total casualties, severity percentages, vehicle type impacts, monthly trends, and factors such as road type, surface, and light conditions. Beyond numbers, it invites reflection: How can these insights drive policy changes to prevent accidents and enhance public safety?

### Tools
- Excel: For data cleaning, processing, analysis, visualization, and dashboard creation.

### Workflow
The process followed a structured approach to ensure accuracy and insightfulness.
#### 1. Data Cleaning:
- Highlighted the entire table and added filters to each column.
- Ensured no blanks in the Accident Index column.
- Corrected inconsistencies, such as replacing 'Fetal' with 'Fatal' in the Accident Severity column using Find and Replace (CTRL + F).
    
#### 2.	Data Processing
- Extracted months from the Accident Date column for trend analysis.
- Extracted years similarly.
- Grouped categories for deeper analysis:
  - Light conditions: Into 'Daylight' and 'Darkness'.
  - Road surface conditions: Into 'Dry', 'Wet', and 'Ice/Snow'.
  - Vehicle types: Into 'Agricultural Vehicle', 'Bike', 'Bus', 'Car', 'Van', and 'Other'. This grouping simplified patterns: Why might these aggregations reveal hidden correlations, like darkness linking to wet surfaces?
  
#### 3.	Data Analysis & Visualization:
- Created pivot tables for KPIs (e.g., total casualties) and insights (e.g., severity percentages).
- Built charts like pie charts for severity, bar charts for road types, and line graphs for monthly trends.
- Combined analysis with visualization to spot relationships, such as higher casualties on single carriageways during daylight.

### Insights

#### 1. Sales Trends and Top Product Categories
- Monthly Trends: Monthly sales varied, with a peak in October at $2.27M and the lowest in February at $1.95M.
  
  ![monthly](https://github.com/user-attachments/assets/016d87f5-e85e-468c-891e-d938e7c2ec23)

-  Annual Trends: Sales started off significantly, from $405K in 2015 to a peak of $11.63M in 2021.

  ![annually](https://github.com/user-attachments/assets/010119b1-c0ab-40b8-8080-f7ac50a5b64d)

-  Seasonal Trends: Fall took the leading place with $6.49M, followed by Summer with $6.35M, Spring at $6.27M, and then Winter at $6.12M.

  ![seasonal](https://github.com/user-attachments/assets/66f66083-0fe0-4a75-92ed-69e6529e3764)

-  Top Product Categories: Office Supplies, accounting for 60.14% of the revenue ($15.17M), followed by Furniture at 21.63% ($5.46M), and Technology at 18.23% ($4.60M).
  
  ![top performing product categories](https://github.com/user-attachments/assets/55d5a837-d01d-42d0-bf0b-0a1a44222214)

#### 2. Customer Retention and Loyalty Performance
- Retention Rate: 73.22% of the orders were from returning customers, which is indicative of high loyalty.
- Repeat Buyers: 62.76% of the customers had more than one order, showing a very loyal customer base.
  
  ![Returning percentage](https://github.com/user-attachments/assets/50eab98a-cd93-49fb-a641-784dca6cdae9)

#### 3.  Geographical Sales and Regional Performance
- Top-Selling Regions: The West led the way with $8.08M in sales, followed by the East at $7.19M, Central at $5.87M, and the South at $4.10M.
- Performance Drivers: Variations in regional sales performance were due to order volume and not because of order value.

  ![regions](https://github.com/user-attachments/assets/c35f74a5-5fc5-474b-b8c1-d5d09b4c275f)

#### 4. Delivery Performance and Impact on Sales
- Late Deliveries: 52.13% prevail in all regions, and the highest late delivery sales come from the West, with $4.23M, possibly affecting customer satisfaction.
  
- On-Time Deliveries (19.26%): The West led with $1.58M in on-time sales, highlighting room for improvement to boost reliability and trust.
  
- Advance Shipping (24.20%): Early deliveries in the West ($1.93M) likely enhanced satisfaction and encouraged repeat purchases.
  
- Shipping Cancellations (4.40%): The East and West had the highest canceled sales, risking customer trust and loyalty.

  - The delivery status impact on sales

    ![delivery performance](https://github.com/user-attachments/assets/c5476f3d-e6b4-46a1-909a-7de047e12958)

  - The delivery status impact on sales in different regions
    
    ![regional delivery performance](https://github.com/user-attachments/assets/0463b025-1d5e-4f2a-9b13-7b61b7a3234a)

#### 5.  Shipping Type and Delivery Efficiency
- Standard Shipping: Most used but problematic due to high delays and cancellations.
- Same-Day Shipping: Least likely to be late, but has a very minimal overall contribution.
- First and Second-Class Shipping: Perform relatively equally but need improvement in on-time deliveries.

  ![Shipping-Delivery](https://github.com/user-attachments/assets/c89e64ba-8b89-4878-a6e0-767b163a1d32)

#### 6. Customer Segmentation and Revenue Contribution

##### Revenue Contributions by Segment:
- Consumers: 51.75%, driven by strong individual demand.
- Corporate: 30.32%, sustained by business partnerships.
- Home Office: 17.94%, with room for growth.
  
  ![Customer Segment](https://github.com/user-attachments/assets/f0fe2738-4183-4d3a-af76-ebac5a329311)

##### Top Five Products by Segment:
- Consumers: Staples, Staple Envelope, and Easy-Staple Paper rule the segment.
- Corporate: More practical needs, such as Staples and Staple Envelope.
- Home Office: Lower demand but relies on versatile products like Easy-Staple Paper.

  ![Segment-Product](https://github.com/user-attachments/assets/7f225bd7-5fbe-45c9-907f-661791e7665c)

#### Product Category Contributions:
- Consumers and Corporate favor Office Supplies, while Home Office lags in Furniture and Technology demand.

  ![Segment-Category](https://github.com/user-attachments/assets/6858a163-e8d5-4164-b79b-e107ebbb83fe)

### Recommendations
- Focus on high yielding seasons and diversification of products.
- Improve loyalty programs and personal marketing in order to retain customers.
- Strengthen regional sales by improving logistics and targeting underperforming areas.
- Minimize late deliveries and cancellations; provide reliable shipping options.
- Drive growth in Corporate and Home Office segments with appropriate solutions.
- Apply data analytics to inventory optimization and targeting of campaigns.

### Strategic Goals
- Improve delivery reliability to boost customer satisfaction.
- Drive segment and regional growth for balanced performance.
- Enhance the overall customer experience to build loyalty and trust.

### Dashboard

  ![Dashboard](https://github.com/user-attachments/assets/4f464b33-b264-461f-b209-9a7f16cf277e)
