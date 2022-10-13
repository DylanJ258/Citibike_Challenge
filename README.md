[link to dashboard](https://public.tableau.com/app/profile/dylan.jungmann/viz/DylanJungmannCitiBike/NYC?publish=yes)


# Citibike_Challenge
## Overview
Now that we've gotten a good idea of how to create our story, there is still some more work to be done to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

For this analysis, you’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, you’ll create a set of visualizations to:

* Show the length of time that bikes are checked out for all riders and genders
* Show  the number of bike trips for all riders and genders for each hour of each day of the week
* Show the number of bike trips for each type of user and gender for each day of the week.

Finally, you’ll add these new visualizations to the two you created in this module for your final presentation and analysis to pitch to investors.

## Results

### Checkout Times for Users
* Majority of the trips are under 20 minutes


<img width="1391" alt="Screen Shot 2022-08-28 at 5 44 55 PM" src="https://user-images.githubusercontent.com/104036750/187097802-be365c94-76a9-45cd-a689-90b3dc22e4b0.png">


### Checkout Times by Gender
* Males use the most bikes and take the longest trips


<img width="1415" alt="Screen Shot 2022-08-28 at 5 45 03 PM" src="https://user-images.githubusercontent.com/104036750/187097809-d729bb87-2c47-4675-99c2-1d88d9ef8033.png">


### Trips by Weekday for Each Hour
* Usage is lowerest between 12-5AM
* Usage is highest between 5-6PM


<img width="1406" alt="Screen Shot 2022-08-28 at 5 45 52 PM" src="https://user-images.githubusercontent.com/104036750/187097833-16bcb2be-4f3b-4bfd-8892-c7802859c3dd.png">


### Trips by Gender (Weekday per Hour)
* Males make up the largest share of users


<img width="1413" alt="Screen Shot 2022-08-28 at 5 46 19 PM" src="https://user-images.githubusercontent.com/104036750/187097840-f898d293-0ad0-4de6-aba9-12ceae9fce21.png">


### User Trips by Weekday
* Male subscribers make up the largest share of usertypes


<img width="1419" alt="Screen Shot 2022-08-28 at 5 46 29 PM" src="https://user-images.githubusercontent.com/104036750/187097851-ee6f29aa-3729-4cb3-95e7-99e211a5dc71.png">


### August Peak Hours
* Peak hours are 5-6PM


<img width="1419" alt="Screen Shot 2022-08-28 at 5 46 38 PM" src="https://user-images.githubusercontent.com/104036750/187097852-c4cad871-c86d-4285-af62-123679c87420.png">


### Checkout Times for Bikes by Weekday
* Thursday is the busiest day


<img width="1362" alt="Screen Shot 2022-08-28 at 5 46 47 PM" src="https://user-images.githubusercontent.com/104036750/187097859-03a498c4-ba78-4953-8288-2cfa115abca6.png">


## Summary
From the analysis we can see that:
* The majority of rides last less than 20 minutes.
* Males use the most bikes and take the longest trips.
* 6-9AM and 4-8PM seem to be peak times during the week, which may imply that many users are riding the bikes to and from work.
* The peak time is 5PM in August.
* Thursdays are the busiest.

Suggestions for Future Analysis:
* Incorporating a visualization for weather.
* Incorporating a visualization of peak tourism times.

