

# Hotel Booking Analysis Dashboard
----






# Table of Contents

* Case Study
* Dataset Description
* Data Cleaning
* Data Analysis
* Dashboard

---

# Case Study

This project analyzes hotel booking data to understand booking trends, customer behavior, revenue performance, and cancellation patterns.
The goal of the dashboard is to help hotels understand their business performance and identify areas where improvements can be made.

---

# Dataset Description

The dataset contains hotel booking information with details about customers, booking patterns, and hotel performance.

Some important fields include:

**Booking Information**

* Hotel – Type of hotel (City Hotel or Resort Hotel)
* Arrival Date – Date when the guest arrives
* Lead Time – Number of days between booking and arrival
* Stays in Weekend Nights – Weekend stay duration
* Stays in Week Nights – Weekday stay duration

**Customer Information**

* Adults – Number of adults in the booking
* Children – Number of children
* Country – Guest country

**Business Information**

* Market Segment – Source of booking
* Distribution Channel – Booking channel
* ADR – Average Daily Rate
* Reservation Status – Booking status (Canceled / Not Canceled)

---

# Data Cleaning

Before building the dashboard, the dataset was prepared in Power BI.

Steps performed:

* Removed unnecessary columns and handled missing values
* Created calculated columns for better analysis
* Created **Total Guests column (Adults + Children)**
* Created **Total Stay Nights column (Week Nights + Weekend Nights)**
* Created bins for **guest groups and stay duration**
* Created DAX measures for key KPIs such as bookings, revenue, and ADR

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

