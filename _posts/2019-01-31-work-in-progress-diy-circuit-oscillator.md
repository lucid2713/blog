---
layout: post
title: Work in progress - DIY circuit oscillator
excerpt: building circuit oscillator
tags:
  - e-waste
  - instrument
  - handmade electronics
categories:
  - work
  - research
modified: 2019-02-12T00:00:00.000Z
---

# Let's build more circuits with e-waste


## metal detector

While reading _A Geology of Media_ by Jussi Parikka, I got to know that one of important recycling process at e-waste dumpsite is to excavate and sort out metal from all broken parts. So I searched how we can detect metals and found there are quite easy ways to make DIY metal detector! I followed these two tutorials. (one, two) Mostly this metal detector works with IC 555 timer chip to make sounds when it detects metal. This is also very cool for me as I've been generating sounds from e-waste so far.

Thus I decided to make a metal detector, the materials to make it would be from e-waste, and then use it to detect and find metals from e-waste. I thought not only it could be useful, but also it could be very playful. I could see several thick coils(made from copper) among my e-waste, which is needed for the metal detector. So I took one out from a complicated looking board and made a circuit with amp chip and this coil.
<br>
<br>

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/J2WGZsE1m4w" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="">
</iframe>
<br>
In this video, you can see how it works.<br>
2 speakers and coil from my e-waste collection
</p>

<br>
However, when I tried, I can hear sounds, but it was not very distinctive whether it catches up the metal or not. And many variables affect the accuracy of this metal detector such as the size of the coil, the values of resistors and capacitors. Anyways when I tired with the same of resistors and capacitors as tutorials, the sound was not clear thus I guess I maybe have to try with a bigger coil. However at the moment, when I change the value of resistors and capacitors randomly and put metals close to it, it makes sounds for some reason. But I'm not sure if it works in this way anyhow.

Nevertheless, this metal detector could be another possible instrument. So I'm going to keep working on it to make it operate properly.

## sorting out e-waste

I decided to make as many circuit instruments as I can from now on. This time I would try with several different oscillator chips together with any possible components from e-waste.
<br>
<br>

![categorizing components]({{site.url}}/img/parts_categorization.gif){: width="800px"}
<br>
<br>
I sorted out what kinds of components I can use from my e-waste collection. This is the list of parts I can directly re-use from e-waste.

- push buttons
- leds (led panels)
- resistors
- capacitors
- transistors
- switch

According to this categorizing, I'll combine these components with several different circuit instruments. For the other e-wastes which are not sorted from this categorization, I can still use them as a resistor by connecting somewhere on their body to the circuit instruments. I used them in this way before.
<br>

![capacitors and resistors, ready to be connected]({{site.url}}/img/ready_to_be_connected.jpg){: width="800px"}
<p align="center">
ready to be connected!
</p>
<br>
![drawing e-waste instruments connected]({{site.url}}/img/e-waste_instrument_connecting_idea.jpg){: width="800px"}
<br>
<br>

--------------------------------------------------------------------------------

### integrated chips - schmitt trigger oscillator and its friends

#### cd40106
 <br>

![circuit with cd40106, cd4093, and cd4049]({{site.url}}/img/cd40106_4093_4049.png){: width="800px"}

