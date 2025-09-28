---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

My research projects span diverse areas including molecular systematics, digital natural history, computer vision applications, freshwater ecology, and taxonomic research. I particularly focus on interdisciplinary approaches that combine traditional biological expertise with modern computational and molecular methods.

## Current Research Projects

{% assign current_projects = site.projects | where: "status", "ongoing" | where: "category", "research" | sort: "year" | reverse %}
{% for post in current_projects %}
  {% include archive-single.html %}
{% endfor %}

## Software & Computational Projects

{% assign software_projects = site.projects | where: "category", "software" | sort: "year" | reverse %}
{% for post in software_projects %}
  {% include archive-single.html %}
{% endfor %}

## Collaborative Projects

{% assign collab_projects = site.projects | where: "category", "collaboration" | sort: "year" | reverse %}
{% for post in collab_projects %}
  {% include archive-single.html %}
{% endfor %}

## Completed Projects

{% assign completed_projects = site.projects | where: "status", "completed" | sort: "year" | reverse %}
{% for post in completed_projects %}
  {% include archive-single.html %}
{% endfor %}

---

**Research Focus Areas:** My projects integrate traditional taxonomic and ecological approaches with cutting-edge molecular and computational methods. Key areas include biodiversity informatics, machine learning applications in biology, phylogenetic analysis, ecosystem assessment, and digital natural history collections.
