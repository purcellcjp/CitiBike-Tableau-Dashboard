# Citi Bike Analysis using Tableau

## Problem

You have been hired as the lead analyst for the [New York Citi Bike](https://en.wikipedia.org/wiki/Citi_Bike) program. You are now resonsible for overseeing the largest bike-sharing program in the United StatesCitibike is the largest bike sharing program in the United States. In this new role, you will b expected to generate regular reports for city officials looking to publicize and improve the city program.

Datasets: Bike data is collected, organized, and made public on the [Citi Bike Data](https://www.citibikenyc.com/system-data) webpage.

## Task

**Design 2-5 visualization for City Officials and Answer the following Questions and explore the data for decision makers 

1. What are the peak hours in which bikes are used ?
2. What are the top 10 stations in the city for starting a journey?
3. What are the top 10 stations in the city for ending a journey?  
4. What is the gender breakdown of active participants (Male v. Female)?
4. How does the average trip duration change by age?
5. Any additional findings. 

**Advanced Option**

* Design a dashboard with an analysis explaining why the phenomena may be occuring. 

**City officials would also like to see one of the following visualizations:**

1. (Basic) A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.
2. (Advanced) A dynamic map that shows how each station's popularity changes over time (by month and year).  

* The map includes a write-up unveiling any trends that were noticed during analysis.

## Solution

A dynamic Tableau dashboard was created to provide real time analytics of the unique trips between stations that were made for a specified period. The dashboard contains visualizations on the following details:

- Map of Trip Routes
- Station Count
- Average Trip Distance
- Average Trip Duration (in minutes)
- User Membership
- Bicycle Type Used
- Top 5 End Station Destinations
- Peak Riding Times

The analytics are dynamically controlled by the following Filters:

- Date Range
- Start Station
- End Station
- Distance Traveled


## Presentation:  

[Tableau Dashboard](https://public.tableau.com/views/CitiBike_17303964060410/CitiBikeDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Dataset

The dataset used was the [January 2024 CitiBike Trip Data](https://s3.amazonaws.com/tripdata/202401-citibike-tripdata.csv.zip).

## Analysis of January 2024 CitiBike data

- Who uses the bike more - members are casual riders?
-- Members

- Who takes longer single trips?
-- Casual members

- What are the peak hours of use?
-- Monday through Friday 8 AM and 5 PM

- What is the average trip distance and duration?
-- 1.11 miles and 10.8 minutes

