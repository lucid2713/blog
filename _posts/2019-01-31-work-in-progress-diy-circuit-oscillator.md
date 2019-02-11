---
layout: post
title: Work in progress - DIY circuit oscillator
excerpt: "building circuit oscillator"
tags: [e-waste, instrument, handmade electronics]
categories: [work, research]
modified: 2019-02-04

---

## Let's build more circuits with e-waste

*to be updated*

### metal detector
While reading *A Geology of Media* by Jussi Parikka, I got to know that one of important recycling process at e-waste dumpsite is to excavate and sort out metal from all broken the parts. So I searched how we can detect metals and found there are quite easy ways to make DIY metal detector! I followed these two tutorials. (one, two)
Mostly this metal detector works with IC 555 timer chip in order to make sounds when it detects metal. This is also very cool for me as I've been generating sounds from e-waste so far.

Thus I decided to make a metal detector, the materials to make it would be from e-waste, and then use it to detect and find metals from e-waste. I thought not only it could be useful but also it could be very playful.
I could see several thick coils(made from copper) among my e-waste, which is needed for metal detector. So I took one out from a complicated looking board and made a circuit with amp chip and this coil.
<br><br>

*(circuit drawing)*
<br><br><br>

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/J2WGZsE1m4w" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>
In this video you can see how it works.
<br>
2 speakers and coil from my e-waste collection
</p>

<br>
However, when I tried, I can hear sounds but it was not very distinctive whether it catches up the metal or not. And there are many variables which affects accuracy of this metal detector such as the size of coil, values of resistors and capacitors.
Anyways when I tired with the same of resistors and capacitors as tutorials, the sound was not clear thus I guess I maybe have to try with more bigger coil. However at the moment, when I just change the value of resistors and capacitors randomly, and put metals close to it, it makes sounds for some reason. But I'm not sure if it works in this way anyhow.

Nevertheless, this metal detector could be another possible instruments. So I'm gonna keep working on it to make it operate properly.


### sorting out e-waste
I decided to make as many circuit instruments as I can from now on. This time I would try with several different oscillator chips together with any kinds of possible components from e-waste.
<br><br>
![categorizing components]({{site.url}}/img/parts_categorization.gif){: width="800px"}
<br><br>
I sorted out what kinds of components I can use from my e-waste collection. This is the list of components I can directly re-use from e-waste.
* push buttons
* leds (led panels)
* resistors
* capacitors
* transistors
* switch

According to this categorizing, I'll combine these components with several different circuit instruments. For the other e-wastes which are not sorted from this categorization, I can still use them as a resistor by connecting somewhere on their body to the circuit instruments. I used them in this way before.
<br>
*(add drawing to illustrate this idea)*
<br><br>
<hr>

### integrated chips - schmitt trigger oscillator and its friends

#### cd40106
<br>
*(description & videos)*

![circuit with cd40106, cd4093, and cd4049]({{site.url}}/img/cd40106_4093_4049.png){: width="800px"}

<br><br>

#### cd4093
NAND gate oscillator
<br>
*(description & videos)*
<br><br>
![cd4093_drawing]({{site.url}}/img/cd4093_drawing.jpg){: width="800px"}

<br><br>

#### cd 4040
<br>
*(description & videos)*
<br><br>
![cd4093 with cd4040]({{site.url}}/img/cd4093_with_cd4040.JPG){: width="800px"}

<br><br>

#### cd 4051
<br>
*(description & videos)*
<p align="center">
8 ways analog switch
</p>
![cd4051 with cd4040 and cd40106]({{site.url}}/img/sequencer_cd4051_cd4040_cd40106.JPG){: width="800px"}

![cd4051 with cd4040 and cd40106 with leds]({{site.url}}/img/sequencer_with_leds.JPG){: width="800px"}


<br><br>
##### non synchronized sounds
<p align="center">
cd40106 and cd4051 with e-waste
<br><br>
<audio controls>
	<source src="/audio/cd40106,cd4051.mp3" type="audio/mpeg">
	<source src="/audio/cd40106,cd4051.ogg" type="audio/ogg">
	Your browser does not support the audio tag.
</audio>
</p>

![cd4051 with cd40106]({{site.url}}/img/cd40106,cd4051.JPG){: width="800px"}

<br><br><br>
