---
layout: magazine
title:  "Magazine"
date:   2024-03-19 09:38:49 +0100
categories: jekyll update
---
# Introduction to the dataset
The SF Crime Data captures reported incidents of crime within the city of San Francisco over several years. It includes details such as the type of crime, the district in which it occurred, the date and time of the incident, and the latitude and longitude coordinates of the crime scene. This dataset provides a rich source for understanding crime patterns, trends, and distributions across different parts of the city over time.

# Vizualisations
### Time series/bar-chart


<img src="/images/new_bar.png" alt="Description of Image" style="display:block; margin-left:auto; margin-right:auto; width:1000px; height:auto;">


*Figure 1: Total Crimes Reported by Hour in San Francisco. The graph highlights the peak times for criminal activity throughout the day.*

Figure 1 presents a clear depiction of the rhythm of crime in San Francisco as it ebbs and flows throughout the day. The lowest number of crimes is reported in the early morning hours around 4 am, which could be attributed to the city's downtime. As the city awakens, there's a noticeable increase in reported incidents, peaking at noon and remaining high until the late evening. This could reflect the increased activity as residents go about their daily routines, including work and leisure, which presents more opportunities for crimes such as theft and burglary. The evening peak at 6 pm coincides with the end of the workday, after which there is a gradual decline. However, crime rates remain relatively high until midnight, possibly linked to nightlife activities. Understanding these patterns can help law enforcement and community programs better plan their crime prevention strategies to address the specific needs at different times of the day.

### Map

<div style="display: flex;">
  <iframe src="/images/discon_heatmap.html" style="width: 50%; height: 500px; border: none;"></iframe>
  <iframe src="/images/stolen_heatmap.html" style="width: 50%; height: 500px; border: none;"></iframe>
</div>
*Figure 2: Heatmaps for two categories, disorderly conduct (on the left) and stolen property (on the right).*

Heatmaps provide a visual representation of data, where colors indicate the frequency of occurrences — warmer colors denote higher activity levels, while cooler colors suggest fewer incidents. Utilizing data from the San Francisco Police Department, we've created two heatmaps to visualize the patterns of disorderly conduct and stolen property crimes throughout the day. This analysis is interesting because it sheds light on two different categories that might require two types of specialized police officers. This could help the police department to organize how many of which type of specialized police officers should be available in each area at which hour.


### Interactive