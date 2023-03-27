---
layout: page
title: San Francisco Police Department.
---

**A 5-YEAR PRIORITIZATION PROGRAM 2018-2023**

In recent years, San Francisco Police Department (SFPD) has struggled to allocate ressources efficiently and adequately for controlling criminal activities in the city. 
To overcome this challenge, the Social Data Dream Team conducted an analysis using criminal data records from SFPD in the period of 2003-2017 to provide insights into typical patterns and the development of crime. The results of the analysis set the foundation for a new prioritization program that will run the coming five years, 2018-2023.

The data set includes 2,084,466 incident records in total, and each incident is characterised by 35 features including date, time, category, location, district, etc. In total the crimes are categorized into 37 categories. The main focus of this analysis are two crtitcal groups of activities: *property-related* and *violence-related* crimes respectively. Property-releted crimes comprise burglary, vehicle theft, arson, larceny/theft, vandalism, tresspass and trea, whereas voilence-related crimes comprise sex offences (forcible), sex offences (non-forcible), assault and robbery.


Below figure shows the historical development of crime frequency of each individual category within the two groups in addition to the overall development of both groups. 

{% include time_series_plot.html %}


During the entire period, a significantly larger frequency of property-related crime has been registered in San Francisco compared to violence-related crime. The most dominating crime activity is *larceny/theft*, which seems to have been rapidly increasing in frequency since 2011. The overall development of property related records seems to be heavily impacted by the development of larceny/theft records,hence SFPD should define a strategy targeting this category in order to combat the overall increasing rate of crime in the dominating property-related crimes.  


In [AREA] theft is critical challenge.



In previous analyses, Ingleside has mistakenly been perceived as the most problematic district. The reason for this is that.... 
For this analysis the crime frequencies have been normalized by the poppulation of the corresponding district. 


{% include map.html %}


Markdown is supported:
## Embed python

```python
2+2
```

Include a html plot (bokeh)

Add the file.html in the _includes folder. In the test.html file we have to remove the first line: <!DOCTYPE html>, otherwise it will be displayed.

{% include plot3.html %}
