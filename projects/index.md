---
title: Projects
nav:
  order: 2
  tooltip: Research projects, software and resources
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Research projects I lead or take part in, and the bioinformatic tools and genomic resources I have helped develop.

{% include tags.html tags="project, software, resource" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
