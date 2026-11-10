---
layout: page
title: Projects
permalink: /projects/
description: Research topics of the lab.
nav: false
nav_order: 2
published: false # hidden for now. Remove this line and set nav to true to show the tab.
---

<div class="projects">
  {% assign sorted_projects = site.projects | sort: "importance" %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
</div>
