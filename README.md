# Visualizations of Citi Bike data from NYC

[link to story](https://public.tableau.com/views/Book_Mod14_1/NYCStory?:language=en-US&:display_count=n&:origin=viz_share_link)
# Analysis of Bikesharing Data from NYC

## Purpose:
This analysis was created to help convince prospective investors to invest in our new bikesharing business in Des Moines. Our experiences with the Citi Bike bike sharing program in New York City has us convinced a similar business can work here in our town of Des Moines, Iowa. A series of data visualizations have been created to detail key usage characteristics of NYC's program. It is hoped the story created from these visuals convinces investors that our bike-sharing business in Des Moines is worth their investment.

## Results:

### Ridership Demographics:
![Demographics](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Demographics.PNG)
- **Total Ridership**: In the month of August 2019 alone, some 2.34 million rides were rented in NYC through the Citi Bike bikesharing program. Of course, NYC is much bigger than Des Moines, but even scaling down for population still shows that good weather months in the summer should attract thousands of rides per month. 
- **Subscribers vs short-term customers**: As shown above, 81% of the ridership was from annual subscribers of the NYC Citi Bike program. This means our program in Des Moines should create a similar subscription plan to capture a loyal customer base who will use our bikes frequently. An attractive membership program will be key to driving long-term growth and stabilization of monthly revenues.  
- **Gender Breakdown**: Around 65% of NYC's ridership was male. This combined with the high level of subscribers means there are likely many men in NYC who use the program as part of their daily lives. Our marketing campeign in Des Moines should seek to target males most likely to use bikes in their daily lives, whether for work or play.

### What types of trips:
![Checkout_times](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Checkout_times.PNG)
- **Checkout Times**: As seen above, the vast majority of bikes are checked out for rides lasting no longer than thirty minutes. In fact, the peak appears to be around 10 minutes. We can infer that many riders are using a rental bike to make a short trip from point A to point B in a shorter time than it would take to walk or drive due to traffic.

![Checkout_times_gender](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Checkout_times_gender.PNG)
- **Checkout Times by Gender**: The short checkout times apply to both genders so there does not appear to be a gender difference in how long bikes are checked out for. However, for riders with with no gender listed (unknown) the trend of ride times is different. The majority of rides are still short (30 minutes or less), but the dropoff isn't as pronounced. These customers are more likely to be short-term users and might be less comfortable with the bikes or tourists more likely to spend time on longer rides.

### When do trips occur:
![Weekday_by_hr](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Weekday_by_hr.PNG)
- **Trips by Weekday per Hour**: Most bike rental trips occur during the daylight hours from 6am to 8pm. From Monday to Friday, the times of highest usage are during the morning (8 to 9am) and evening (5 to 7pm) commute hours. This indicates many riders are using the bikes as part of their commutes to and from work. On weekends, usage is more spread out from the mid-morning hours to early evening. This makes sense as a majority of people are not at work during the weekends. 

![Weekday_by_hr_gender](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Weekday_by_hr_gender.PNG)
- **Trips by Gender for each Weekday per Hour**: Both males and females use bikes more frequently during the workweek (Mon-Fri) morning and evening commute hours. Both appear to use bikes a bit more during evening commutes than the mornings. During the weekends, both genders again follow similiar trends with mid-day around noon being the most popular weekend times for rentals. For customers of unknown gender, more ridership appears on weekends indicating these are more leisure types, perhaps tourists, who are not subscribers, and don't want to give out their gender information.

![Weekday_usertype_gender](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Weekday_usertype_gender.PNG)
- **Trips by Usertype and Gender by Weekday**: The main point gleaned from the figure above is that male subscriber usage from Monday to Friday is the largest driver of NYC's Citi Bike business. Beyond this key point, Thursday was the busiest usage day for annual subscribers (male and female) and Saturday the busiest for short-term customers. Also of interest is that Wednesday is the least busiest day of the week, for all genders and customer types.

### Where do trips occur:
![Locations](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Locations.PNG)
- **Top Start/Stop Locations**: In NYC, most trips center on Manhattan, the most densely populated area of New York. Within Manhattan the concentration is even more pronounced in midtown Manhattan, which is the main business district in the bourough. 

## Summary:
The analysis of New York's bike sharing program have given us the insights to successfully develop a similiar program here in Des Moines. NYC's experience shows an attractive subscription model will attract the core part of the customer base who will use the bikes in their day work lives. Of course, bikes must be placed in densely populated areas with business activity so these commuters can take advantage. Although males are likely to be users, females will follow similar usage patterns. Although more attention must be paid to developing annual subscribers, short-term users cannot be neglected, particularly in areas that see a lot of activity over weekends.

#### Additional Visualizations for Future Analysis:
A start/stop map by customer type is suggested. So one map sized and colored by usage for just suscriber users, and another map just for short-term customers. This way we can determine if the customer or short-term users are focused more around tourist or recreational areas like parks. Likewise, the subscriber users focused in the main business districts specifically.
**Additionally**, it is important to visualize usage by month if possible. The location of a dataset for a colder weather month is important to calculate how much the NYC business fell off during the winter months. This will allow us to estimate the seasonality impact to our business in Des Moines. **Finally**, mapping of population density and commercial/business activity within Des Moines needs to occur. The demand will focus in these areas so it is important we determine where those are with great accuracy. 
