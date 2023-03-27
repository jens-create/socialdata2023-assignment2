---
layout: page
title: San Francisco Police Department.
---

## A 5-YEAR PRIORITIZATION PROGRAM 2018-2023


In recent years, San Francisco Police Department (SFPD) has struggled to allocate resources efficiently and adequately for controlling criminal activities in the city. 
To overcome this challenge, the Social Data Dream Team conducted an analysis using criminal data records from SFPD in the period of 2003-2017 to provide insights into typical patterns and the development of crime. The results of the analysis set the foundation for a new prioritization program that will run the coming five years, 2018-2023.

The data set includes 2,084,466 incident records in total, and each incident is characterised by 35 features including date, time, category, location, district, etc. In total the crimes are categorized into 37 categories. 

### Property- & Violence Related Crime
The main focus of this analysis are two critical groups of activities: *property-related* and *violence-related* crimes respectively. Property-related crimes comprise burglary, vehicle theft, arson, larceny/theft, vandalism, trespass and trea. From 2003 until 2018 there has been recorded 812,501 property crimes. Violence-related crimes comprise sex offences (forcible), sex offences (non-forcible), assault and robbery, for which 225,089 records have been registered throughout the same period. 

Below figure shows the historical development of crime frequency of each individual category within the two groups in addition to the overall development of both groups. 

{% include time_series_plot.html %}


During the entire period, a significantly larger frequency of property-related crime has been registered in San Francisco compared to violence-related crime. The most dominating crime activity is *larceny/theft*, which seems to have been rapidly increasing in frequency since 2011. The overall development of property related records seems to be heavily impacted by the development of larceny/theft records, hence SFPD should define a strategy targeting this category in order to combat the overall increasing rate of crime in the dominating property-related crimes.  


### Critical Districts
In previous analyses, Ingleside has mistakenly been perceived as the most problematic district. One reason is that the district has a larger area and thus ..
For this analysis of crime patterns by district, population data has been included in the data set in order to normalize the frequency counts by the size of population for each district. 

Analyzing the crime occurrences relative to the population within each district shows that the critical challenge of larceny/theft is highly dominating in especially the Southern district and also in the adjacent districts; Central, Northern, Tenderloin, Mission and Bayview. As previously observed in the crime development over time, the total property-related records resemble a similar behaviour as to larceny/theft independently, which ... 

{% include map.html %}





### Critical Times 
{% include plot3.html %}
