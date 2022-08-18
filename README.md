# CitiBike data analysis

## Project Overview
This project is an analysis of New York Citi Bike data, using data visualization tools to explore the viability of a bike-sharing business in Des Moines.

## Resources
- Data Source: [Citi Bike Data](https://www.citibikenyc.com/system-data), [201908-citibike-tripdata.csv.zip](https://s3.amazonaws.com/tripdata/201908-citibike-tripdata.csv.zip)
- Software: Python 3.7.5, Conda 4.13, Jupyter Notebook 7.1.3, Tableau Public 2022.2.2

## Results

Tableau Dashboard link: [https://public.tableau.com/app/profile/miguel.boada/viz/BikeSharingCompleted/Dashboard1?publish=yes](https://public.tableau.com/app/profile/miguel.boada/viz/BikeSharingCompleted/Story1?publish=yes)


### Overview 
![image](https://user-images.githubusercontent.com/60283799/185261731-9f7fa863-fadd-4f41-bf8f-1d1bd0427d12.png)

There are a few different observations we can make from this snapshot:
- The majority of riders were male and CitiBike Subscribers
- There were over 2 Million trips taken in August of 2019 
- Though there is a large range when it comes to birth year of riders, most fall between 1980 and 2000

### Checkout times by gender 

This graph shows the hours and minutes with most bikes checked out by Gender: <br> <br>
![image](https://user-images.githubusercontent.com/60283799/185263236-814a0b8e-44f4-48e1-b3c6-e9af0d0dab5e.png)

- Bikes are most commonly checked out for 4-6 hours
- Males are checking out more bikes than Females

### Trips by Weekday per Hour
Below is a heatmap showing the trips by hour and weekday, with darker sections being the higher count: <br> <br>
![image](https://user-images.githubusercontent.com/60283799/185262602-124dd2ce-1dc0-49cc-b5ce-29bfd1497ba0.png) ![image](https://user-images.githubusercontent.com/60283799/185262611-0d8421f0-7f02-44d0-81b6-065ad880e0a7.png)
- Thursday and Saturday seem to be the most popular days for rentals 
- Monday and Tuesday also have high rental rates

### User Trips by Gender and Weekday: 
The chart below is another heatmap, this time showing the count of trips grouped by day of the week and by user type: <br> <br>
![image](https://user-images.githubusercontent.com/60283799/185262894-26eb1173-fbc8-439b-983e-dd75392fdbc6.png)
![image](https://user-images.githubusercontent.com/60283799/185262884-66d4a330-6f5a-417f-9512-871aa09cbc98.png)
- This chart shows how much more men really rent bikes
- It also continues the thursday-heavy trend


## Summary
In conclusion, bikeshare services are remarkably popular in busy metropolitan areas, where occupied real estate is densely packed and parking spaces may be scarce. The user base is made up mostly of male subscribers, providing regular income to the program. More outreach should be done to attract female riders.

If I were to pursue additional lines of inquiry for analysis and visualization, given the data provided, I would explore:

- Trip starting and ending locations during morning and evening rush hour time-windows, to display the flow of traffic between neighborhoods at peak hours;
- Average trip duration, by birth year, by gender, to explore if there was any difference in male or female or un-gendered riders as they age.
- Explore the data by year and see how it has changed 
- Compare this to other methods of commuting and posibly see why people prefer their certain method
