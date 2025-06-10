# OLA-Data-Analysis-Project
Analyzed Ola ride data using SQL to answer key business questions on ride patterns, revenue, and customer behavior. Built an interactive dashboard in Power BI to visualize trends, hotspots, and performance insights.
## 🎯 Project Objectives
1.Keep the overall booking status success for this data at 62%. If the booking status is successful, then only
fare charge ratings, average VTAT, average CTAT, and other data will be there.
2.Make sure orders cancelled by customers should not be more than 7%
3.Make sure orders cancelled drivers should not be more than 18%
4.Also, increase the number of orders on weekends and match days. Keep match day by using the
following dates.
5.keep incomplete rides less than 6%
6.Keep order value high on weekends


## 📂 Dataset Used
<a href="https://github.com/piiuushh/OLA-Data-Analysis-Project/blob/main/Bookings-20000-Rows.xlsx">Bookings Dataset</a>
The dataset includes synthetic or anonymized ride data with fields such as:
1. Date
2. Time
3. Booking_ID
4. Booking_Status
5. Customer_ID
6. Vehicle_Type
7. Pickup_Location
8. Drop_Location
9. V_TAT
10. C_TAT
11. cancelled_Rides_by_Customer
12. cancelled_Rides_by_Driver
13. Incomplete_Rides
14. Incomplete_Rides_Reason
15. Booking_Value
16. Payment_Method
17. Ride_Distance
18. Driver_Ratings
19. Customer_Rating

## 🧠 SQL Queries Answered
1. Retrieve all successful bookings:
2. Find the average ride distance for each vehicle type:
3. Get the total number of cancelled rides by customers:
4. List the top 5 customers who booked the highest number of rides:
5. Get the number of rides cancelled by drivers due to personal and car-related issues:
6. Find the maximum and minimum driver ratings for Prime Sedan bookings:
7. Retrieve all rides where payment was made using UPI:
8. Find the average customer rating per vehicle type:
9. Calculate the total booking value of rides completed successfully:
10. List all incomplete rides along with the reason:

## 📊 Power BI Dashboard Visualizations

The Power BI dashboard includes:
1. Ride Volume Over Time
2. Booking Status Breakdown
3. Top 5 Vehicle Types by Ride Distance
4. Average Customer Ratings by Vehicle Type
5. cancelled Rides Reasons
6. Revenue by Payment Method
7. Top 5 Customers by Total Booking Value
8. Ride Distance Distribution Per Day
9. Driver Ratings Distribution
10. Customer vs. Driver Ratings

## 🛠 Tools Used

- **SQL** (MySQL / PostgreSQL)
- **Power BI**
- **Excel** (optional pre-processing)

