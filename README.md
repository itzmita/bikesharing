# bikesharing
# Learning Tableau
## Overview
This Tableau story can be seen, in its entirety, at this [link](https://public.tableau.com/app/profile/moumita.dhali/viz/NYCCitiBikeStory_16573370260920/NYCCitiBikeStory?publish=yes)

### Background
This project was to analyze bikeshare data from CitiBike company in New York City in order to explore if a similar program can be established in  in Des Moines, Iowa. Des Moines is a very different city than NYC, the demographics, weather etc can be different but this analysis might help answer a few key questions such as

* What type of people uses Bike Ride Sharing programs?
* What location of a city uses this program the most?
* What time of day are bikes used the most and the least?
* How much time riders are using the bikes?

## Results
![image](https://user-images.githubusercontent.com/3753839/178090075-73cf12a2-289a-475d-9c84-d61e1bf7c269.png)

![image](https://user-images.githubusercontent.com/3753839/178090076-7ed52fb0-efb0-4e1c-8c0b-2e3e21f2a2b5.png)


![image](https://user-images.githubusercontent.com/3753839/178090080-f7d50b27-501b-442c-a647-d00f5efe4f32.png)

From the above screenshots we see that out of all the riders, there are more subscribers who would regularly use the program which is good for the company. The Customers may be tourists or less frequent users. Also we can see that there are comparatively more number of male riders than the female. The company can investigate and see how to appeal to female riders.

![image](https://user-images.githubusercontent.com/3753839/178090089-5c681a14-3c67-4841-acb5-327e74342aa1.png)

From the above screen shot its seen that during the early hours of 2 - 6 AM, it’s a good to perform bike maintenance activities. 
![image](https://user-images.githubusercontent.com/3753839/178090100-40a3766a-dee4-4947-9c77-37d32b542d26.png)

![image](https://user-images.githubusercontent.com/3753839/178090103-3c7a1b90-9fa3-422f-8f8a-e3f9e13c8c23.png)


The above screen shot shows when the bike trips started. The darker the circle is the more number of riders started their trip at that location. The place where the concentration of the big dark circles are may be the heart of the city. The less lighter small circles are may be for residential areas. 

### Deliverable 1: Change Trip Duration to a Datetime Format
In this task we converted the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). 
![image](https://user-images.githubusercontent.com/3753839/178090142-a0b16b43-dd3a-4e43-9de0-11005515eb42.png)

A new column was created with the converted value as shown below.
![image](https://user-images.githubusercontent.com/3753839/178090157-08e0adf5-1dce-4fa4-8be4-c9cc1070256b.png)

This data was then uploaded in a spreadsheet for the next deliverable

### Deliverable 2: Create Visualizations for the Trip Analysis
#### How long bikes are checked out for all riders and genders. 
![image](https://user-images.githubusercontent.com/3753839/178090189-29cd8ceb-168f-49b6-b091-608f5b258cc2.png)

The above screenshot shows the duration in minutes a rider uses a bike. Here we see most of the durations are within an hour length.  
![image](https://user-images.githubusercontent.com/3753839/178090206-82f63de7-0313-4653-9352-70b7bc786ade.png)

The above screenshot shows again that male riders are more than the female/unknown riders. But mostly all the rides are completed within an hour length.
	
#### How many trips are taken by the hour for each day of the week, for all riders and genders. 
![image](https://user-images.githubusercontent.com/3753839/178090225-82724e90-bc9d-4c2e-8758-b82ecc89b39b.png)

![image](https://user-images.githubusercontent.com/3753839/178090226-a00bbb53-8b86-468d-80f7-3e72edb74dc8.png)

The above 2 screen shots show heatmap of weekly usage patterns. Its evident that most of the rides are during weekdays during morning 6-9 AM and 4-8 PM. Also here its seen the male riders are more than female/unknown. 

#### A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender. 
![image](https://user-images.githubusercontent.com/3753839/178090253-43e44a6f-0151-4525-baab-96a1c01ba611.png)

The above screen shot again shows that male riders are more using this program. 

### Deliverable 3: Create a Story and Report for the Final Presentation

This Tableau story can be seen, in its entirety, at this [link](https://public.tableau.com/app/profile/moumita.dhali/viz/NYCCitiBikeStory_16573370260920/NYCCitiBikeStory?publish=yes)

## Summary
In conclusion, bikeshare program can be very successful in a busy metropolitan area like the NYC that we analyzed, where there are more real estate in a densely packed area and also less parking space so people don’t get their cars for commute. As seen from the above screenshots, mostly male riders are using this program. More outreach should be done to attract female riders, however male riders seem to be a reliable market.

More analysis can be done on the lines of during the peak hours of weekday where do we see more bikes starting and where they are ending. Are they happening near train stations or any corporate park or schools? This will show us a flow of the rides and we can estimate how it will work in Des Moines. 

Also we can bring in Age in the equation. Is it mostly used by adults/teenagers etc and where are they mostly starting and ending etc.  

