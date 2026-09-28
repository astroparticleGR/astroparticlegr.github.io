---
title: Projects
nav:
  order: 2
  tooltip: Software, datasets, and more
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

From deep learning algorithms that reconstruct particle properties and identify rare signals in real time to open-source tools that make raw detector data AI-ready, our projects turn physics data into results - with applications reaching beyond neutrino physics into imaging and sensing.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
