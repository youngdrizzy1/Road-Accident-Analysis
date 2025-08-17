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
The analysis revealed compelling patterns. Let's explore them with questions to deepen understanding.
#### 1. Overall Casualties and Severity
- Total: 255,864.
- Breakdown: Fatal (2,319, 0.91%), Serious (30,433, 11.89%), Slight (223,112, 87.20%).
  
Why might slight injuries dominate? Could early interventions in minor accidents prevent escalation?
  
  <img width="117" height="41" alt="Screenshot (485)" src="https://github.com/user-attachments/assets/b0816b27-ee42-44b7-93b9-460ac4f6ffe1" />

#### 2. Casualties by Vehicle Type
- Cars: 203,357 (79.5%), Bikes: 21,218 (8.3%), Vans: 20,416 (8.0%), Buses: 7,444 (2.9%), Agricultural: 598 (0.2%), Others: 2,831 (1.1%).

Maximum by type: Cars. What role do vehicle volumes versus safety features play?

<img width="255" height="174" alt="Screenshot (486) 1" src="https://github.com/user-attachments/assets/e6d5f229-3d84-4990-8d7a-43617f6b4bfb" />

#### 3.  Monthly Trends (2021 vs. 2022)
- 2021 Total: 134,613 (higher peaks in Nov-Dec).
- 2022 Total: 121,251 (general decline).
- Why the drop? Post-COVID travel changes or improved safety measures?

  <img width="399" height="230" alt="Screenshot (490) 1" src="https://github.com/user-attachments/assets/c350d0f7-f095-4ca1-9d37-5a00b4264ec9" />

#### 4. Light Conditions and Time of Day
- Daylight: 186,161 (72.75%), Darkness: 69,703 (27.25%).
- Does higher daylight volume reflect more traffic, or overlooked risks like distractions?
  
<img width="321" height="313" alt="Screenshot (493)1" src="https://github.com/user-attachments/assets/1421daef-e994-4a65-a1f9-37b5e721fa27" />

#### 5.  Road Type and Surface Distribution
- Road Types: Single carriageway (196,600, 76.85%), Dual (32,400, 12.66%), Roundabout (17,200, 6.72%).
- Surfaces: Dry (181,484, 70.91%), Wet (64,567, 25.23%), Ice/Snow (9,813, 3.83%).
- Notice correlations: Most on dry, single carriageways. How might weather interact with infrastructure?

  <img width="240" height="108" alt="Screenshot (492)1" src="https://github.com/user-attachments/assets/1cc427ce-948c-4942-83c3-92416a77864e" />
  <img width="257" height="178" alt="Screenshot (491)1" src="https://github.com/user-attachments/assets/c9165707-b29a-4400-86ea-637aa4a30e9a" />

#### 6. Location Focus
- All visualized data filtered to urban areas (255,864). Why prioritize urban? Higher density amplifies risks.

### Recommendations
Based on patterns, consider:
- Target car safety campaigns, as they dominate casualties. What tech like auto-braking could help?
- Boost awareness for daylight driving risks, perhaps via apps alerting to high-traffic times.
- Improve single carriageway infrastructure (e.g., better lighting on wet surfaces) to address 76.85% of incidents.
- Use monthly trends for seasonal alerts, focusing on winter peaks.
- Expand analysis to rural data for comprehensive views.

### Strategic Goals
- Empower stakeholders (governments, insurers) with data for targeted interventions.
- Reduce overall casualties by 10-20% through evidence-based policies.
- Promote data literacy in road safety to build community-driven changes.
- Foster ongoing analysis for long-term trends, like post-2022 updates.

### Dashboard
The interactive Excel dashboard summarizes all insights with filters for customization.

<img width="1008" height="498" alt="Screenshot (484)" src="https://github.com/user-attachments/assets/1f22f9ec-1c68-4e1c-a908-424241db75cb" />
