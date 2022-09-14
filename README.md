# Analysis of Bikesharing Data from New York City

[link to story](https://public.tableau.com/views/NYCCitiBikeData_16629532598900/NYCBikesharingDesMoinesNext?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)
![Story](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Story.PNG)

## Purpose:
This analysis was created to help convince prospective investors to invest in our new bikesharing business in Des Moines, Iowa. Our experiences with the Citi Bike bike sharing program in New York City has us convinced a similar business can work here in our town of Des Moines. A series of data visualizations have been created and to detail key facts and usage characteristics of NYC's program. It is hoped the story created from these visuals convinces investors our business proposal is worth their investment.

## Results:

### Ridership Demographics:
![Demographics](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Demographics.PNG)
- **Total Ridership**: In August 2019 alone, some 2.34 million rides were rented in NYC through the Citi Bike bike sharing program. Of course, NYC is much bigger than Des Moines, but even scaling down for population still shows that we could expect to attract thousands of rides per month in the good weather summer months. 
- **Subscribers vs short-term customers**: As shown above, 81% of the ridership was from annual subscribers of the NYC Citi Bike program. This means our program in Des Moines should create a similar subscription plan to capture a loyal customer base who will use our bikes frequently. An attractive membership program will be key to driving long-term revenue growth and reducing revenue variability.  
- **Gender Breakdown**: Around 65% of NYC's ridership was male. This combined with the high level of subscribers means there is significant demand from men who use bike rentals as a regular part of their lives. Any marketing campaign in Des Moines should seek to target this key demographic.



### Types of Trips:
![Checkout_times](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Checkout_times.PNG)
- **Checkout Times for All Users**: As seen above, the vast majority of bikes are checked out for rides lasting no longer than thirty minutes. In fact, the peak appears to be around five minutes long. As such, this likely indicates most riders are using rental bikes not as leisure, but as a means to get from one place to another nearby. Whether to avoid the hastle of driving or because it's quicker than walking, the benefits of travel by bike should be a core highlight of any marketing push.


![Checkout_times_gender](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Checkout_times_gender.PNG)
- **Checkout Times by Gender**: Breaking out checkout times by gender above does not highlight any real difference between males and females. The vast majority of both take short trips. However, the trend of ride times is a little different for riders with with no gender listed (unknown). The majority of their rides are still short (30 minutes or less), but the dropoff isn't as pronounced. This might indicate more of a leisurly focus or pace for these riders, as well as being more predominately short-term customers. These types of users would likely be less willing to note their gender and probbaly less likely to move as quickly and purposefully as experienced subscribers might.


### When Trips Occur:
![Weekday_by_hr](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Weekday_by_hr.PNG)
- **Trips by Weekday per Hour**: To begin, most bike rental trips occur during the daylight hours, which follows common sense. From Monday to Friday, the times of highest usage are during the traditional morning (8 to 9am) and evening (5 to 7pm) commute periods. This indicates many riders are using the bikes as part of their commutes to and from work. On weekends, usage is lower and more spread out from the mid-morning hours to early evening. This means that much of NYC's ridership is likely working a more traditional Mon-Friday workweek and using weekend rentals for other miscellaneous uses. 


![Weekday_by_hr_gender](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Weekday_by_hr_gender.PNG)
- **Trips by Gender for each Weekday per Hour**: Shown above, both males and females use bikes more frequently during the workweek (Mon-Fri) morning and evening commute hours. Both also seem to slightly favor evening commute rentals over mornings. During weekends, both genders again follow similiar trends with mid-day around noon being the most popular weekend rental times. For riders customers of unknown gender, more ridership occurs on weekend afternoons, perhaps indicating more leisure or one-off usage for errands or special occurances.


![Weekday_usertype_gender](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Weekday_usertype_gender.PNG)
- **Trips by Usertype and Gender by Weekday**: Right away, the darkest shading for male subscribers stands out, reiterating that they are the key driver of ride demand. In general, subscriber (male & female) demand is focused most heavily from Mondays to Fridays, with a midweek lull on Wednesdays followed by the the busiest day on Thursdays. Short-term customers of all genders are weekend focused, with Saturday the busiest day. Also of interest is that the Wednesday lull found in subscribers also appears in short-term customers.


### Where Trips Occur:
![Locations](https://github.com/bfox87/bikesharing/blob/main/Visualizations/Locations.PNG)
- **Top Start/Stop Locations**: As the maps above show, most NYC trips center on Manhattan, the most densely populated area of New York. Within Manhattan the concentration is even more pronounced in midtown Manhattan, the main business district in the bourough. Although Des Moines is more spread out than NYC, there are still many urban areas bustling with activity that we can focus on.


## Summary:
The analysis of New York's bike sharing program have given us the insights to successfully develop a similiar program here in Des Moines. NYC's experience shows a well-designed subscription model will attract the core part of the customer base who will use the bikes in their daily lives. Of course, bikes must be placed in densely populated areas and areas with business activity so these commuters can take advantage. Males are more likely to be users, but females will follow similar usage patterns. Finally, although more attention must be paid to developing annual subscribers, short-term users cannot be neglected, particularly because a series of good experiences could then lead them to becoming subscribers.

#### Additional Visualizations for Future Analysis:
A start/stop map by customer type is suggested. So one map sized and colored by usage for just suscriber users, and another map just for short-term customers. This way we can determine if the short-term customers are focused more around tourist or recreational areas like parks. Likewise, if the subscriber users focused in the main business districts or areas high-density residential. **Additionally**, it is important to visualize usage by month if possible. This dataset analyzed here was for August, but there are likely datasets for colder weather months. We can then calculate how much the NYC business fell off during the winter months, enabling us to estimate the seasonality impact to our business in Des Moines. 
