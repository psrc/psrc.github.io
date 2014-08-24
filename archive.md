---
layout: default
title: Archive
---

### I/O Blog Archive

{% assign years = "2020|2019|2018|2017|2016|2015|2014" | split: "|" %}
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
* {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})
         {% endif %}
      {% endfor %}
    {% endif %}
{% endfor %}
