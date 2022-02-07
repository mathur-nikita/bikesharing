# bikesharing

## Overview

### Purpose of Statistical Analysis 

After using a bike share service to travel around New York City with our friend Kate, we've come up with the idea to open a similar bike share service in Des Moines, Iowa.  Kate has found a potential angel investor for this project, and now we need to present a proposal.  As part of this proposal we are analyzing existing data about the bike share service in NYC (Citi Bike) and how it works there, and using that to determine how this service might work in Des Moines and what the potential risks might be.  The data used for this analysis was collected during the month of August.

### Resources

- Link to Tableau Story: [Citi Bike Bikeshare Service Analysis](https://public.tableau.com/app/profile/nikita.mathur2534/viz/CitiBikeBikeshareService/CitiBikeBikeshareService)
- screenshots folder containing images from the Tableau story

## Results 

### Results of Analysis

Out of the 2,344,224 riders recorded, about 81% of them are annual subscribers while about 19% of them are short-term customers.

![screenshots/customers_vs_subscribers.JPG](https://github.com/mathur-nikita/bikesharing/blob/main/screenshots/customers_vs_subscribers.JPG)

The highest concentration of starting points for trips is downtown, which could indicate a high concentration of tourists.  It could also represent people who work downtown and commute using the service on weekdays.

![screenshots/starting_points.JPG](https://github.com/mathur-nikita/bikesharing/blob/main/screenshots/starting_points.JPG)

The highest concentration of ending points for trips is downtown, which could indicate a high concentration of tourists.  It could also represent people who work downtown and commute using the service on weekdays.

![screenshots/ending_points.JPG](https://github.com/mathur-nikita/bikesharing/blob/main/screenshots/ending_points.JPG)

The majority of trips last between 1 - 20 minutes, with the most at 5 minutes.

![screenshots/checkout_times.JPG](https://github.com/mathur-nikita/bikesharing/blob/main/screenshots/checkout_times.JPG)

The majority of male riders have about 5 minute trips.  The majority of female riders have about 6 minute trips.  The majority of riders unknown make trips that last between 5 - 30 minutes, peaking at around 11 minutes.

![screenshots/checkout_times_by_gender.JPG](https://github.com/mathur-nikita/bikesharing/blob/main/screenshots/checkout_times_by_gender.JPG)

On weekdays, there are high concentrations of trips that start between 7 - 9 AM and end bertween 5 - 7 PM.  This seems to reflect commute times for those who work downtown.  On weekends trips tend to be more spread out, starting around 10 AM and ending around 7 PM.  This might reflect people who are casually traveling through the city for leisure as there are no significant hotspots.

![screenshots/trips_per_hour.JPG](https://github.com/mathur-nikita/bikesharing/blob/main/screenshots/trips_per_hour.JPG)

The heatmaps below reflect the same information as above, though it can be seen there are a higher concentration of male riders opting to commute on weekdays than anyone else.

![screenshots/trips_per_hour_per_gender.JPG](https://github.com/mathur-nikita/bikesharing/blob/main/screenshots/trips_per_hour_per_gender.JPG)

The following heatmap reflects that the majority of annual subscribers who use the service are males who travel during weekdays.  Female subscribers have a more balanced distribution of riders through the week, though still using the service a bit more on weekdays.  Unknown subscribers use the service equally all week.

For short-term subscribers across all genders, the distribution of rides through the week is almost equal with maybe a little more activity on weekends.

![screenshots/trips_by_gender_by_weekday.JPG](https://github.com/mathur-nikita/bikesharing/blob/main/screenshots/trips_by_gender_by_weekday.JPG)

### Summary of Results

The Citi Bike bikeshare service seems to be a popular option for traveling around the city, especially in the downtown area.  It's an eco-friendly option to using cars, and great for enjoying the sights at one's own pace.  It's a good mode of travel for tourists, but it also seems to be highly favored during the weekdays.  This implies that many people who live in the downtown area opt to commute to and from work using the bikeshare service.  

Two additional visualizations are suggested for future analysis:

1) It would be great to have more information on short-term customers who become annual subscribers to estimate the number of people who would be more likely to use the service regularly after giving it a trial run.  Information on subscribers cancelling their subscriptions and/or converting to short-term customers would also help in determining if the service retains its popularty after time has passed.

2) The information we collected was for the month of August, a time when the weather is more pleasant in NYC.  It would make sense to collect information on the usage of the bikeshare service during times of the year with different weather (rainy seasons, winter, etc.).  Based on that and the weather patterns in Des Moines we could then determine the usage of bikeshare service predicted througout the year.
