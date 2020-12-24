---
layout: page
title: Synology NAS Beeper
description: "<b>Disable / enable the beeper sound from a USB connected UPS in Synology DiskStation Manager</b> | 2019" 
img: 
github: https://github.com/renatopanda/synology-nas-beeper
categories: personal
importance: 4
---

Based on [this post](https://moshib.in/2019/02/08/disable-ups-beeper-synology.html) from [Moshi's Blog](https://moshib.in).

Some time ago the power went off at 4am for a long time and I had to get up and shutdown the UPS in order to stop the beeping. The abovementioned post describes how to disable it permanently. Still, I did not want it to stop beeping during day time. The next steps and scripts are my solution to disable and enable the beeping during specific parts of the day (in my case between 00h and 09h).

{% if page.github %}
<a href="{{ page.github }}" target="_blank"><i class="fab fa-github gh-icon"></i> Code Repository</a>
{% endif %}