---
layout: default
title: Archive
---

### _I/O BLOG ARCHIVE_

{% assign years = "2023|2022|2021|2020|2019|2018|2017|2016|2015|2014" | split: "|" %}
{% capture strnowyear %}{{'now' | date: '%Y'}}{% endcapture %}
{% assign nowyear = strnowyear | plus: 0 %}

{% for stryear in years %}
   {% assign year = stryear | plus: 0 %}
   {% if year <= nowyear %}
<br/>

<p class="sidebar_title"> {{year}}</p>

{% for post in site.posts %}
{% capture postyear %} {{post.date | date: '%Y'}}{% endcapture %}
{% if postyear contains stryear %}
**[ {{ post.title }} ]({{ post.url }})**
<br/>
_&nbsp;&nbsp;&nbsp;&raquo; by {{ post.author }} on {{ post.date | date_to_string }}_

{% endif %}
{% endfor %}

{% endif %}
{% endfor %}

