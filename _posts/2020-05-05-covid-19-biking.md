---
title: "How many people are biking during COVID-19 in Seattle?"
author: Polina Butrina
image: /images/2020/bike_sky.png
image-wide:
comments: true
layout: post
tags: [tools]

images:
   image1:
      image: /images/2020/2nd-ave-moving-average.jpeg
   image2:
      image: /images/2020/burke-and-elliot-moving-average.jpeg
   image3:
      image: /images/2020/travel-apr-2019-time.jpeg
   image4:
      image: /images/2020/travel-apr-2020-time.jpeg
---
------THIS POST IS WORK IN PROGRESS------

In the past couple of months, governments around the world implemented social distancing measures to slow the spread of COVID-19. During this unique time, we would like to understand how people's travel behavior is changing.
The first data point we wanted to analyze was the number of people bicycling for a couple of reasons: 


 * The data is publicly available on the Seattle DOT website (link here);

 * Usually, May is the Bike Everywhere Challenge month in the PSRC region and Washington State (not this year, but we are hoping to participate next year) 

 * Biking is one of the popular modes of getting to and within Seattle downtown .


Here are the questions we explored :

*1.	Have numbers of people biking and walking decreased in March 2020 comparing to previous months/years?*

*2.	Was there a decrease in biking after Work from Home or stay-at-pace orders?*

*3.	How has the people's behavior has changed?*


## Data


Seattle DOT has 12 bike counters providing bicycle and pedestrian counts on multi-use trails, streets, and greenways. The counts are available starting February 2014 to present, and most counts are updated once a month. Some of the trails don't have March 2020 counts, hence in our analysis we wanted to focus on the trails that have March 2020 counts, including:


*	Fremont Bridge 
*	Spokane Street Bridge
*	2nd Avenue at Marion
*	2nd Avenue at Cedar
*	BurkeGilman Trail north of NE 70th St Bike and Ped Counter
*	W 58th St Greenway at 22nd Ave NW Bike Counter
*	Elliott Bay Trail in Myrtle Edwards Park Bike Count
*	7th Avenue and Blanchard
*	Westlake Ave at Newton
*	26th Avenue Greenway

## Analysis


*1.	Have numbers of people biking and walking decreased in March 2020 comparing to previous months/years?*

To understand if the number of people biking changed, we've calculated a percentage change of bicycle counts in March and April (2019 vs 2020).

|    Trail Name            |    March 2019 vs 2020 Delta, %    |    April 2019 vs 2020 Delta, %    |
|--------------------------|-----------------------------------|-----------------------------------|
|    Burke Gilman          |    -5.0                           |    65.5                           |
|    Elliot Bay            |    -21.8                          |    20.4                           |
|    26th Ave Greenway     |    -24.4                          |    No data available              |
|    NW 58th Greenway      |    -30.9                          |    No data available              |
|    Fremont Bridge        |    -32.3                          |    -25.7                          |
|    Spokane Bridge        |    -33.2                          |    -2.1                           |
|    2nd Ave and Cedar     |    -46.4                          |    No data available              |
|    2nd Ave and Marion    |    -50.2                          |    No data available              |
*Note: the counter at 7th Avenue and Blanchard was not included because the counter started collecting data in August 2019. Westlake and Newton counter was also excluded because of data quality.*

The bicycle counts declined on all trails/streets in March 2020 when compared to March 2019 with some areas like Seattle Downtown and Belltown having a steeper decline (2nd Avenue and Marion and 2nd Avenue and Cedar) and some trails have a more shallow decline (Burke Gilman and Elliot Bay trails). In April, there is a different picture where Burke Gilman and Elliot Bay trails saw growth in bicycle counts when comparing to April 2019.

*2.	Was there a decrease in biking after Work from Home or stay-at-pace orders?*

On March 4th, the King County officials gave the recommendation to work from home to the companies, and government agencies and tech firms advised their employees to work from home. Stay-at-home order was placed by the Washington State on March 23rd.
The next two figures show February-March 2020 bicycle counts for two different types counter locations: Downtown/Belltown (2nd Ave and Marion St; 2nd Ave and Cedar St) and trails (Burke Gilman and Elliot Bay trails). These four counters will represent commute biking routes and recreational routes respectively. 


{% include image.html image=page.images.image1 =250x %}



Bicycle counts in Downtown/Belltown started decreasing at the start of March, right after Washington State and King County's work from home recommendation. The downward trend continued after the Stay-at-Home order. The bicycle count decline along commute-heavy routes was expected and not surprising. 


{% include image.html image=page.images.image2 %}


The Burke Gilman and Elliot Bey trails didn't see such a steep decline in bicycle counts. Moreover, the highest bicycle counts occurred after the work from home recommendations and stay at home order. 
An interesting shift occurred in bike counts between the Burke Gilman and the Elliot Bay trails. In February 2020, bike volumes were higher on the Elliot Bay trail than on the Burke Gilman. Generally, bike counts on Elliot Bay trail were higher during weekdays vs weekend - this suggests that this trail was mostly used for commuting in February 2020. In the middle of March 2020, Burke Gilman trail saw bike counts growth that exceeded bike count on Elliot Bay trail.

