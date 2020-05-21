---
title: "New Tool Release - the Household Travel Survey Data Explorer app"
author: Christy Lam
image: /images/2020/HHTS_exploration_app.png
image-wide:
comments: true
layout: post
tags: [tools]

---

We have some exciting news to share! PSRC has just released Version 1.0 of the **Household Travel Survey Data Explorer app**. 

Almost a year ago, we held a soft launch of the Beta version that allowed users to explore summary results from the 2017 Regional Household Travel Survey. Since the Beta release, we have been working on improving the details of the graphical user interface, integrating the app with new data from the 2019 survey, and optimizing the app's performance upon loading. 

It was an "achievement unlocked" moment when the app initially deployed as **one of our goals was to make survey results easily accessible and efficiently sharable**. A tool to crunch the numbers that would allow us to explore more easily what the survey contains and derive data-driven stories are other factors towards pursuing this project.

To make it possible, we developed (and are still developing) our technical prowess by learning *R* to harness its data wrangling and visualization capabilities. The app was written in *R*, powered by *Shiny* and other libraries such as *data.table* , *ggplot2*, *DT*, and *Plotly* for *R* to name a few. The process also involved designing a database schema to house iterations of the household survey and have the app read-in data from our *SQL server* data warehouse.


We're continuing to fine-tune the app by addressing/resolving bugs and conceptualizing new features. All the while, we are continually quality checking results to make for a better tool and user experience. Overtime you may see some changes as we build up to the 2021 survey. 


In the meantime, **Version 1.0** of the app reflects the combined 2017 and 2019 Regional Household Travel Survey data. Generating data summaries of general statistics (shares and total estimates, sample counts, margin of errors) across 90-plus aspects (and cross-tabulation of aspects) is only a couple clicks away.


Happy exploring!

[http://dataexplorer.psrc.org/household-travel-survey/](http://dataexplorer.psrc.org/household-travel-survey/)
 



