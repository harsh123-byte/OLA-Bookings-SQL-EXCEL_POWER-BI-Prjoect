OLA Data Analytics Project
This project simulates an OLA Cab Booking System dataset containing 20000+ rows and 19 columns, covering bookings, customers, vehicles, cancellations, payments, and ratings for a 1-month period(JULY) 

The project is implemented using SQL, Excel, and Power BI for data storage, analysis, and visualization


Data Columns

1.Date

2.Time

3.Booking_ID

4.Booking_Status

5.Customer_ID

6.Vehicle_Type

7.Pickup_Location

8.Drop_Location

9.V_TAT (Avg Vehicle Time to Arrive)

10.C_TAT (Avg Customer Time to Arrive)

11.Cancelled_Rides_by_Customer

12.Cancelled_Rides_by_Driver

13.Incomplete_Rides

14.Incomplete_Rides_Reason

15.Booking_Value

16.Payment_Method

17.Ride_Distance

18.Driver_Ratings

19.Customer_Rating



Vehicle Types

.Auto

.Prime Plus

.Prime Sedan

.Mini

.Bike

.eBike

.Prime SUV

📄EXCEL analysis - 20000+ rows data File (OLAexcel.xlsv)

📄 To Insert 20000+ row  Into MYsql - (OLAsql.csv)

📄 INSERT Slides in POWER BI - (ola-Slideshub.pptx)

📄 SQL Queries Script -  (OLAquery.sql)

📄  Power BI Dashboard File - (OLA DASHBOARD.pbix)

📄 Questions of SQL and POWER BI - (Sql-powerBI Ques-Ans.pdf)


 


SQL Analysis

The dataset is stored in MySQL/PostgreSQL for running queries.


SQL Queries Implemented

1.Retrieve all successful bookings

2.Find the average ride distance for each vehicle type

3.Get the total number of cancelled rides by customers

4.List the top 5 customers who booked the highest number of rides

5.Get the number of rides cancelled by drivers due to personal & car-related issues

6.Find the max & min driver ratings for Prime Sedan bookings

7.Retrieve all rides where payment was made using UPI

8.Find the average customer rating per vehicle type

9.Calculate the total booking value of successful rides

10.List all incomplete rides with reasons


📄 SQL Queries Script
 (OLAquery.sql)

 

 Power BI Dashboard

The dataset is visualized in Power BI to derive business insights.


SLIDES of Power BI Dashboard Views

SLIDE 1- Overall

-Ride Volume Over Time

-Booking Status Breakdown


SLIDE 2- Vehicle Type

-Top 5 Vehicle Types by Ride Distance

-Average Customer Ratings by Vehicle Type


SLIDE 3- Revenue

-Revenue by Payment Method

-Top 5 Customers by Total Booking Value

-Ride Distance Distribution Per Day


SLIDE 4- Cancellations

-Cancelled Rides by Customers (Reasons)

-Cancelled Rides by Drivers (Reasons)



SLIDE 5- Ratings

-Driver Ratings Distribution

-Customer Ratings Distribution

-Customer vs Driver Ratings


📄 Power BI Dashboard File
 (OLA POWERBI DASHBOARD.pbix)

 

Key Insights:

.Majority of rides completed successfully with few cancellations.

.Prime Sedan and Mini show higher booking values.

.UPI is the most preferred payment method.

.Top customers contribute significantly to total revenue.

.Cancellation reasons vary, with "Change of Plans" and "Personal & Car Issues" being most frequent.

.Strong correlation between Driver Ratings and Customer Ratings.
