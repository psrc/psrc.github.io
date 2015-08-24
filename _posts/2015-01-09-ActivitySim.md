---
title: Building an Open Source Software Platform for Travel Analysis
author: Elizabeth Sall
image: /images/2015/activitysim-github.png
comments: true
layout: post
tags: [tools, visualization]

images:
   image1:
      image: /images/2015/activitysim-github.png
      caption: "All of the code is available in an online, version-controlled environment hosted on GitHub"
      source: "[ActivitySim Github Repository](http://github.com/synthicity/activitysim)"
   image2:
      image: /images/2015/activitysim-roadmap.png
      caption: "The project wiki outlines a development roadmap, governance, and software architecture"
      source: "[ActivitySim Github Repository](http://github.com/synthicity/activitysim/wiki/Roadmap)"
   image3:
      image: /images/2015/activitysim-issues.png
      caption: "See what issues we are currently working on and the questions and discussion that they bring up"
      source: "[ActivitySim Github Repository](http://github.com/synthicity/activitysim/issues)"

---

PSRC is working with agencies in [Atlanta](http://www.atlantaregional.com), [San Diego](http://www.sandag.org), [San Francisco](http://www.sfcta.org), and the whole [Bay Area](http://mtc.ca.gov) to develop an open-source platform for travel demand modeling, analysis, and forecasting.

### Don't you already have software for this?

Why do you need more software - don't you already have a bunch?

It is true that there are a multitude of both commercially-available and open-source software alternatives for travel modeling and we are not just interested in recreating wheels.

However, most of the commercially-available products are not currently optimized to take advantage of what is called [Activity-Based Travel Modeling](http://tfresource.org/Activity-Based_Models), which is better poised than traditional [trip-based models](http://tfresource.org/Trip_Based_Models) to capture the complex behavior that takes place in metropolitan areas where people don't just travel back and forth from work in their car every day at 8:00AM and 5:00PM. 

Currently each urban area with an Activity-Based Travel Model (including PSRC's [SoundCast](http://www.psrc.org/data/models/abmodel/)) has developed their own custom software that has been descended from the early 2000s (read: many vestigal parts).  

Over the past decade, several consulting firms have developed specialties in various Activity Model "flavors" and have taken it upon themselves to invest in refactoring the code to run more efficiently (SoundCast's current flavor is called "DaySim") and on more modern programming languages such as Java and c# (as opposed to c++).  While these efforts are appreciated, it leaves the industry with several inefficiencies:

 * difficulties in porting improvements made by agency A to agency B, which results in a lot of the same improvements being programmed dozens of times
 * significant learning curves for staff and consultants: each model at each agency is it's own bag of tricks to learn
 * unsustainable business model for consultants who have taken up the burden of keeping the basic background code up to date
 * inability (or overly-burdensome) to compare data and utilities across regions and agencies 
 * making it truly open-source and owned by the community takes away pride and competitiveness issues and makes it easy for anybody to contribute
 * more heads are better. It has been incredibly rewarding and useful to hear different perspectives from different agencies about how to approach a problem.
 * user-driven process.  If we break it, we own it.  This weeds out pie in the sky features that don't help us do our job better on a daily basis.

### Can I see what is going on?

We're so glad you asked!  Open-ness is an important component to getting the best ideas in the pot and gaining trust with both the professional community and the public at large.

Therefore, we are happy to let you know that *the entire process (not just the computer code) is [available online](http://github.com/synthicity/activitysim) for you to look at in real time.*

### So what will it do?

Perhaps the best way of saying what it does, is by starting with what it *wont do*, which is be a plug and play crystal ball into the future.

A good analogy is that it is software that enables you to easily build the analysis tool.  A word processor doesn't write your report for you and a spreadsheet doesn't do your accounting for you, but they give you a decent set of tools to make it easy: formatting, spell-check, built-in statistical formulas, etc.

So what tools and abstractions do you need built in for travel modeling?  There are quite a few and it varies across agencies, however some standards are:
 * [Discrete Choice Modeling](http://tfresource.org/Choice_models)
 * [Skim Matrices](http://tfresource.org/Skim_Matrix)
 * Auto Ownership and other mobility models (i.e. transit pass ownership)
 * Location Choice (i.e. usual workplace destination choice)
 * [Mode Choice](http://tfresource.org/Mode_Choice)
 * [Accessibility Variables](http://tfresource.org/Accessibilities)
 * Person- and Household- based simulation of all these choices

We should also clarify that the current intent of ActivitySim is to provide tools for the *demand* as opposed to *travel supply* side of travel analysis.

That is to say that this took needs to be paired with appropriate [network assignment](http://tfresource.org/Network_Assignment) models.  Furthermore, ActivitySim is not currently scoped to simulate the demand associated with [Goods Movement](http://tfresource.org/Freight_modeling) or Commercial Vehicles.

### Who decides what gets done? 

Isn't it confusing with so many people directing traffic?

Luckily, the five agency partners have a fairly overlapping vision for this thing and were able to develop a singular scope of work for a consultant.  The five agencies and the consultant collaboratively developed and refined a [roadmap using a wiki](https://github.com/synthicity/activitysim/wiki/Roadmap).  

{% include image.html image=page.images.image2 %}

From there, the consultant created a series of open issues via the interface on GitHub where we discuss various implementation details.

{% include image.html image=page.images.image3 %}

If we don't agree at the end of the day...that's where the voting comes into play, which is all outlines
in legalese in documents that we have made available to everybody [online](http://github.com/synthicity/activitysim/wiki/Governance). 


### I have opinions - how can I participate?

Stellar!  Assuming your opinions are constructive, we welcome them.  Here are a few ways to participate:

**Discuss open issues**
Log in and comment on our current set of [unresolved issues](https://github.com/synthicity/activitysim/issues).  
To do this, you will need a free [GitHub Account](http://github.com/join), then you can click on issues that you might be interested and (respectfully) chime in on the conversation.

**Tell us what you think**
If you have an opinion about the [overall process](http://github.com/synthicity/activitysim/wiki/Roadmap) or things that you think we should consider - let us know in the comments!

**Download and test the code**
It is a bit premature to actually test the code at the time of this posting, because it doesn't do much...yet.  

...and it has a ton of undocumented dependencies.

But for the intrepid, feel free to clone or fork the repository now: `https://github.com/synthicity/activitysim.git`

{% include image.html image=page.images.image1 %}

Hopefully in the next few months we will put up a users guide to make this process more seamless.

