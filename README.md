# Time-Zone-data-analysis
This project describes how different time zones in the same data set can offset your results and how to handle it.
I will be analyzing this analytical problem that has open ended solutions.
in this project, I performed wrangling process to make the data clean and ready for analysis.

* QUALITY ISSUES 

* https://raw.githubusercontent.com/vkoul/data/main/misc/instacart.csv
1. The 'order_delivery_time' was an object instead of datetime
2. There were white spaces in certain column names 
3. There were multiples rows with duplicated values
4. The column 'region' had San Francisco entered twice as two different regions 
5. There were no columns with specified time periods (hour, day, etc.)
6. The data included three major cities in the USA with different time zones, but this was not specified.

After resolving the issues above, the cleaned version of the data was much reliable to work on. I then was able to visualize the data using seaborn and matplotlib, and therefore draw insights to make certain inferences.

* INSIGHTS:
1. What was the highest customer rating across each region?
2. What is the delivery count in each region?
3. Which hour of the day is the busiest in each region?
4. How did the different time zones affect delivery count
5. Is there a relationship between local time and deliveries made?

CONCLUSION
This project was an interesting one to do. At the end, I compared the images of before and after I has corrected the time-zone error. Cleaning this dataset was very fun, forcing me to look beyond what was clear to the ordinary eye and fix the problem.
Appropriating the regions to their appropriate time zones saved  me a lot of time and effort.
It was eventually  clear to get accurate readings of the orders and their timing in New York, Chicago and san Fransisco.
At the end of the notebook, we would see that there is a significant difference between the graphs visualizing the delivery counts across the different regions. The last set of graphs make more sense (as deliveries are normally made during daytime) and is more readable.
 main
