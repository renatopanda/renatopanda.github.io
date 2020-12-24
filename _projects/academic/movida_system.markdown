---
layout: page
title: MOVIDA System
description: "<b>Physical activity tracking with a strong CI/CD component</b> | BSc project | 2018/2019 | Supervisor" 
img: /assets/img/movida_web.jpg
categories: academic
importance: 4
---
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/movida_web.jpg' | relative_url }}" alt="" title="MOVIDA Web App"/>
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/movida_app.jpg' | relative_url }}" alt="" title="MOVIDA Android App"/>
    </div>
</div>
<div class="caption">
    On the left, data visualization (web app). Right, the mobile app main screen.
</div>

This work was related with the MOVIDA research project (where I did not participate). Near the project conclusion, I was asked to project a new version of the system, consisting of a mobile application (Android and iPhone - React Native) to track physical activity, frontend (React) and API (Node.JS/Express). To this end, two BSc students (<a href="https://github.com/hug0Hq" target="_blank">Hugo Costa</a> and <a href="https://github.com/aluno19426" target="_blank">Diogo Martins</a> developed a solution using project and added a strong DevOps component, with automated testing, build and deployment to a cloud solution using containers (Docker Swarm on Amazon Web Services EC2 instances).

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/movida_app_logic.jpg' | relative_url }}" alt="" title="MOVIDA - React Native UI logic"/>
    </div>
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/movida_backend_cicd.jpg' | relative_url }}" alt="" title="CI/CD logic"/>
    </div>
</div>
<div class="caption">
    Differences between Android and iOS in React Native (right), and the CI/CD logic for the backend components.
</div>