The picture above is a circuit instrument combined with cd40106, cd4093, and cd4049, which was made by myself last year. I connect e-waste by using alligator clips on top of this circuit board(on the little clips). It was used for my work ['sonic waste'](http://mina-vitamina.net/sonic-waste) and ['playful obsolescence'](http://mina-vitamina.net/playful-obsolescence). And I've been playing it at several performances; [shaky grounds festival](https://www.youtube.com/watch?v=APx7oDdLYCg), [gallery sign](https://www.youtube.com/watch?v=reulvS8F-fg) and [tuttottud](https://www.youtube.com/watch?v=Fom82mC99Wg).

<br>
<br>

#### cd4093 NAND gate oscillator
<br>
<br>
![cd4093_drawing]({{site.url}}/img/cd4093_drawing.jpg){: width="800px"}
<p align = "center">
cd4093 schematics
</p>


<p align = "center">
cd4093 with e-waste(using resistor and capacitor)
<br><br>
<audio controls="">
<source src="https://raw.githubusercontent.com/lucid2713/blog/master/audio/cd4093_with_e-waste.mp3" type="audio/mpeg">
    Your browser does not support the audio tag.
</audio>
</p>

<br>
<br>

#### cd 4040
<br>
<br>
![cd4093 with cd4040, 1]({{site.url}}/img/cd4093_with_cd4040.JPG){: width="800px"}

![cd4093 with cd4040, 2]({{site.url}}/img/cd4093_with_cd4040_2.jpg){: width="800px"}
<p align="center">
cd4040(frequency divider) with cd4093
<br>
<br>
<audio controls="">
<source src="https://raw.githubusercontent.com/lucid2713/blog/master/audio/cd4093,cd4040.mp3" type="audio/mpeg">
<source src="https://raw.githubusercontent.com/lucid2713/blog/master/audio/cd4093,cd4040.ogg" type="audio/ogg">
    Your browser does not support the audio tag.
</audio>
</p>
<br>
<br>

#### cd 4051
<br>

<p align="center">
8 ways analog switch (cd40106, cd4040, and cd4051)
</p>

![cd4051 with cd4040 and cd40106]({{site.url}}/img/sequencer_cd4051_cd4040_cd40106.JPG){: width="800px"} ![cd4051 with cd4040 and cd40106 with leds]({{site.url}}/img/sequencer_with_leds.JPG){: width="800px"}
<br>
<br>

##### non synchronized sounds

When the schmitt trigger(e.g. cd40106) is directly connected to the cd4051(sequencer) without the same resistors to make the sounds synchronized, it makes very messy dissonant sounds.

![cd4051 with cd40106]({{site.url}}/img/cd40106,cd4051.JPG){: width="800px"}

<p align="center">
cd40106 and cd4051 with e-waste
<br>
<br>

<audio controls="">
<source src="https://raw.githubusercontent.com/lucid2713/blog/master/audio/cd40106,cd4051.mp3" type="audio/mpeg">
<source src="https://raw.githubusercontent.com/lucid2713/blog/master/audio/cd40106,cd4051.ogg" type="audio/ogg">
    Your browser does not support the audio tag.
</audio>
</p>



<br>
<br>

#### cd4069

cd4069 chip has much smoother sounds as it is 'buffered' and has a triangle wave.

![cd4069 with cd40106]({{site.url}}/img/cd4069,cd40106.JPG){: height="500px"}

<p align="center">
cd40106 and cd4069 with e-waste
<br>
<br>

<audio controls="">
<source src="https://raw.githubusercontent.com/lucid2713/blog/master/audio/cd4069,cd40106_with_e-waste.mp3" type="audio/mpeg">
    Your browser does not support the audio tag.
</audio>
</p>

<br><br>

#### Play all together!

<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/wJkMtNKQ2Oo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>
Improvised play with four different circuits and e-waste
</p>

<br>
from below to upper
* n1. cd40106 + cd4040 + cd4051 + e-waste<br>
* n2. cd40106 + cd4051 + e-waste<br>
* n3. cd40106 + cd4069 + e-waste<br>
* n4. cd4093 + cd4040 + e-waste<br>

<br>
<hr>

#### Reference

- [Noise hackerspace](https://noisehackerspace.com/amazing-lunetta-synth-simple-diy-quad-nand-cmos/)
- [Hackaday, 'logic noise' series](https://hackaday.com/2015/02/04/logic-noise-sweet-sweet-oscillator-sounds/)
- [Bastl instruments, DIY synth tutorials](https://bastl-instruments.com/support/tutorials/omsynth-project-2)
<br>
<br>
<br>
