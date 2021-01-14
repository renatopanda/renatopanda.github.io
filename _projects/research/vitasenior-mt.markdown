---
layout: page
title: VITASENIOR-MT
description: "<b>Senior healthcare assistance in Medio Tejo</b> | September 2017 - September 2019 (24 months) | <i>Financed by FEDER / CENTRO2020 / FCT: 127 189€</i>"
website: http://vita.ipt.pt/vitasenior-mt/
img: /assets/img/vitasenior.jpg
categories: research
importance: 2
---
<a href="{{page.website}}" target="_blank">Project website - CENTRO-01-0145-FEDER-023659</a>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/vitasenior.jpg' | relative_url }}" alt="" title="VITASENIOR Project"/>
    </div>
</div>

This project aim was to develop a telehealth / tele-assistance technological solution
to monitor and improve health care for the elderly living in isolated areas of the
Médio Tejo region. Three entities were involved: the Polytechnic Institute of Tomar
(promoter), Polytechnic Institute of Coimbra (co-promoter), Inter-municipal Community of Médio-Tejo (co-promoter).

Our part (IPT) dealt with the development of the entire infrastructure, from the
hardware to measure and aggregate biometric and environmental data in patients’
homes, to the cloud infrastructure where data was processed and available for consultation by health professionals. Among others, my strongest contribution was the
design of the cloud infrastructure and supervision of the master’s student (<a href="http://hdl.handle.net/10400.26/31425" target="_blank">Diogo
Mendes</a>) responsible for developing it.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/vitasenior_architecture.png' | relative_url }}" alt="" title="VITASENIOR platform architecture"/>
    </div>
</div>
<div class="caption">
    The VITASENIOR architecture, using embedded processors, sensors and communication hardware to collect, send and act on data acquired from direct end-users and the environment. Collected data is then shared by connecting to an IoT gateway, the VITABOX, where it is either sent to the cloud to be stored and processed, or analyzed locally.
</div>

The cloud infrastructure follows a microservices architecture, with several of these services communicating through a message queue server, all orchestrated by docker swarm (details).
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/vitasenior_cloud.jpg' | relative_url }}" alt="" title="VITASENIOR cloud services architecture"/>
    </div>
</div>
<div class="caption">
    VITASENIOR cloud services architecture.
</div>

This work originated several publications, 1 best poster award at a national conference, and 5 M.Sc. theses, which are listed at the project website.
