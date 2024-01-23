# CitiBike-Challenge
Module 18 Homework Assignment - Tableau Challenge

## Challenge
The task for this assignment was to aggregate the data found in the CitiBike trip history logs and find two unexpected phenomena.

1. Design 2-5 visuals per discovered phenomenon. 

2. Use your visualizations to design a dashboard for each phenomenon with an analysis explaining your findings. 

3. Create a map that plots all bike stations with a visual indicating the most popular locations to start and end a trip. 

4. Create your final presentation by creating a story that brings together the visualizations, requested maps, and dashboards. 

## CitiBike Challenge Observations
To tackle this challenge, I gathered data spanning from March 2020 to December 2020, aiming to observe the evolving patterns in CitiBike usage during the initial phases of the COVID-19 pandemic. The data from each month was consolidated into a unified CSV file, subsequently employed to generate visuals using Tableau. This analysis is designed to dissect usage based on demographics, explore the reasons behind the popularity of specific bike stations, and provide a comprehensive overview of bike usage trends in New York City.

### Tableau story can be found [here.](https://public.tableau.com/views/CitiBikeChallenge_17056298633890/CitiBikeAnalysisObservations?:language=en-US&:display_count=n&:origin=viz_share_link)

### Bike Stations by Geography and Popularity
![Bike Stations Map](Images/Bike%20Station%20Map.png)

The leading 10 stations remain consistent when analyzed based on their roles as both starting and ending points. Their popularity is probably attributed to the substantial population density in their respective areas. Additionally, examining the map reveals that these stations are situated at or in close proximity to train stations, which could be an additional factor contributing to the high number of recorded trips to and from these locations.
#

### Usage Summary
![Usage Summary](Images/Usage%20Summary.png)

Since New York Governor Andrew Cuomo declared the confirmation of the first recorded case of COVID transmission, a cumulative total of 287,820 trips had been documented. Subscribers accounted for 65% of the riders during this period, with the 31-40 age group registering the highest number of trips. Subsequent to this announcement, there was a notable decline of 48% in ride usage, attributed to the ongoing COVID-19 outbreak and the imposition of the NYC lockdown.
* User Types: 
    * Subscriber: Annual Membership
        * Subscribers are primarily NYC residents.
    * Customer: 24-Hour or 3-Day Passholders
        * Customers are often considered tourists.
#

### Usage by Day and Time
![Usage by Day and Time](Images/Usage%20by%20Day%20and%20Time.png)

The prime hours for riding within this period were from 5 pm to 7 pm on weekdays and 1 pm to 5 pm on weekends. Notably, summer emerged as the peak riding season, influenced primarily by favorable weather conditions. Apart from weather considerations, New York City initiated the initial phase of its reopening plan in early June. By August, various gathering establishments like bowling alleys, museums, and cultural institutions had resumed operations. Transitioning into early October, the city reached Phase 4 of its reopening process, encompassing the reopening of museums, gardens, and gyms. Interestingly, October marked the peak in trip numbers during our analysis, potentially reflecting the sustained efforts of the reopening process.
* Service Availability:
    * Bikes are available 24/7, 7 days a week.
    * Riders have access to all stations.

## References
* [CitiBike Logo](https://images.search.yahoo.com/search/images?p=citibike+logo&fr=mcafee&type=E210US105G0&imgurl=http%3A%2F%2Fallvectorlogo.com%2Fimg%2F2017%2F07%2Fciti-bike-logo.png#id=0&iurl=http%3A%2F%2Fallvectorlogo.com%2Fimg%2F2017%2F07%2Fciti-bike-logo.png&action=click)

* [CitiBike NYC](https://citibikenyc.com/homepage)

* [COVID-19 NYC Timeline](https://en.wikipedia.org/wiki/Timeline_of_the_COVID-19_pandemic_in_New_York_City#2021)