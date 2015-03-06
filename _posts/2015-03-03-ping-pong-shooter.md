---
layout: post
title: Ping Pong Ball Shooter
description: omschrijving eind product
tags: [project, ping-pong, beschrijving]
modified: 2015-03-03
image:
  feature: 3134373590_56872e3ba8_o.jpg
  credit:  Michael Knowles
  creditlink: https://www.flickr.com/photos/mknowles/3134373590
comments: true
share: false
---

Na een paar weken denken en doen met de Arduino kom je er achter wat de beperkingen zijn van het platform. Het is mogelijk om de stem te gebruiken om het aan te sturen, helaas is dit een stuk moeilijker om het werkend te krijgen. [Een beetje zoeken](http://arduinoinaustralia.blogspot.nl/2012/09/diy-ping-pong-ball-launcher-with-arduino.html) helpt me een nieuwe richting in te slaan. Het idee is om een klap geactiveerde ping-pong ballen lanceerder te maken. Het aantal klappen zou moeten aangeven hoeveel ballen afgevuurd moeten worden.

Ik heb al eerder een samenvatting [hier]({% post_url 2015-02-17-hello-world %}) gemaakt, maar deze is terug gebracht naar een iets makkelijkere opdracht. Fucties die vervallen zijn de stem commando's voor de bediening. Wat komt er voor in de plaats?

<!--more-->

##Ping Pong SHOOTER

<figure>
    <img src="/images/ping-pong.png" alt="flowchart hoe het uiteindelijk moet werken">
</figure>


## Componenten
Er zijn ook componenten nodig om dit allemaal werkend te krijgen. 

| Component | Functie | Opmerkingen |
|:----------|:--------|:------------|
| Motor | Aandrijving voor de bal | Moet Arduino compatible zijn, geavanceerdere toepassingen hebben een transistor nodig |
| Transistor | maakt communicatie tussen motor & Arduino mogelijk | **meer informatie over toepassing in het Arduino systeem** |
| Servo | nodig om het klepje te openen zodat er een bal door heen past |  |
| Ping pong ballen | Projectielen |  |
| Wielen | Contactpunt met de ballen | Rubberen omhulsel voor meer grip |
| Bevestigingsmateriaal | |
| Constructiemateriaal | |
| _LCD scherm_ | om het aantal afgeschoten ballen te tellen | ook voor instructies |
| drukschakelaar | het geheel aan- en uitschakelen | voorkomt ongelukken |

In het weekend ga ik onderzoeken welke motoren schikt zijn om een bal af te schieten.
