# Fordgobike Dataset Exploration
## by Egbebuike Emmanuel


## Dataset
The dataset used is the fordgobike dataset. According to heavy.ai "The Ford GoBike system dataset provides anonymized, timestamped data about the start- and end- station for a bike, the user type (subscriber or casual rider), as well as some customer-reported attributes like birth year and gender"

The dataset consists of about 184,000. To use this data, I had to clean up the dataset. This involved changing column data types and extracting the day and day hour from the dataset. I dropped rows having null values and i removed the gps data of the start and end locations. This reduced the rows to about 175,000. Further into the analysis, I used the log of the duration_sec to provide better visualization.


## Summary of Findings
In this project, I was primarily concerned with how the independent variables affected the dependent variable. i.e the duration. The "bike_share_for_all_trip" would easily pass for an independent variable but i used it as a dependent variable. My findings shows that the following factors affect how long bikers will use the bike for:
 1. customer - they are perhaps the biggest influencer of how long the bike share spans. They use the bikes longer and they do not use the bikeshare for all trips
 2. days - bike share on weekends has the most of outlier per day (duration) than any other days
 3. female - female on the average bike for longer hours than male
 
 **In terms of frequency however, the following factors affect the duration somewhat because of the high number of occurences.**
 4. afternoon - during the day bike share are more akin to be used for long hours. This can partially be alluded to more people using the bikes during the day
 5. age - aside being more in the dataset, they also have highest variance in usage. The younger ones have very varied duration but surprisingly, the mean duration for all ages remain the same.



## Key Insights for Presentation
The presentation shows how the duration is likely to be affected by the user_type. It also shows how the duration varies with the day of the week. Lastly, we see that while the females are far lesser in terms of numbers, they actually have more avearge duration than the males.  