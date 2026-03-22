# Uber India Driver & Trip Analysis (Power BI)

##  Objective
To analyze driver performance, trip behavior, and operational efficiency for Uber India, focusing on revenue generation, cancellations, and ride patterns.

---

##  Tools Used
- Power BI  
- Excel 

---

##  Dataset
Uber ride dataset containing:
- Trip details (pickup/dropoff, duration, distance)  
- Fare & revenue data  
- Driver ratings  
- Ride status (Completed / Cancelled)  

---

##  Dashboard Preview

###  Executive Overview
![Overview](Dashboards/Executive%20Overview.png)

###  Operational Metrics
![Operations](Dashboards/Operational%20Metrics.png)

###  Driver Performance
![Driver](Dashboards/Driver%20Performance.png)

###  Trip Insights
![Trip](Dashboards/Trip%20Insight.png)

---

##  Key Insights
- ~90% trip completion rate indicates strong operational efficiency  
- Peak demand observed during evening hours (5–8 PM)  
- Tier 1 cities contribute higher trip volume and revenue  
- Cancellations are significant in specific city segments  
- Fare and distance show a clear positive correlation  

---

##  Data Modeling & Feature Engineering

###  Calculated Columns
- Trip duration derived using pickup & drop timestamps  
- Fare efficiency metrics (fare/km, fare/minute)  
- Surge and high-risk ride classification  
- City segmentation into Tier 1 vs Non-Tier 1  
- Time-based features (Trip Hour, Weekend flag)  
- Promotional eligibility logic  


---

###  Key Measures (DAX)
- Total Trips, Revenue, Distance, Drivers  
- Completion Rate & Cancellation Rate  
- Average Rating, Fare, Distance  
- Avg Earnings per Driver  
- Peak hour trip analysis  
- Driver ranking based on performance  

 
