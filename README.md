# Hotel Booking Analysis Dashboard :
---

## Business Problem :
---
Hotels receives a large number of bookings from different channel ,  but they always face challenges such as high cancellation rates, changing booking patterns and it is difficult to understanding customer behavior . So i need to analyze hotel booking data to understand trends and identify key performance metrics and make better decisoions to improve revenue and reduce cancellations.

## Project Objective
---
This project is to analyze hotel booking data and create a dashboard that helps to understand booking trends , customer behavior, revenue performance and cancellation patterns.This dashboard aims to provide insights that supports better decision making for hotel management.

## Dataset Description
---

Our data set consists of the following observations which include:

Some important fields include:

**Booking Information**

* hotel – Type of hotel where the booking was made.
* lead_time – Number of days between booking date and arrival date.
* arrival_date_year – Year of arrival.
* arrival_date_month – Month of arrival.
* arrival_date_week_number – Week number of arrival.
* arrival_date_day_of_month – Day of arrival.

**Guest Details**

* adults – Number of adults in the booking.
* children – Number of children in the booking.
* babies – Number of babies in the booking.
* total_guests – Total guests included in the reservation.
* customer_type – Type of customer (Transient, Contract, Group).
* is_repeated_guest – Indicates whether the customer is a returning guest.

**Booking Details**

* market_segment – Market segment through which the booking was made.
* distribution_channel – Booking channel (Direct, TA/TO, Corporate).
* reserved_room_type – Room type originally reserved.
* assigned_room_type – Room type assigned during check-in.
* deposit_type – Type of deposit made for the booking.

**Stay Information**

* stays_in_week_nights – Nights stayed during weekdays.
* stays_in_weekend_nights – Nights stayed during weekends.
* total_stay_nights – Total number of nights stayed.

**Booking Status**

* booking_cancelled – Indicates whether the booking was cancelled.
* reservation_status – Final booking status (Canceled, Check-Out, No-Show).
* reservation_status_date – Date when the status was updated.
* previous_cancellations – Number of previous cancelled bookings.
* previous_successful_bookings – Number of successful previous bookings.

**Additional Features**

* required_car_parking_spaces – Number of parking spaces requested.
* total_of_special_requests – Number of special requests made by guests.
* days_in_waiting_list – Number of days the booking stayed in the waiting list.


# Data Cleaning :
---

Before building the dashboard, the dataset was prepared in Power BI.

* Removed unnecessary 4 columns and handled missing values.
* Created calculated columns for better analysis
* Created **Total Guests column ** and  **Total Stay Nights column**
* Created bins for **guest groups and stay duration**
* Created DAX measures for key KPIs such as bookings, revenue, and ADR
   Some important measures were created in Power BI to calculate  key performance indicator for the dashboard.
---

# Data Analysis

## Booking Insights

* The dataset contains **119K total bookings**.
* Most bookings are made through **Online Travel Agents (OTA)**.
* The majority of guests book **short stays between 1–3 nights**.

## Revenue Insights

* Total revenue generated from bookings is around **42.7M**.
* **City hotels generate higher revenue** compared to resort hotels.
* ADR trends show seasonal variations in booking prices.

## Cancellation Insights

* The overall cancellation rate is about **37%**.
* Bookings with **longer lead times tend to have higher cancellations**.
* Certain market segments show higher cancellation behavior.

## Customer Insights

* Most bookings come from **a few major countries**, showing strong geographic demand.
* Most bookings include **1–2 guests**, indicating smaller travel groups.
* Short stays dominate hotel bookings.

---

# Dashboard

The Power BI dashboard consists of **five main report pages**:

**1. Overview**
Shows total bookings, revenue, ADR, and cancellation rate.

**2. Revenue Analysis**
Analyzes revenue trends and performance across different booking factors.

**3. Booking Behavior**
Explores booking patterns, lead time, and guest stay duration.

**4. Cancellation Insights**
Highlights cancellation patterns and their impact on hotel performance.

**5. Customer Insights**
Analyzes customer types, guest distribution, and booking locations.

The dashboard includes **interactive charts, slicers, and navigation buttons** to explore the data easily.

