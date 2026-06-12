### Motor reversing door controller board for use in chicken coops

## Introduction

I have had chickens for the past 10 years and have had multiple iteations of contollers to open/close a door via a linear actuator.  The circuit requiered is pretty simple, but wiring quickly becomes messy as extra features and functions are added.  This board was created to simplify all the messy wiring and functions of my custom coop controller.  

![]({{site.baseurl}}/assets/images/chicken/done.jpg)

## Key Features

Detachable timer - Bring the timer inside and program it indoors in a warm house, in good light, with your glasses
![]({{site.baseurl}}/assets/images/chicken/detach.jpg)
Manual Override - Open/Close the door without changing the timer
![]({{site.baseurl}}/assets/images/chicken/switches.jpg)
External status LED hookups - Instantly see door status at night by colored leds
Multiple linear actuator outputs
Photor Electric safety cutoff - Stops motion if a chicken is blocking the door.

## Videos

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/cAsn8lur-BM"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/w9KVft6hweE"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>

##Assembly
Assembly requires soldering.  All solder parts are included. 

## Buy the kit
https://www.ebay.com/itm/168453167090

## Parts Not Included - I am selling this board as a solder kit.  In order to keep the cost low, these items you'll need to buy yourself.

Weasch CN101A 12v Timer - Available on Amazon.  Other timers might work, but get this one to ensure the connectors line up exactly. 

https://www.amazon.com/dp/B0D59B1DD1?th=1

External 12v LEDs - Use to display door, power, and beam status.
https://www.ebay.com/itm/406938606988
https://www.ebay.com/itm/196760274076

Photo Electric Emitter and Sensor - I suggest one "E3F-5L" emitter and one "E3F-5DP2" sensor.  Sensor is PNP NC. Available on EBay


Power Supply - This board is designed to run on 12v DC.  Be sure to use a power supply that can deliver enough amerage to power your liner actuator(s).   I am using this 5A supply from Amazon

https://www.amazon.com/dp/B0D7GGGM6Q

## Build Instructions

Insert and solder components into the PCB matching the labels on the PCB front silkscreen.  There are a few items to be aware of.

1. Glass fuse clips are use to hold the timer spade blades in place.  Before soldering them in, beak off and discard the small end tab.   Gradually bend the fuse holder sides in usind needle nose pliers.  Ensure both sides touch each other and are centered. A few extra clips are inluded if you break one.

![]({{site.baseurl}}/assets/images/chicken/bend.jpg)
![]({{site.baseurl}}/assets/images/chicken/fuseslots.jpg)

3. The two small transistors in the center of the board are not labled on the silkscreen.  Ensure the VP3203N is on the left and the 2N7000 is on the right

![]({{site.baseurl}}/assets/images/chicken/transistors.jpg)

4. Make sure you get the LED polarity correct.  The long leg of the LED is positive and should be away from the flat side of the silkscreen symbol. 


