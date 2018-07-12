---
layout: post
title: "S.O.S(sense of self) workshop"
excerpt: "Self-quantification workshop with physical computing by TeZ Maurizio Martinucci"
tags: [Arduino]
categories: [workshop]
modified: 2018-07-12
image:
  feature: heartbeat01.png
---

From 10th t0 12th Jan, 2018, my colleagues and I had participated physical computing workshop dealing with measurement sensors. Under the guidance of [Tez](http://www.tez.it/), we tinkered with ESP32 board with Pulse sensor, RGB Neopixel, Temperature sensor, and GSR(Galvanic Skin Response) sensor.

For the outcome of 3days workshop, I made a fake, cheesy deceptive visual interface interacting with Pulse sensor. Additionally, I followed this [tutorial](https://pulsesensor.com/pages/code-and-guide) for controlling Pulse sensor, and used Processing to make the visual interface. I utilized [Processing Visualization App](https://pulsesensor.com/pages/processing-visualization) and modified it for my idea.  


![Smithsonian Image]({{ site.url }}/img/heartbeat.gif)
{: .pull-right}
<br>

For some technical problem, I used Arduino instead of ESP32 board for this work. So it is basically devised to induce people to put their index finger on the Pulse sensor, and then the program analyzes the pulse rate received from the sensor. Thus people can see the visual outcome through the screen with a diagnosis phrase and the graph changing in real time.

The trick is, heart rate has no direct association with the personal health. Even though, lots of information online suggest proper heart rate with age, and people are deceived by them. I used the fake information scrapped from online and combined them with pules rate outcome.

![Smithsonian Image]({{ site.url }}/img/heartbeat06.png)
{: .pull-right}

Setup for the Open day event of my college on 17th Feb. 2018.

<br><br>
