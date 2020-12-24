---
layout: page
title: MER Web Concept
description: "<b>A distributed MER system proof-of-concept using microservices</b> | MSc and BSc projects | 2018/2019 | Supervisor" 
img: /assets/img/DockerMER_concept.jpg
youtubeId: m4ySmVLXkMw
categories: academic
importance: 4
---

The aim of the project was to study and implement a robust, distributed MER proof-of-concept system that could be expanded with novel algorithms in the future. The work was focused on software engineering, exploring the usage of microservices implemented with simple containers and message queues. The MER components were simple, serving as proof of concept: YouTube was used as the source of songs, while the Essentia framework and Support Vector Machines were used to feature extraction and machine learning respectively.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/dockerMER_architecture.jpg' | relative_url }}" alt="" title="System architecture diagram"/>
    </div>
</div>
<div class="caption">
    Architecture of the prototype with the various services communicating through the message broker.
</div>


The MER systems were developed by Ricardo António (<a href="http://hdl.handle.net/10400.26/31444" target="_blank">MSc project</a>), while the React frontend and API were part of the BSc final project of <a href="https://github.com/Tiago622" target="_blank">Tiago António</a> and <a href="https://github.com/tiagoareias" target="_blank">Tiago Areias</a> at Polytechnic Institute of Tomar.

{% include youtubePlayer.html id=page.youtubeId %}

<div class="caption">
    A simple demo of the system classifying 3 youtube videos.
</div>

A more complex and robust version (v2) is being built based on the knowledge gathered from this project.
