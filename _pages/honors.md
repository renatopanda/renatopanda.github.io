---
layout: page
permalink: /honors/
title: honors
description: List of honors and awards I have received over the years.
nav: true
---

<div class="publications">

  {% assign honors_sorted = site.honors | sort: "year" | reverse %}

  {% for honor in honors_sorted %}

    <h2 class="year">{{ honor.year }}</h2>
    <div class="row">
      <div class="col-sm-2 abbr">
        <span class="badge badge-success">{{ honor.badge }}</span>
      </div>
      <div class="col-sm-8">
        <div>
          <b>{{ honor.title }}</b>
          {% if honor.website != blank %}
            (<a href="{{ honor.website }}">link</a>)
          {% endif %}
        </div>
        <div>{{ honor.description }}</div>
      </div>
    </div>

  {% endfor %}
    
</div>