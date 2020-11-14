# Analysis of Domestic Flight Delays
## by Manuel Mane


## Dataset

The data consist of 285159 observations per month, year, carrier, and airports of arrival domestic flights. This data is provided by the  U.S. Department of Transportation's (DOS) Bureay of Transportation Statistics of the United States Department of Transportation. It covers the timeline from June 2003 to July 2020, described by month. The data can be found in the [Bureau of Transportation Statistics website](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp)

## Summary of Findings

In the exploration I found that all of the delays variable have a right skewed distribution because of the huge outliers in some of the delay observations during the timeline of the recording of the data. After applying logarithm scale they obtained a somehow normal distribution with some peaks between the 100 and 1000 values but almost unseen. 

I also could notice that there were some carrier/airlines and airports with higher representation than others in the data which could affect when summarizing the variables for each of them, taking into consideration all of them with the same criteria could bias my analysis. Because of this, in the latest parts of my analysis I took into consideration the variables with higher representation in order to reduce this bias and be able to find valuable insights in the relationship of the different delays with the carrier and time of the year.

Some of the most important findings were to realize that some of the most common (top 3) airlines were not the ones with higher delays. This is probably because of a better service or infrastructure of the company. In other parts, where some airlines advantaged in delays by weather condition, other had higher values of delays because of late aircraft. Unsurprinsingly Las Vegas and Los Angeles had the airports with higher delays, mostly due the high traffic of flights on these airports. 

I also could notice how 2020 was by far the year with less delays, not because the service improve considerably from 2019 (which had high index of delays) but because of the current pandemic situation that had put on stop many flight plans.
 
## Key Insights for Presentation

For the presentation I focus on the effect of the different delays variables on the airport and different airlines, making a comparation among months. The goal is to stablish an idea of what airlines offer more security regarding to puntuality in the schedule of their flights. 

First, I introduce the main variable focus which is the time of delay of arrival, and afterwards I show the correlation of the time on cancelled flights and amount of flights. I extract the top 10 airlines with more delays and I make a comparison with the variation of time delay of the airlines among the months. Lastly I include the city that experience the most delays.
