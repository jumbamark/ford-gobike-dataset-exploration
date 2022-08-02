# Ford GoBike Data Explorationataset Exploration Title)
## by Jumba Mark


## Dataset

This data includes information about 183412 individual rides made in a bike-sharing system covering the greater San Francisco Bay area in the month of Febraury. The dataset can be downloaded [here](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv) and has attributes such as duration, user type, start/end time, as well as additional information such as bike id, rental access method, start/end station, etc. The dataset was cleaned by removing outliers in the Exploration step while erroneous data types were corrected in the wrangling step. The following columns that were not related to the research questions were removed; `start_station_id`, `start_station_name`,`end_station_id`, `end_station_name`, and `bike_id`

## Summary of Findings

In the exploration, I found that user type affects bike usage in number of rides and trip duration. Although subscribers make a lot more trips than customers, customers generally take longer bike trip than subscribers. Both subscribers and customers take longer trips during weekend than weekdays. Subscribers take most of their trips around 7-9am(peak at 8am) and 4-6pm(peak at 5pm), typical commute hours. They are probably commuters to work/school. Subscribers took more trips during the weekdays and less on weekend. The usage trend for customers is relatively constant during the week but with higher usage on Friday and Saturday. Houly average duration for customers are higher between 10am-5pm reaching its peak at 2pm.

Outside of the main variables of interest, I verified that the the genders have more subscribers than customers with the male subscriber showing a very huge proportion of the total sample. Although tha Male have a higher count, Female and Other showed a slightly higher trip duration

## Key Insights for Presentation

For the presentation, I focus on the influence of user type. I start by introducing the numeric variable duration in seconds followed by other categorical variables (user type, start_hour and start_weekday). Afterwards I'll plot to see impacts of user type on duration and usage(in number of rides) and focus on how different groups of users use the service.




For the presentation, I focus on just the influence of the four Cs of diamonds
and leave out most of the intermediate derivations. I start by introducing the
price variable, followed by the pattern in carat distribution, then plot the
transformed scatterplot.

Afterwards, I introduce each of the categorical variables one by one. To start,
I use the violin plots of price and carat across clarity. I'm only looking at
the clarity grade plot here since it's the clearest example of how the
categorical quality grades affect diamond pricing. The other two categorical
variables, cut and color, are covered afterwards, using point plots. I've made
sure to use different color palettes for each quality variable to make sure it
is clear that they're different between plots.
