---
layout: page
title: press
permalink: /press/
description: Press releases and interviews featuring research activity i was or am involved with.
nav: true
---

<div class="projects grid">

  {% assign sorted_projects = site.press | sort: "date" | reverse %}
  {% for project in sorted_projects %}
  <div class="grid-item">
    {% if project.redirect %}
    <a href="{{ project.redirect }}" target="_blank">
    {% else %}
    <a href="{{ project.url | relative_url }}">
    {% endif %}
      <div class="card hoverable">
        {% if project.img %}
        <img src="{{ project.img | relative_url }}" alt="project thumbnail">
        {% endif %}
        <div class="card-body">
          <h2 class="card-title text-lowercase">{{ project.title }}</h2>
          <p class="card-text">{{ project.description }}</p>
          <p class="card-text text-right">{{ project.date | date_to_long_string }}</p>
        </div>
      </div>
    </a>
  </div>
{% endfor %}

</div>
