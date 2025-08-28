# Inside Rapido: Bangalore Rides – Tableau Dashboard  

## Overview  
This project analyzes **50,000 rows of Rapido ride data from Bangalore (June–August 2024)** to explore customer behavior, cancellations, revenue drivers, and ride preferences.  
The Tableau dashboard allows interactive exploration of ride trends across service types, time periods, and trip characteristics.  

## Features  
**KPIs at a glance**  
- Cancellation %  
- Monthly revenue  
- Most used ride type  

**Visualizations**  
- **Revenue per Day** – Tracks daily performance with clear peaks and dips.  
- **Time-of-Day Trends** – Avg. fare and ride count segmented into Morning, Afternoon, Evening, and Night.  
- **Service Mix** – % contribution of ride types (bike, auto, cab economy, bike lite, parcel).  
- **Revenue by Distance & Duration** – Insights into how short, medium, long, and very long rides contribute to revenue.  
- **Interactive Controls** – Filters for ride type and custom date ranges.  

## Key Insights  
1. **Bike rides dominate**, making up ~30% of total rides.  
2. **Auto and Cab Economy** together contribute ~45% of rides.  
3. **Revenue drivers** are longer rides (16–30 km, 1+ hour) despite lower ride counts.  
4. **Cancellations average 9–10%**, fairly stable across time.  
5. **Most preferred payment method is UPI**, which is used **100% more than cash**, highlighting a strong digital-first customer base.  

## Dataset  
- **Files**: `rides_data.csv`, `rides_data_fixed.xlsx`  
- **Size**: 50,000 rows  
- **Columns**:  
  - `date` – ride date  
  - `service_type` – auto, bike, bike lite, cab economy, parcel  
  - `distance_km` – ride distance  
  - `duration_mins` – ride duration  
  - `fare` – ride revenue  
  - `payment_method` – UPI, Cash, Card, Wallet  
  - `status` – completed or cancelled  

## Tools Used  
- **Excel** – Data cleaning and preprocessing  
- **Tableau Public** – Dashboard design and visualization  

## How to View  
The interactive dashboard is available on Tableau Public:  
👉 (https://public.tableau.com/app/profile/divjyot.singh.suri/viz/InsideRapidoBangaloreRides/FinalDashboard?publish=yes)

