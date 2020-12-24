---
layout: page
title: Strate App
description: "<b>HW and SW solution to detect enduro bike crashes</b> | BSc project | 2019/2020 | Supervisor" 
img: /assets/img/strate_hw_v1.jpg
categories: academic
importance: 4
---

The initial idea was proposed by <a href="https://github.com/bettercallcruz" target="_blank">Pedro Cruz</a>, a BSc student which practices Enduro motorcycle sport – create a simple system to detect falls during his Enduro trips and message his emergency contact.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/strate_architecture.jpg' | relative_url }}" alt="" title="System architecture diagram"/>
    </div>
</div>
<div class="caption">
    Architecture of the prototype with the various services communicating through the message broker.
</div>

Although being a bachelor degree project, it started earlier (in September 2019) and exposed the student to a myriad of different concepts:
* Hardware / device creation (3D printed box, ESP32, MPU6050, battery)
* Real-time operating systems programming (FreeRTOS) with parallel tasks accross the available cores
* Mobile app development (React Native Android app that controls the hardware and reads sensors data via Bluetooth)
* Backend development (using Node.JS and MongoDB)
* Introduction to pattern recognition (data analysis, simple decision trees, possibility of exploring simple machine learning concepts)

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/strate_hw_diagram.jpg' | relative_url }}" alt="" title="Hardware diagram"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/strate_app_trip.jpg' | relative_url }}" alt="" title="Android screen for trip details"/>
    </div>
</div>
<div class="caption">
    On the left, the proposed hardware solution. Right, the android app logging data from the current trip.
</div>

The year long project was divided in several mini-projects, from hardware testing, selection and design. Developing the freeRTOS code, Android App, collecting some example datasets, API+frontend and data analysis.

The HW part was one of the major challenges, testing different prototypes and even printing a 3D case.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/strate_hw_v1.jpg' | relative_url }}" alt="" title="Prototype v1 onboard"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/strate_hw_v1_2.jpg' | relative_url }}" alt="" title="Prototype v1 open"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/strate_hw_v2.jpg' | relative_url }}" alt="" title="Final HW prototype"/>
    </div>
</div>
<div class="caption">
    Evolution of the HW prototype, from the first version (tupperware) to the last (printed 3D case).
</div>

Although unfinished, the last part consisted in analysing data from trips and simulated crashes.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/strate_data_analysis.jpg' | relative_url }}" alt="" title="Application diagram"/>
    </div>
</div>
<div class="caption">
    Sensor data analysis and visualization for a short test trip.
</div>