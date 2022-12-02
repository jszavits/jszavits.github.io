---
permalink: /
title: Welcome
---

I am a biophysicist based in the School of Biological Sciences at the University of Edinburgh, working in the research group of [Ramon Grima](https://grimagroup.bio.ed.ac.uk/home). 

My research focuses on noise in gene expression, where does it come from, how cells cope with it, and what consequences does it have for the regulation of gene expression and ultimately human health.

I have a background in nonequilibrium statistical physics, and an expertise in building and solving kinetic models of transcription and translation. 

I am especially interested in using kinetic modelling to infer the dynamics of gene expression from live-cell imaging and sequencing data.

## News

{% for post in site.posts limit:3 %}
{{ post.date | date: "%m-%d-%Y" }} {{ post.title }}
{% endfor %}
