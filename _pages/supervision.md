---
layout: archive
title: "Student Supervision"
permalink: /supervision/
author_profile: true
---

{% include base_path %}

I have had the privilege of supervising students at various career stages, from MSc projects to PhD dissertations and postdoctoral research. My supervision focuses on combining traditional taxonomic and ecological approaches with cutting-edge molecular and computational methods.

## Postdoctoral Researchers

{% assign postdocs = site.supervision | where: "category", "postdoc" | sort: "year" | reverse %}
{% for post in postdocs %}
  {% include archive-single.html %}
{% endfor %}

## PhD Students

{% assign phds = site.supervision | where: "category", "phd" | sort: "year" | reverse %}
{% for post in phds %}
  {% include archive-single.html %}
{% endfor %}

## MSc Students

{% assign mscs = site.supervision | where: "category", "msc" | sort: "year" | reverse %}
{% for post in mscs %}
  {% include archive-single.html %}
{% endfor %}

---

**Research Areas:** My supervision covers diverse topics including molecular systematics, digital natural history, computer vision applications, freshwater ecology, climate change biology, and taxonomic research. I particularly encourage interdisciplinary approaches that combine traditional biological expertise with modern computational and molecular methods.
