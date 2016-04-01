---
title: "SoundCast 1.1 Released"
author: Suzanne Childress
image: /images/2016/the-soundcat.jpg
image-wide: 
comments: true
layout: post
tags: [tools]
---

# SoundCast 1.1 is now available on GitHub #

An improved version of SoundCast, PSRC's activity-based travel model, is [now available on GitHub](https://github.com/psrc/soundcast). The main improvements to SoundCast 1.1 from SoundCast 1.0 are:

- Implementation of a [bike assignment module](https://github.com/psrc/soundcast/blob/master/scripts/bikes/bike_model.py)
- Implementation of a [benefit-cost tool](https://github.com/psrc/soundcast/blob/master/scripts/summarize/benefit_cost/benefit_cost.py)
- **Truck model** improvements
- Code clean-up and re-organization
- Run time speed up options implementation

## New Features ##

### Bike Assignment ###
The bike assignment module routes cyclists through the network, based upon research by Broach et al from Portland Metro. The assignment captures cyclists dislike of elevation gains, high traffic volumes and longer distances. It also captures cyclists preference for separated bike facilities.  Using the bike assignment, we can predict volumes on bicycle facilities which may prove useful to help determine good policies and projects for cycling.

The bike trip origins and destinations come from the [Daysim model](http://www.rsginc.com/sites/default/files/publications/20120224%20DaySim%20Model%20Technical%20Documentation.pdf). The Daysim model accounts for how different people prefer biking more than others and how land use impacts bike mode choice.

### Benefit-Cost Tool ###
For several years, PSRC has used a [benefit-cost tool](http://www.psrc.org/data/models/benefit-cost-analysis/) to find the benefits and costs associated with transportation policies.

In this code update, we have implemented the benefit cost tool that uses our activity-based model outputs, instead of trip-based model outputs.  It includes benefits and costs associated with: 

- auto operating cost and transit fares
- travel time (via value of time)
- parking cost
- vehicle operating and vehicle ownership costs
- air quality costs
- accident costs
- health costs associated with active transport

The new benefit cost tool includes greater disaggregation by geography and different types of people. For example, we can look at measures such as the **average time spent walking for transport for low-income people**.

**Example Benefit Cost Outputs: 2040 Baseline Scenario, Daily Costs**

| Costs by Type            | Total Value               | Value per Person |
|--------------------------|---------------------------|------------------|
| Travel Time              | $105,560,000              | $29.35           |
| Auto Operating and Tolls | $8,590,000                | $2.39            |
| Auto Ownership           | $57,880,000               | $16.09           |
| Transit Fares            | $350,000                  | $0.10            |
| Parking                  | $10,150,000               | $2.82            |
| Health                   | Only Used As a Difference |Between Scenarios |
| Safety                   | $5,380,000                | $1.49            |
| Air Quality              | $2,920,000                | $0.81            |



### Truck Improvements ###
We restricted the truck model to only allow trucks to go to zones that have industrial uses. This restriction corrected a problem in which trucks were destined to illogical zones.  Some re-calibration of trip rates were performed to account for this change and to match counts. External truck trip totals were updated to match recent counts.


## Learning more about our work ##
If you're not familar with GitHub, there's a ton you can learn about our project, just by clicking around. For example, you might be wondering, what type of issues does the PSRC team think they will work on soon?  Upcoming issues we will work on can be seen [here](https://github.com/psrc/soundcast/issues).

Or what if you wonder exactly what changes we made? You can see the [entire history of changes here](https://github.com/psrc/soundcast/commits/master). Or what if you want to see our productivity over time and who have been major contributors? [Check this out!](: https://github.com/psrc/soundcast/commits/master)

 [It definitely looks like we leave early on Fridays.](https://github.com/psrc/soundcast/graphs/punch-card)