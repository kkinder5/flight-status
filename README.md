# flight-status

Predicting Flight Status
Summary
For this project I will explore publicly available data from The Bureau of Transportation (https://www.transtats.bts.gov) to explore features associated with flight status (on time versus delayed)

Goal: Predict Flight Status (on time or delayed) based on relevant features
Database Schema
Number of attributes: 5 million rows and 36 columns post feature engineering

Outcome variable:

Flight Status - On time or delayed (binary outcome)
Feature Information:

Flight Date - day,month,year of flight
Airline - airline names
Cancelled - flight cancellelation status
DepDelay - Departure Delay in minutes. Negative values = early departures
I will be using flight data from 2020 classifying flight status based on the above features. These features were chosen based on airline domain knowledge (e.g., busier months predicting delayed flights).
