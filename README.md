# Bike Sharing 
Bike sharing data analysis using Tableau to visualize the data
## Overview
The purpose of this analysis is to visualize the breakdown of information provided by the New York Citibike data in order to implement a bike sharing program in Des Moines. In order to complete this visualization, I used jupyter notebook to first convert the tripduration from an integer datatype into datetime datatype. The next step was to take the new data and implement it into a new storyboard using Tableau.
## Results 
For this repository, I used [Tableau](https://public.tableau.com/views/Bike_Sharing_16633796743960/BikeSharing?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

In the Tableau story, I used the following visualizations:

![Bike_Share_1](https://user-images.githubusercontent.com/107289345/191864636-177bf3d5-9288-4140-ba64-d7a77d0a08a5.png)

The first story board shares the generic client information collected in the Citibike Data. This includes the total number of riders, the amount of riders basded on the usertype (customer or subscriber) and lastly the ridership based on gender. 

![bike_share4](https://user-images.githubusercontent.com/107289345/191865665-befe807b-6a3a-4f2e-aafa-feb0dd9a2ddb.png)

The next two story slides, I used was the Top Starting and Ending Locations, based on this visualization we can see that the majority of the rides remain within the city. Based on that information it could be seen that for the most part bike sharing is beneficial to the downtown areas and less so going further out. 

![bike_share2](https://user-images.githubusercontent.com/107289345/191866041-5ad046a7-4583-42c0-b231-bdb75cbc1324.png)

In the the Checkout slide, the first line graph we are using the data to find out how the length of time that the bikes are checked out for all riders with. In the second line graph we wanted to see the length of time the bikes are checkedout based on each gender. Both of these line graphs are also able to be filtered based on the data given. The first line graph can be filtered based on hour and the second line graph can be by both the hour and the gender. 

![bike_share3](https://user-images.githubusercontent.com/107289345/191866509-9c5e1f74-5062-452e-bf80-4aca6b28a2c3.png)

This slide is using a heatmap to graph the number of bike trips by days of the week for each hour of the day. Based on the heatmap we can see the majority of the times the bikes were used were during the morning hours and early evening hours. 

![bike_share5](https://user-images.githubusercontent.com/107289345/191866875-cf6a0471-3c4c-421b-a006-3f74b5e9948c.png)

This next heatmap graph is to show the number of bike trips by gender for each hour of each day of the week. This heatmap can also be filtered based on gender. 

![bike_share6](https://user-images.githubusercontent.com/107289345/191867175-936c80f5-bcce-4dbb-bb91-c54bebb86998.png)

This last story slide brings together the last two heatmaps plus being able to filter the data based on usertype (customer or subscriber). So, we can see each the number of bike trips based on gender for each day of the week and if the rider is a customer or a subscriber. 

## Summary
In summary, with the help of Tableau understanding the Citibike data is more comprehensible. While there are some who are able get the whole picture based on numbers. Others need different ways to visualize the same data. Another great aspect of using Tableau, would be that it also allows the data to be filtered into multiple different visualizations. One additional visualization that would be beneficial to this dataset would be to find out where did the riders start based on their gender.  Does one gender predominately start their bike trip in a different place then the others? A second visualization that could be added would be does age factor into the starting and ending locations. 
