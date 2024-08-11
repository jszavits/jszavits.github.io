---
permalink: /
title: "Welcome"
---

I am a data scientist at [Oldbaum Services](http://www.oldbaumservices.co.uk/), specializing in Lidar data analysis for wind energy industry. Previously, I worked as a researcher at the University of Edinburgh, first at the School of Physics and Astronomy, and later at the School of Biological Sciences in the research group of [Ramon Grima](https://grimagroup.bio.ed.ac.uk/home). I have a PhD in statistical physics from the University of Zagreb.

## Latest news

{% for post in site.posts limit:5 %}
{{ post.date | date: "%Y-%m-%d" }} {{ post.category }}: [{{ post.title }}]({{ post.url }})
{% endfor %}
