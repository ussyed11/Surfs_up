# Surfs_up

## Overview of the statistical analysis:

W. Avy is planning to invest in a surf and ice cream shop in Oahu, Hawaii.  Initially, we used hawaii.sqlite database to run and write queries for weather analysis to help him decide a perfect location to open his business.  He liked our analysis, but he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. The purpose of our this analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. We got the required data by running two seperate queries, one for the month of June and the other being December. Once we ran our queries, we stored the temperatures in a list then converted them to a dataframe. Once our dataframe is created we were able to get our summary statistics by using the .describe() method to get the average, minimum, and maximum tempretures for the given months.



## Results:

Our June tempreture results are as follow:

* Average: 75
* Minimum: 64
* Maximum: 85


Our December results are as follow:

* Average: 71
* Minimum: 56
* Maximum: 83

Both results can be seen in the following screen shots from our code:

![Screen Shot 2022-04-15 at 1 42 22 PM](https://user-images.githubusercontent.com/98566486/163603339-9f42d0b4-f694-4485-8fa2-c4188a93db33.png)
![Screen Shot 2022-04-15 at 1 42 42 PM](https://user-images.githubusercontent.com/98566486/163603370-770b9a98-9546-4092-921e-5e281d2cdafa.png)

Based on these results , we can say:

*  There is not a significant difference in average tempretures for June and December. Both months averages are in 70's.
*  There is a slight difference in Minimum tepretures as being 64 in June vs 56 in December.
*  Maximum tepretures are also in the same range of being in 80's.

## Summary:

From the results, we can conclude that it is sustainable year-round to open the surf and ice cream shop business because we have identified that the average temperature in the summer (June) was 75°F and 71°F in the winter (December).  However, we ran two additional quries to confirm our finding based on precipitation results to check the soak out days. Our analysis shows the average precipitation in those months as follow:

* June at 14%
* December at 22% 

![Screen Shot 2022-04-17 at 12 23 10 PM](https://user-images.githubusercontent.com/98566486/163723423-868835d2-2b48-458b-80a0-4da064136493.png)



![Screen Shot 2022-04-17 at 12 24 19 PM](https://user-images.githubusercontent.com/98566486/163723457-a2c7f317-490a-4d84-a1cc-2db0f490b93e.png)

