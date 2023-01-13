# PyBer_Analysis

Overview of the analysis: Explain the purpose of the new analysis.
Results: Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.
Summary: Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

## Overview of the analysis
### The purpose of this analysis was to use Matplotlib to create line charts, bar charts, scatter plots, bubble charts, pie charts, and box & whisker plots to analyze the data for the Pyber ride share apps to compare ride fares, different cities, and types of communities. We can format the necessary information to better visualize the chart coding output by adding titles, axes labels, legends, and custom colors if needed. We can also determine the mean, median, and mode using Pandas, Numpy, and SciPy statistics to gather the requested Pyber data and display the information accordingly.

## Results
### We began generating our data by importing the correct infomation from the provided ride and city CSV files. A dataframe is created to gather data on total ride counts, total drivers, amount of ride fares, and averages fares per drivers & rides.

As we can see from the summary image below that there are some obvious takeaways:
  * The urban communities have a cheaper rate per driver & rides with more total rides & drivers available resulting in the total fare being the highest among the three communities
  * Being in the rural areas caused an increase to the rates per driver & ride due to insufficient amount of drivers available resulting in the lowest outcome for total rides & fares.
  * The median between the three communities came out to be the suburban community with more totals then the rural areas but less totals then urban areas.
![Ride Share Data](https://user-images.githubusercontent.com/118647523/212169903-19a12395-6a60-433b-9587-3c9d41fac6ff.png)

### By creating the  Matplotlib "fivethirtyeight" chart style for the specific timeline we can almost see the similarities in data for the short timeframe given. A dataframe was created to display the graph by certain groups and specific dates then resampling or pivoting the data as needed.
Listed below you can compare the total fares by city type through the specified dates of 1/1/2019 to 4/29/2019:
  * All three communities seemed to peak in fares toward the end of Februaury.
  * Urban rates still remain the highest fare but tends to fluctuate during the spring season.
  * Rural areas stay fairly consistant throughout this timeframe with very little dramatic increase or decline.

![PyBer_fare_summary](https://user-images.githubusercontent.com/118647523/212168005-17d369f4-fe5a-4a5a-aba2-93f550707f2f.png)

## Summary 
### - Analyze and view a larger time window for the entire year to adjust fare pricing during peak and low ride totals. This would increase profit for all the total fares during busy fluctuation for all urban, suburban, and rural areas.
### - The suburban areas have good amount of drivers so lowering the average fare per ride in this areas could attract more rides in total but doing so could cause average fare per driver to slightly decrease.
### The rural areas have more drivers total than total rides all together. Adjusting average fare per driver in rural areas could help bring down a more affordable cost for the average fare per ride which might help increase more rides for the total amount of drivers



