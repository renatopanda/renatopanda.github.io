---
layout: page
permalink: /teaching/
title: teaching
description: A brief list of courses I have taught since 2010/2011, mostly at IPT (BSc and MSc in Informatics Engineering as well as the BSc in Electrical and Computer Engineering.
nav: true
---

<div class="publications">

{% assign grouped_courses = site.teaching | group_by: "last_year" | sort: "name" | reverse %}
{% for course_year in grouped_courses %}
  
  {% assign year_courses_sorted = course_year.items | sort: "importance" %}
  {% for course in year_courses_sorted %}

    <h2 class="year">
    {% if course.first_year != course.last_year %} {{ course.first_year }}-{% endif %}{{ course.last_year }} ({{ course.times }}x)</h2>
    <div class="row">
      <div class="col-sm-2 abbr">
        <a href="{{ course.course_url }}" title="{{ course.course_full }}" class="badge {{course.course_color}}">{{ course.course }}</a>
      </div>
      <div class="col-sm-8">
        <div><b>{{ course.title }} ({{ course.level }})</b></div>
        <div>
          <em>{{course.role}}</em>
        </div>
        <div>
          <b>Topics:</b> {{ course.topics }}
        </div>
      </div>
    </div>
  {% endfor %}
    
{% endfor %}

</div>