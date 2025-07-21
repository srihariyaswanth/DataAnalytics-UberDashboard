#Uber Dashboard
UBER TRIP ANALYSIS
1.A smart, interactive Power BI dashboard built to analyze Uber ride data across locations, customer behavior, and operational trends—focusing on trip volumes, location-based drop-offs, revenue insights, and peak hour trends.

2.Short Description / Purpose
The UberPro Dashboard is an interactive analytics solution developed in Power BI that enables deep insights into Uber ride data. It visualizes trip distribution, location-wise drop-offs, earnings, and demand peaks, helping stakeholders make informed decisions. The tool is designed for use by data analysts, transportation planners, city authorities, and ride-hailing companies to explore trends in mobility, efficiency, and service coverage.

3.Tech Stack
The dashboard was built using the following tools and technologies:
📊 Power BI Desktop – Main data visualization and dashboard creation platform.
📂 Power Query – Used for data cleaning, importing, and shaping raw datasets for analysis.
🧠 DAX (Data Analysis Expressions) – Used for calculated measures, such as revenue, trip count, and frequency analysis.
🛢️ SQL (via Power Query M Language) – Concepts of joins, filtering, and aggregation were applied during data transformation.
🔗 Data Modeling – Relationships established among Trip Details, Location Table, and Calendar Table to enable correct filtering and metric accuracy.
📁 File Format – .pbix for dashboard development, .png for visual preview.

4. Data Source
Source: Mock dataset for Uber ride details (simulated for analytical purposes).
The data includes ride records with the following columns:
Trip ID, Pickup Time, Dropoff Time, Pickup Location ID, Dropoff Location ID, Fare Amount, Date, etc.
Joined with Location Table and Calendar Table for readable location names and date hierarchies.

5. Features / Highlights
💼 Business Problem
In large cities, Uber collects huge volumes of ride data daily, but decision-makers often struggle to answer operational questions like:
What are the most frequent drop-off or pickup zones?
During which hours does demand peak?
Which locations generate the highest revenue?
Raw tables make it hard to answer these questions intuitively.

6.Goal of the Dashboard
To provide an interactive dashboard that helps:
Understand peak ride times and trip density
Identify high-demand and high-revenue zones
Analyze frequency patterns based on hour and location
Support city planning, driver allocation, and promotional targeting

5.Walkthrough of Key Visuals
📌 Top KPIs (Top Cards)
Total Rides: Displays the total number of trips completed
Total Revenue: Summarizes total fare earnings
Average Fare per Ride: A KPI card for profitability insights
Unique Locations Covered: Number of distinct pickup/drop-off points

6.Most Frequent Drop-off Location (DAX)
A DAX measure determines and displays the single most frequently occurring drop-off location using relationship-based filters.

.Rides per Hour – Line Chart
A time-based line chart visualizes the frequency of trips across the 24-hour clock, identifying demand peaks.

.Location-wise Drop-off Volume – Bar Chart
Shows drop-off volume for each location (translated from Location IDs to real names via relationships).

.Dynamic Filtering with Slicers
Date Range Slicer – Filter data by calendar date

.Hour Filter – Narrow down ride frequency per time slice

.Location Filter – Focus analysis on specific areas

7.Custom DAX Calculations
Used for calculating frequency metrics
Applied USERELATIONSHIP and CALCULATE for accurate trip counts against dimension tables

8.Business Impact & Insights
*Operational Optimization: Helps Uber improve resource allocation by identifying demand spikes.
*Driver Dispatching: Determine which areas require more drivers during certain hours.
*Revenue Targeting: Identify high-earning zones for promotions or fleet expansion.
*Urban Planning: City officials or planners can use this data to optimize transit and ride-hailing integration.

🖼️ Screenshots / Demo
