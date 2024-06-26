---
permalink: /
title: "Welcome"
---

I am a biophysicist based in the School of Biological Sciences at the University of Edinburgh, working in the research group of [Ramon Grima](https://grimagroup.bio.ed.ac.uk/home). 

My research focuses on noise in gene expression, how cells cope with it, and what consequences does it have for the regulation of gene expression and ultimately human health.

I have a background in nonequilibrium statistical physics, and an expertise in building and solving kinetic models of transcription and translation. 

I am particularly interested in applying mechanistic models of gene expression to live-cell imaging and sequencing data in order to understand how gene expression is orchestrated and regulated in time. 

## Latest news

{% for post in site.posts limit:5 %}
{{ post.date | date: "%Y-%m-%d" }} {{ post.category }}: [{{ post.title }}]({{ post.url }})
{% endfor %}
