


# Bay Wheels's trip data analysis
# by Ayman El Taweel





# Dataset:

-Intro:
We are going to analyze a Bay Wheels's trip dataset which includes data about each trip such as :          duration,start time and place, end time and place and customer categories as well.


-Data source: 
https://www.lyft.com/bikes/bay-wheels/system-data


- Wrangling steps : 
	-We will make the column names all in small letters and replace any space by '_'.
	-Dropping unneeded columns.
	-Converting time columns into its right type.
	-defining a function to return (( month)) when each trip had started.
	-defining a function to return (( day )) when each trip had started.
	-defining a function to return (( hour )) when each trip had started.
	-Converting column values to be in minutes.





## Summary of Findings:

1) The vast majority of trips ends in other stations, So,Bay Wheels require a strong communication and coordination among their stations in order to keep controling its assets.

2) Most trips don't exceed 25 minutes with a peak from 5 to 20 minutes . This may be an inference that most people use bikes as quick transportation mean for only near location.

3) Trips count increases around 8AM and 5PM . This may be beacause people go and return from their workplaces, schools and so on at these times. So, Bay Wheels's should make sure of bikes availability at these times in order to keep satisfying its customers.*

4) The number of trips experience a noticeable decrease on both "sunday and saturday". This makes sense as they are the weekly vacation .

5) It's crystal clear that there are no trips in the period from January to May ,inclusive, In other words, No trips starts in winter, May be beacuse of snow in the streets.

6) The number of trips carried out by subscribers are nearly 4 times as of non-subscribers. So, Subscribers are more important for Bay Wheels's. Also, This ratio makes sense as frequent users tend to subscribe beacause of economic perspective.

7) Non-subscribers ride bikes more in vacation days than in workdays. While Subscribers ride bikes more in workdays than vacation days. But Subscribers trips' count remains higher than non-subscribers in most cases.

8) Non-subscribers are often higher in terms of trips' duration. While subscribers are often higher in terms of trips' count.

9) Trips' count reached its peak in October then started to fall again as winter was coming.




## Key Insights for Presentation

1) The number of trips carried out by subscribers are nearly 4 times as of non-subscribers. 
2) Non-subscribers are often higher in terms of trips' duration. While subscribers are often higher in terms of trips' count.
