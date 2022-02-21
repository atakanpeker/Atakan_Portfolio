# [Project 1: EC48T Financial Model Project: Overview](https://github.com/atakanpeker/R_FinancialModel_Project)

Group project for the “Financial Modelling and Its Applications Using R” course.

This project’s aim is trying to find a cross correlation between RUB/TRY and WTI/TRY price through evaluating the “Adjusted” prices.

* Using Tidyverse, Quantmod packages
* Collecting 2010-2021 data from yahoo finance, divided them into 4 time frames, and evaluating each one of them.
* Creating a basic financial model based on the trading opportunity that may come out with WTI crude oil prices and the currency.
* Calculating profit out of this opportunity.
* This report found a positive correlation and trading opportunity. However, we calculated very small profit out of it.

![](/images/2016-2018.png)

![](/images/2016-2018_ccf.png)

# [Project 2: Google Data Analytics Project: "Cyclistic" Overview](https://github.com/atakanpeker/Google_Certificate_Capstone_Project)

Capstone project of Google Data Analytics Professional Certificate program. 

This program gave me a data about a fictional company called "Cyclistic". It is a bike-share company that has casual riders and annual members.

My business task is to analyse previous 12 months of bike trip data of Cyclistic and identify trends to answer how annual members and casual riders differ.
* Using Tidyverse, Lubridate, ggplot2 packages.
* Adding new columns to the data frame such as average length of the trip durations called "ride_length" and "day_of_week" which is the day of the week riders used the bicycle.
* Including data of how many times people used this service as "number_of_rides".
* The analysis is based on how members and casual riders differ in terms of "ride_length", "day_of_week", and "number_of_rides".
* This report identified a trend according to being a member or casual and found differences with respect to day of the week such as weekday or in the weekend.

![](/images/number_of_rides_by_rider_type.png)

![](/images/average_ride_length_by_rider_type.png)
