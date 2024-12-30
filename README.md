# OLA Ride Bookings

![](https://github.com/Hansal13/OLA/blob/main/OLA.jpg)

### Dashboard Link : https://github.com/Hansal13/OLA/blob/main/OLA.pbix

## Problem Statement

This dashboard helps the OLA Rides Bookings to understand their customers better and revenue. It helps the OLA know if their customers are satisfied with their services. Through different ratings, they get to know their improvement area, & thus they can improve their services by identifying these area. It also lets them know the booking status by ride, thus since by using this dashboard they have identified this problem, they can further work on factors responsible for these cancel issue. OLA can understand payment methods, vehicle types and ratings.


### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : There are four clickable button Gross, Revenue, Vehicle Type, Ratings.
- Step 5 : First added date slicer to get data for particular time range.
- Step 6 : Booking Status added in Pie chart which have 100% booking and out of that some status is there for booking like success, canceled by driver, canceled by customer, driver not found.
- Step 7 : Line chart for ride total count based on date.

# Snapshot of Dashboard (Gross Details)

![Gross](https://github.com/Hansal13/OLA/blob/main/Gross.png)
        
- Step 8 : Revenue dashboard have some cards to get key insights for revenue like total revenue, success order booking revenue, cash payment booking revenue.
- Step 9 : Added matrix table for vehicle type and booking status for it and with respect to booking value sum.
- Step 10 : Two charts for check payment methods and booking status with respect to booking value.

# Snapshot of Dashboard (Revenue)

![Revenue](https://github.com/Hansal13/OLA/blob/main/Revenue.png)

- Step 11 : For vehicle type dashboard first line chart is about vehicle type with respect to booking status total count.

- Step 12: Second chart is all about multi line chart there is vehicle type with respect to booking value total and ride distance.

# Snapshot of Dashboard (Vehicle Type)

![Vehicle Type](https://github.com/Hansal13/OLA/blob/main/Vehicle%20Type.png)

- Step 13 : For rating dashboard there is two customer and driver rating added.

# Snapshot of Dashboard (Rating)

![Rating](https://github.com/Hansal13/OLA/blob/main/Rating.png)

# Insights

Following inferences can be drawn from the dashboard;

### [1] Total Number of Booking Value = 11 M

### [2] Total Number of Booking Count = 20.41 K

### [3] Number of Booking Status Percentage 
   
    a) Success 62%
    b) Canceled by Driver 17.91%
    c) Canceled by Customer 10.2%
    d) Driver Not Found 9.9%

### [4] Total Number of Success Order Value = 7 M

### [5] Total Number of Cash Payment Count = 4 M

### [6] Average Ratings for Customer

    a) Auto - 4.00/5
    b) Bike - 3.98/5
    c) eBike - 3.98/5
    d) Mini - 4.02/5
    e) Prime Plus - 4.00/5
    f) Prime Sedan - 3.99/5
    g) Prime SUV - 3.98/5

### [7] Average Ratings for Driver

    a) Auto - 3.99/5
    b) Bike - 3.99/5
    c) eBike - 4.00/5
    d) Mini - 3.99/5
    e) Prime Plus - 4.01/5
    f) Prime Sedan - 4.00/5
    g) Prime SUV - 4.00/5
    

## Author - Hansal Amrutiya

This project is part of my portfolio, showcasing the Power BI skills essential for data analyst and business analyst roles. If you have any questions, feedback, or would like to collaborate, feel free to get in touch!

- **Personal Website**: [Hansal](https://hansal.web.app/)

Thank you for your support, and I look forward to connecting with you!
