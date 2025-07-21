Uber Ride Analytics Dashboard

A smart, interactive Power BI dashboard built to analyze Uber ride data across locations, customer behavior, and operational trends—focusing on trip volumes, location-based drop-offs, revenue insights, and peak hour trends.

---

2. Short Description / Purpose

The UberPro Dashboard is an interactive analytics solution developed in Power BI that enables deep insights into Uber ride data. It visualizes trip distribution, location-wise drop-offs, earnings, and demand peaks, helping stakeholders make informed decisions.

This tool is designed for use by data analysts, transportation planners, city authorities, and ride-hailing companies to explore trends in mobility, efficiency, and service coverage.

---

3. Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Main data visualization and dashboard creation platform  
- 📂 **Power Query** – Used for data cleaning, importing, and shaping raw datasets for analysis  
- 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures such as revenue, trip count, and frequency analysis  
- 🛢️ **SQL (via Power Query M Language)** – Concepts of joins, filtering, and aggregation were applied during data transformation  
- 🔗 **Data Modeling** – Relationships established among Trip Details, Location Table, and Calendar Table  
- 📁 **File Format** – `.pbix` for development and `.png` for dashboard previews

---

4. Data Source

**Source:** Mock dataset for Uber ride details (simulated for analytical purposes).  
The dataset includes ride records with the following columns:

- Trip ID  
- Pickup Time  
- Dropoff Time  
- Pickup Location ID  
- Dropoff Location ID  
- Fare Amount  
- Date  

The data was joined with a Location Table and Calendar Table to provide readable location names and date hierarchies for time-based analysis.

---

5. Features / Highlights

**Business Problem**  
In large cities, Uber collects massive volumes of ride data daily. However, decision-makers often struggle to answer questions like:
- What are the most frequent drop-off or pickup zones?  
- During which hours does demand peak?  
- Which locations generate the highest revenue?

Raw data makes it difficult to extract actionable insights efficiently.

**Goal of the Dashboard**  
To deliver an interactive dashboard that:
- Identifies peak ride times and trip density  
- Highlights high-demand and high-revenue locations  
- Analyzes ride frequency patterns by time and place  
- Supports dispatch planning, marketing efforts, and city-level transportation decisions

**Walkthrough of Key Visuals**

- **Top KPIs (Top Cards):**  
  - Total Rides  
  - Total Revenue  
  - Average Fare per Ride  
  - Unique Locations Covered  

- **Most Frequent Drop-off Location (DAX):**  
  A custom DAX measure identifies the most frequently occurring drop-off location using relationship-based logic.

- **Rides per Hour – Line Chart:**  
  Displays ride frequency across a 24-hour cycle to identify peak demand hours.

- **Location-wise Drop-off Volume – Bar Chart:**  
  Highlights total drop-offs per location, joined with readable names.

- **Filtering Options:**  
  - Date Range Slicer  
  - Hour Filter  
  - Location Filter

- **Custom DAX Measures:**  
  - Used `USERELATIONSHIP`, `CALCULATE`, and other DAX functions for frequency and revenue logic

---

6. Business Impact & Insights

- **Operational Optimization:** Improves resource allocation by identifying demand spikes  
- **Driver Dispatching:** Helps identify locations requiring more driver presence during specific time blocks  
- **Revenue Targeting:** Spotlights zones with highest earnings for business expansion or promotions  
- **Urban Planning:** Assists in optimizing ride-hailing integration into city infrastructure planning

---

7. Screenshots / Demo

**Overview Analysis**  
![Overview](https://github.com/srihariyaswanth/DataAnalytics-UberDashboard/blob/main/Snapshot%20of%20Overview%20Analysis.png)

**Time Analysis**  
![Time Analysis](https://github.com/srihariyaswanth/DataAnalytics-UberDashboard/blob/main/Snapshot%20of%20TimeAnalysis.png)

**Details Tab**  
![Details](https://github.com/srihariyaswanth/DataAnalytics-UberDashboard/blob/main/Snapshot%20of%20Details.png)
