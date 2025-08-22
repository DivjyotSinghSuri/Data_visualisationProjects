# ✈️ Flight Review Analytics Dashboard

## 📌 Overview

This project analyzes passenger reviews of global aircrafts using an interactive Tableau dashboard. The reviews are rated on a **1 to 5 scale**, and the dashboard helps visualize aircraft performance, customer sentiment trends, and regional review patterns to support better decision-making.

🔗 **Live Dashboard:** [View on Tableau Public] - https://public.tableau.com/views/FlightReview_17473852126420/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## 🎯 Project Goals

- Analyze customer reviews to evaluate aircraft performance and service quality.
- identify trends in passenger satisfaction by timeline, traveller type, region, and travel class.
- Provide an accessible self-service analytics tool that supports business analysts and customer experience teams in monitoring real-time sentiment patterns.

---

## 🛠️ Tools & Technologies

- **Tableau Public** – Interactive dashboard and data visualization
- **Microsoft Excel** – Data preprocessing and formatting

---

## 📊 Dashboard Features

- **Bar Chart:** Average rating by airline  
- **Bar Chart:** Number of reviews per airline  
- **Map Visualization:** Average rating by reviewer country  
- **Time Series Trends:** Analyze rating patterns over time  
- **Filters:** Dynamic filters for airline, reviewer country, seat type, flight type, and rating value  
- **Interactive Dashboard:** Clicking on one chart updates all others in real time

---

## 🔍 Process

1. **Data Cleaning**
   - Removed incomplete or invalid records
   - Normalized airline names and categorical values
   - Grouped the airplanes which had reviews less than 50

2. **Filter Design & Implementation**
   - Created dynamic filters in Tableau for:
     - Traveller type
     - Aircraft type
     - Seat Class (Economy/Business/First Class)
     - Time period
     - Rating for a specific section
Enabled cross-filtering to update all visuals based on user selections.
    
3. **Dashboard Design**
   - Created in Tableau with multiple interactive elements
   - Used tooltips, color coding, and filters to enhance user experience
   - Used bar charts, maps and tooltips for guided insights.

---

## 📈 Key Insights

- **Aircrafts with higher review volumes** often showed more variation in ratings, reflecting broader operational scale and mixed customer experiences.  
- **Top-rated aircrafts** consistently scored above 4.2, indicating strong overall customer satisfaction.
- **High review volumes** were linked to more **polarized feedback**, suggesting varied passenger experiences.

---


