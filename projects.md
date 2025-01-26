---
layout: page
title: Projects
permalink: /projects/
---

<h1>My Projects</h1>

<ul>
  {% for project in site.projects %}
    <li>
      <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
      <p>{{ project.description }}</p>
    </li>
  {% endfor %}
</ul>
