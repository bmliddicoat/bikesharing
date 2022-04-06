# bikesharing

## Overview of the analysis: Explain the purpose of this analysis.
The analysis is to convince investors that a bike-sharing program in Des Moines is a solid business proposal.  One key stakeholder would like a bike analysis of NYC Citi data.  In using Pandas, the "tripduration" will converted from an integer to a datetime datatype.  After completion of converted datatype, Tableau was used to create set of visualizations.  These include a length of time bikes are checked out by genders, number of bike trips for all riders and gender for each day of the week, number of bike trips for each type of user (subscriber and customer) for each day of the week and at least two further visualizations to further detail vital information for stakeholders.  

## Results

### Checkout Times for Users

![alt text]()

The line graph above details the average checkout time for all users.  The peak of graph shows that five minutes is most common checkout time with 146,752 users.  The graph line increases and then "dips" drastically.  This "dip" exposes those users count of rides lowers quickly after five minutes.  This shows a skew to the left of the graph.  The user’s checkout stops the dramatic shift at 20 minutes.  This continues until the graph approaches the x-axis.  The user checkout times decreases after the six-minute mark.  It can be stated that majority of users use the service for shorter period.  


### Checkout Times for Gender

![alt text]()


The above visualization explores relationship between gender and checkout times.  The data follows a similar trend for users.  Males peak at five minutes.  Female peak at seven minutes.  Although unknown gender, has more of a plateau from six to twenty minutes.  This could be due to unknown coming from non-subscribers (less data on gender) who may be tourist using service as leisure compared to getting to work as customers.  The male gender also shows a higher usage of the service.  

### Trips Weekday per Hour

![alt text]()

The graph details the number of trips for each weekday and associated time for that day.  The highest usage of time during the week are 8 am and between 5pm-6pm.  Wednesday does show 8am trend.  5pm to 6pm is less active compared to other days of the week.  The weekends usage is following different trend.  Between the hours of 11am to 5pm, have steady trend of users.  Saturday has longer large usage till 7pm.  These weekend usage total can be explained by user not working and taking leisure activities.  

### Trips By Gender (Weekday by Hour)
![alt text]()

This visualization further explores difference between males and female users.  The trends of Trips Weekday per Hour continue.  Males having a higher volume usage show through the darker red within the graph.  The weekday hour trends, and weekend hour continue with each gender.  

### User Trips by Gender Weekday

This graph details the difference between gender and user type. The two user types are subscribers and customers.   One gender category that customer has more users is the unknown.  This is due to subscription user giving more detail on they're background and gender.  Subscriber Males use the service the most on Thursdays (259,316).  Subscriber Females use the service most from Thursday to Saturday.  Wednesday shows lowest use for both subscriber genders. Comparison of Customer versus Subscribers shows that stark difference in usage between two groups.  In using largest males’ usage day of week Thursday, the graph shows 21,034 customer trips compared to 239,316 trips for male subscribers.  Customer usage show largest increase on weekends.


## Summary: Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.


When looking into data visualizations, Ny Citi Bike programs has vital information for a Boise Program.  The first area is seeing that service is used by most subscribers compared to customers.  if implemented, Boise Team should promote the service through marketing prior to implementation.  This will ensure a stable customer base.  The use of customers or non-subscribers usage shows that tourist due use the service as well.  This is another target market to develop a marketing strategy.  The usage time times shows that all users generally use service to go five minutes.  This can help with planning where bikes should be located, how many need to be on hand for demand, when to service the bikes.  The service time should occur early in the am after usage has decreased drastically. The usage can help develop number of bikes needed in service.  Boise would need to implement data gathering to see peak hours which help determine the size of "fleet" of bikes.  

I have created three additional visualizations/graphs which can help develop the Boise program and NYC program.  I focused on the gender aspect of the study.    

![alt text]()

### Number of Riders Per Gender

![alt text]()

This shows a breakdown of users by gender.  Males are almost triple the amount of users.  If this trend occurs in Boise, it could be valuable marketing information.  It also shows that maybe there is a lack of marketing toward females in NYC.  

### Top Starting for Gender in Location

Map visualization was created to detail male, female, and unknown users.  I used a layer of census data on male/female ratio to determine if usage in higher concentration of genders would show a variance.  Also, if males were more likely to be starting one area or vice versa for females.  Where male population increased, usage increased.  The map does also expose denser areas of usage.  These our near attractions and/or places of employment.  This could help Boise develop a plan to place bike stations in higher usage areas for tourism and employment.
![alt text]()

### Top Ending for Gender in Location

![alt text]()

I created another map visualization for ending points for males, females and unknown.  I again used layer of census data on male/female ratio.  The same pattern occurs from prior graph.  There is high concentration in certain areas.  this supports the data on shorter trips and distance traveled by users. These areas can be used for service areas, pick up areas and maybe higher number of stations created.  The map also shows the areas of longer trip riders end up after a trip.  This can help with pickup and tracking 'missing' bikes.    The census data and both maps shows that higher male concentration of population can be target markets.  When designing the Boise program, stations should be in areas with similar trends.




[link to dashboard](https://public.tableau.com/app/profile/brett.liddicoat/viz/NYCCitiBikeReport_16486808917830/Story1?publish=yes)
