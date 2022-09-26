# Bike-sharing services usage data exploration
## by Jinwoong Nam


## Dataset

The data consists of information regarding 183,412 usages of the bike-sharing service in the greater San Francisco Bay area during February 2019. This includes duration, start/end time, station, member birth year, member gender, user type, whether or not bike sharing is used for the whole trip, and so on.  
Before starting exploration, null rows were removed and some data types were changed.


## Summary of Findings

After the log transformation, the duration (sec) followed a normal-like distribution with a mean of ~700 sec. Generally, the usage is high on weekdays and low on weekends. During the day, morning (8-10 am) and evening (4-6 pm) have the highest usage. Not surprisingly, most of the users are in their 20s and 30s. The number of male users in total usage is more than three times bigger than the number of females. For user type, the subscribed users are much more (about eight times) than non-subscribed users (that is, customers). Most of the users use bike-sharing services as a part of their trip rather than a whole trip.

Also, non-subscribers have a longer duration than subscribers implying subscribers tend to spend a shorter time per trip than the non-subscribers. Also, Female has a distribution of a little longer duration than male. The distribution of start_hour for the "bike share for all trip = yes" group is upshifted compared to the "no" group and this is attributed to very low usage in the morning and relatively high usage in the evening and night of this group. We can guess not many users exploit bike-sharing services for their whole trip in the morning.

Non-subscribers tend to spend more time per trip than subscribers at any start hour. Also, the "bike share for all trip = yes" group has the distribution of the duration that is relatively widespread at any start hour while the "no" group has very much concentrated on the 300 - 1000 sec.


## Key Insights for Presentation

For the presentation, I focus on the things below.
1) Distribution of the duration that shows most of the trips are between 2.5 and 33.3 minutes 
2) High usage on weekdays in the morning and evening obtained from start time distribution
3) A large number of subscribers compared to the non-subscribers
4) Patterns showing the users who travel only with bike-sharing services have less usage in the morning

With the above findings and visualizations, I argue that many users subscribe to the service and commute by the combination of bike and subway/train/bus or others. These findings give many insights into developing strategies to help encourage more people to use the services.



