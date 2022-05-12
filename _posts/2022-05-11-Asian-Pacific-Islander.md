---
title: The Diversity of Asian and Pacific Islander Experiences
author: "Suzanne Childress"
image: /images/2022/aapi_month_picture.jpg
image-wide: /images/2022/aapi_month_picture.jpg
comments: yes
layout: post
editor_options: 
  markdown: 
    wrap: 72
---

## Across Heritages and Where People Live

The Puget Sound Region has more than 596,000 people who identify as
Asian Alone and more than 35,000 people who identify as Native Hawaiian
and Pacific Islander Alone, as we discovered [last year during Asian
American and Pacific Islander heritage
month](https://www.psrc.org/whats-happening/blog/celebrating-asian-american-and-pacific-islander-heritage-month).
Asian, Native Hawaiian, and Pacific Islander groups represent a wide
variety of [many different
heritages](https://www.psrc.org/whats-happening/blog/region-has-diverse-asian-and-pacific-islander-heritage)
in the region.

***This year we wanted to dive deeper to learn more about the how Asian
and Pacific Islander experiences vary across different groups based on
their heritage and where they live in our region.***

Aggregate Census data can tell one story about people's experiences, but
underneath that lies a wide variety of individual experiences. Broad
data about race and ethnicity can at times hide how different people
really experience the world.

While writing this post, I learned that [Native Hawaiian and Pacific
Islander
people](https://www.seattletimes.com/seattle-news/why-its-time-to-retire-the-term-asian-pacific-islander/)
experience significantly more disadvantages than some Asian groups. For
future analyses, I plan to keep the two groupings separate based on our
findings.

#### How do worker earnings for Asian and Native Hawaiian Pacific Islander people compare to other groups?

Asian Alone workers as an overall group have one of the highest median
personal earnings at \$53,000 annually. On the other hand, Native
Hawaiian and Other Pacific Islander alone workers have some of the
lowest median earnings at \$32,000.

<iframe src="median-worker-annual-earn_broad.html" height="450px" width="100%" style="border:none;">

</iframe>

#### How do worker earnings vary across different groups of Asian, Native Hawaiian, and Pacific Islander people?

Median earnings vary widely across different groups of Asian people.
Burmese, Other Native Pacific Islander, Nepalese, Fijian, Marshallese,
and Hmong workers in the region have median earnings of less than
\$30,000 per year. On the other end of earnings, Asian Indian workers
have median earnings of over \$97,000 per year.

<iframe src="median-worker-annual-earn_detailed.html" height="450px" width="100%" style="border:none;">

</iframe>

detail: RAC2P, PERNP Fields, workers working more than 10 hours per week

**Asian, Native Hawaiian and Pacific Islanders education levels**

Similarly to median earnings, Asian Alone people as a broad group have
some of the highest education levels in the region by race, with 56% of
adults over 25 having obtained a bachelor's degree. Only 11% of Native
Hawaiian and Pacific Islander adults over 25 had obtained a bachelor's
degree.

<iframe src="aapi_education.html" height="600px" width="100%" style="border:none"></iframe></iframe>

Detail: ACS Table C15002D: Educational Attainment by Race (2015-2019)

**How do education levels for Asian and Pacific Islander adults vary
across the region?**

We were interested in looking into how educational levels vary across
the **geographies** of the region. The map below shows that the share of
Asian alone adults over 25 with a Bachelor's degree or higher ranges
vary broadly across the region[[1]](#_ftn1).

Over 60% Asian Alone adults in King County have a bachelor's degree, as
compared to 30% of Asian Alone Adults in Pierce County.

Native Hawaiian and Pacific Islander adults have low levels of education
throughout the region, as around 10% of adults have a bachelor's degree
or higher.

<iframe src="AsianAloneBachelors.html" height="400px" width="100%" style="border:none;"></iframe>

source:ACS Table C15002D: Educational Attainment by Race (2015-2019)

## **Intersecting diverse heritage and geography**

**Where do different groups live in our region? How does where different
people live relate to differing levels of earnings and education for
Asian and Pacific Islander people geographically?**

Different groups of Asian people have settled in different parts of the
region. Those groups experience different levels of earnings and
education, and which is reflected in where the most advantaged and
disadvantaged Asian people live in the region.

The map below shows the top Asian alone group by Census tract in the
region, for those tracts that have more than 200 people in that top
group.

Asian alone people in King County have high earnings and education. The
top Asian groups in King County are Chinese, except Taiwanese,and Asian
Indian people -- the groups with high incomes.

Some of groups with the lowest earnings have big populations in Pierce
County, and hence the median income is lower in Pierce County.

<iframe src="asian_groups_tract.html " height="600px" width="100%" style="border:none;"></iframe>

source: Table B02015 ACS 5-year 2015-2019

The geographic distribution of people's heritages impacts where Asian
people have greater advantages and disadvantages. ***When planning for
racial equity, we must consider the diversity of where people live and
where they come from, and look beneath the surface of regional
medians.*** It is an big challenge on the data side to deal with low
sample sizes, but if we just report broad categories, we lose important
details.

*Technical note: For these analyses, we used an R package we built
called* [psrccensus](https://psrc.github.io/psrccensus/) *that makes
it's really easy to pull ACS, PUMS, and Census data for our region. The
code for this analysis is here:
<https://github.com/psrc/heritage-month/blob/main/aian_2_history_month_region.Rmd>*

------------------------------------------------------------------------

[[1]](#_ftnref1) Because of data availability at a small geographic
level, we had to focus on Asian Alone adults only, and did not have
sufficient data to analyze Native Hawaiian and Pacific Islander adults.
