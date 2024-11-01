---
title: "Shiny Data Visualization for Urban Planning"
date: 2024-10-31
author: "Suzanne Childress"
image: /images/2024/suzannes-laptop.jpg
image-wide: /images/2024/suzannes-laptop.jpg
comments: yes
layout: post
editor_options:
  markdown:
    wrap: 100

images:
   image1:
      image: /images/2024/hackathon.jpg
      caption: "Christy Lam, Brandon Wong, and Joanne Li participated in Seattle's Open Data Hackathon."
   image2:
      image: /images/2024/summer-planning-academy.jpg
      caption: "High school students used a shiny app we developed to learn about urban planning. You can see images they took from the app in the presentation behind the students."
   image3:
      image: /images/2024/suzannes-laptop.jpg
      caption: "My laptop has stickers for libraries we use in our Shiny apps frequently, and other things I like such as women mathematicians, GitHub collaboration, and women hugging trees."
   image4:
      image: /images/2024/work_hispanic.png
      caption: "The shiny apps are created to eludicate the complex interactions between demography, economy, land use and transportation."
   image5:
      image: /images/2024/livinthedream.png
      caption: "We also developed an R library to easily create nicely formatted charts so we can quickly go from numbers to meaningful data visualization without mucking around with getting the colors, fonts, and other layout parameters set by hand. Here you can see some of the color scales from the library."
   image6:
      image: /images/2024/vmt.png
      caption: "Household travel survey results showing that workers who work at home drive fewer miles. The app will show this data eventually. For now, I just want this data out because it's important to policies being enacted today!"
   image7:
      image: /images/2024/hackathonwinner.png      
      caption: "A screenshot of the app we developed to show Census Transportation Planning Package data in regional centers."
       
     
---
#### Why do we use Shiny to visualize urban planning data?


Over the past several years, the PSRC data science team has deployed several [Shiny apps](https://shiny.posit.co/) that create interactive web data visualizations to inform regional urban planning.

{% include image.html image=page.images.image4 %}

We recommend other urban planning data experts who program in python and R like us check out Shiny as option. 
Our team uses many other data visualization software packages such as Tableau, Infogram, ArcGIS Story Maps, and yes, Excel.
Shiny stands out because it allows for an ***open source*** clean integration of code along a data pipeline from engineering, to statistics, and into a final product, without a ton of web programming expertise.
All of our code and data to create the apps is open!! See the our [shiny app code here on Github](https://github.com/psrc).

{% include image.html image=page.images.image5 %}


We host our Shiny apps on [shiny.apps.io](https://www.shinyapps.io/) so we don't have worry about server details. Shiny.apps.io has free hosting service, but we pay about $500 a year to get more features like unlimited apps and performance. We've got about 20 apps up there!

We've been developing our coding and Shiny chops on the urban planning data team for about the past ten years, so using Shiny wasn't an overnight solution. As an example of the continous skill-building our team does, this year several team members attended the [Posit Conference](https://posit.co/conference/) to increase our Shiny and other programming skills in python and R. (Posit is the company that develops Shiny.) 

Shiny apps work well for our situation that we have statisticians, GIS experts, and data analysts with a little coding skill who want to push our data into an open venue. If you're a real web developer with skills in javascript and css, Shiny also might not be the thing for you.

## Top Seven PSRC Shiny apps
#### Click on the links to see the apps live. 

<ol>
  <li>
    <a href="https://psrcwa.shinyapps.io/rtp-dashboard/">Regional Transportation Plan Dashboard</a>
    <br>

    The regional transportation plan dashboard is my favorite Shiny app because it integrates with a top planning process at PSRC. Historically, the regional transportation plan has been a hundreds of pages long PDF.
    The Shiny app brings the transportation plan to life with relevant, easily understandable data in a visually appealing framework. We toiled away to make the graphics match our website and have a modern design.

  </li>
  <br>

  <li>
    <a href="https://psrcwa.shinyapps.io/seattle-hackathon/">Seattle Open Data Hackathon Housing Permit App</a>
    
    {% include image.html image=page.images.image1 %}

    Last year several data team members participated in the <a href="https://innovation-hub.seattle.gov/2023/11/20/join-us-one-seattle-data-hackathon/">City of Seattle's open data hackathon</a>.
    The team developed an app that shows time to complete housing permitting processes in Seattle's Racial Social Equity areas. We got second place! I like this app because it shows how teamwork makes the data science dream work.
  
  </li>
  <br>
  <li>
    <a href="https://psrcwa.shinyapps.io/travel-survey-explorer/">Household Travel Survey Explorer</a>
    {% include image.html image=page.images.image6 %}
    
    The household travel survey explorer creates data summarizations from our rich dataset of household's daily activities. The app summaries show the diversity of travel behavior by different demographic and geographic characteristics.
    <a href="https://www.psrc.org/our-work/household-travel-survey-program">Learn more about the survey program</a>.
  </li>
  <br>
  <li>
    <a href="https://psrcwa.shinyapps.io/community-profiles/">Community Profiles</a>
    <br>
    The community profiles app allows local jurisdictional planners to quickly access key Census and American Community Survey data from their area. Census data underlies much of the work we do as planners, but it can be inaccessible at times, and this app puts the important information at planner's fingertips.

  </li>
 <br>
  <li>
    <a href="https://psrcwa.shinyapps.io/planning-academy-centers-2024/">Summer Planning Academy Toolbox</a>
    {% include image.html image=page.images.image2 %}

    The <a href="https://www.psrc.org/get-involved/summer-planning-academy">summer planning academy at PSRC</a> introduced high school students underrepresented in urban planning to our work. The Shiny app we developed packaged together maps and data to help the students create a capstone project. We were wowed to see what they were able to do with easy access to the data provided in the app. They learned a ton about planning data!
    
  </li>
  <br>

  <li>
    <a href="https://psrcwa.shinyapps.io/centers-monitoring/">Centers Monitoring Dashboard</a>
    
    PSRC's regional centers are areas of the region targeted to add new housing and job density. I like this dashboard because regional centers are a key aspect of PSRC's land use planning paradigm, and the dashboard allows us to track center performance.
  </li>
  
  <br>
  
  <li>
    <a href="https://psrcwa.shinyapps.io/ctpp-explorer/">CTPP Hackathon App</a>
    {% include image.html image=page.images.image7 %}

    The Census Transportation Planning Package(CTPP) is a dataset that allows for a deep understanding of transportation data coming out of the Census. The CTPP team was developing an API, and we helped them test it by developing an app. We won first place in a national competition! The main reason I like this app is: teamwork makes the dream work again, and we helped out the CTPP national development team by testing (we did a public service!)
  </li>
</ol>


#### Hoping to inspire others!

The PSRC data team has reached to integrate programming, statistics, and urban planning to create more modern data products for about ***ten years*** now.



We've learned a ton along the way and we'd love to share. Here's some hard-earned wisdom: 
*  Fully preprocessing data to feed to the app saves valuable user time as opposed to performing analytical calculations in the app
* 90% of app development is graphical formatting -getting things just right. When you get it just right, the response is exponentially higher than just conveying the raw information without nice visuals.
* Bringing an almost fully baked app at least visually (if not functionally) to people before we get feedback is critical- otherwise people don't understand our vision.

Do you want to learn more? Or do you have something you've learned you'd like to share? Please reach out! [email me: Suzanne Childress](mailto:schildress@psrc.org)