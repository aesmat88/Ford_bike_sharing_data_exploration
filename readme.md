# (Ford GoBike tripdata Exploration)
## by (Ahmed Esmat)


## Dataset

> The data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area by Ford GoBike. Ford GoBike is the Bay Area's bike share system. Bay Area Bike Share was introduced in 2013 as a pilot program for the region, with 700 bikes and 70 stations across San Francisco and San Jose.
> It is a 1-month data of trips with more than 180000 record. The data was messy, have inapproperiate feeatures data types and missing values, specifically in members gender, birth year and station names.

> - The features data types were corrected.
> - Then, a trial to recover station names using available staion coordinates, but in vain. These data was dropped.
> - Missing member gender and birth year date was dropped.
> - Some outliers were handled based on condition.
> - Some Features were add such as distance between start and end stations (using stations' coordinates), trip speed, member Age and the day of the month.


## Summary of Findings

> More Than 90% of our travellers are using subscribtion services.
> About 75% of bike rider members are males.
> About 2% of bike riders prefer not to tell about gender.
> It is clearly showen in the age distribution that the minimun age of travellers are 20 years, This may support a regulation set for bike riders or a data cut setting 20 years old as a threshold.
> The most frequent members age is between 27 ~ 37 Years old.
> It is noted that "San Francisco Caltrain Station 2 (Townsend St at 4th St)", "Market St at 10th St" and "Montgomery St BART Station (Market St at 2nd St)" are most crowded (Down town area, travel stations, Markets area) as they have the highest frequency for start / end stations of bike users.
> On the opposite, "Parker Ave at McAllister St", "Palm St at Willow St", "16th St Depot", "Willow St at Vine St", "21st Ave at International Blvd" are common in lowest frequency for start / end stations of bike users, this may reflect outskirts of the city or a luxury life (that depends on own cars).
> There is 3453 recorded trips with "Zero" distance (i.e. The bike was start and end the trip at the same station).
> 892 trips out of those 3458 are last for less than 5 min, this is highly supporting a hypothesis of a trouble with the bike or unexperienced / new member.
> 1498 trips out of those 3458 consumed more than 20 mins, this may represent somebody has a small journey with friends or delivering a request to another.
> Lower calculated speed may reflect traffic issues, long idle time for something purchasing, old members, unexperienced members or bike issues during travelling.
> There is only 9 trips with distance more than 10 Km. 5 of them has a high speed with duration less than 40 mins.
> High trip speed -over 26 Km/hr-are rare and may occured by experienced cyclist.
> The majority of trips lasts for (250 ~ 1000 secs), while the majority of trips moves in a distance between (0.8 ~ 2.5 Km) and the average travelling speed varies between (8 ~ 14 Km/hr).
> Females showing relatively lower average age in compare with Males and other.
> Other (or "unknown gender") showing a peak at ages between 50 and 60 years.
> Subscribers are distributed equally overall the month with some peaks on weekly basis (suggested to be weekends).
> Customers are increasingly have a service at the second half of the month. It may reflect a non-routine work or bi-weekly work basis pattern.
> A linear relationships on log scales for trip distance and trip duration.
> Exculding a higher trip duration, the customer/undefined gender relationship is quiet strong in positive direction.
> Generally, overall the month, The subscribers' average trip speed is higher than customers.
> The average travelling speed by Males is higher than Females.


## Key Insights for Presentation

> The added Features (distance between start and end stations, trip speed, member Age and the day of the month) introduce new concepts for the data analysis process.
> A trial of recovering stations data using the available data, but in vain due to no reference was found.