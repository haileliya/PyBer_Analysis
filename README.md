# PyBer_Analysis
Module 5 Aysnc and Challenge Repository 
Use your repository README file to write your analysis of how to address any disparities in the ride-sharing data among the city types.

Overview of the analysis: Explain the purpose of the new analysis.

The objective of this analysis is to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, I created a multiple-line graph that shows the total weekly fares for each city type. 


Results: 

Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

In this analysis, I began by loading and merging two datasets. Additionally, I used the merged dataset to find the sum, mean, and count of for total rides, drivers, and amount of fares for each city type , using the groupby method. After finding this I found the average fare per ride and per driver for each city type. After finding these values, I created a dataframe using the pd function. Next, I removed the index from the table and formatted the columns to make sure the values were showing as currency with only 2 decimal points. The table below shows the final result.

From this line graph, I can see that urban areas have the most rides and drivers. Using the table, I waws able to deduce that the average fare per ride and fare per driver is much lower than suburban and rural areas. Additionally, the urban area had more total drivers than total rides. As shown in the table, rural areas have the least amount of total rides and drivers. However, the average fare per ride and far per driver is much higher than the other area location types. 


Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

1. Based on the data analysis, my first recommendation to the CEO would be to decrease the disparaties in rural areas, which have less drivers, thus driving the average cost per ride to be very high. One possible way of decreasing this disparity is by adjusting the requirments for becoming a driver so that perhaps more people can sign up with the company.

2. Another way to address the disparity for all riders and drivers is to have incentives for driving with the company as a form of compensation. For instance, for every 10 rides that a driver completes, both the rider and driver receive some incenstive/reward.

3. Lastly, since there are more drivers than rides in urban areas and drivers in this area are only making on average $16.56/ride, it might be a good idea to reduce the % that the company takes from each ride from the driver. On average, a ride in an urban area costs $24.53 but the driver and on average the driver is receiving only 67% of what the ride costs. This is an area to investigate as a possible measure to provide financial relief for urban drivers. 