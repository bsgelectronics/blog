#  Williams Stereo Adapter for Stargate Joust Sinistar
![]({{site.baseurl}}/assets/images/williams/complete.jpg)
### What is it?
One of the only early 80s Williams games that featured stereo sound was Sinistar, but this was only in the cockpit version.  This project shows how you can add this same original stereo to a Sinistar (upright) as well as add stereo to Joust and Stargate. 

### Videos
I added Stereo to my Stargate and it sounds great!  Unfortunately, it is difficult to hear the stereo through a cell phone video recordings.  The sound is MUCH BETTER in person.

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/sVfttbVLo6k"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/h_hqxc9s1T0"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>

![]({{site.baseurl}}/assets/images/williams/machine2.jpg)

### What you'll need

1. A second working Williams Sound Board - (1C-2001-146-6)  - Look for one on ebay

2. A 2532 EPROM programmed with either the Sinistar, Joust, or Stargate special stereo rom. (keep reading for more info)

3. Soldering iron and experience with soldering.

4.  An interconnect PCB.   This PCB avoids custom wiring or hacking of the stock harness. The stereo board taps all its connections right from the main harness and provides quick screw terminals for easy speaker hookup and a built in volume pot. 

[https://bsgelectronics.com/williams-stereo-interconnect-board](https://bsgelectronics.com/williams-stereo-interconnect-board)

![]({{site.baseurl}}/assets/images/williams/board.jpg)

5.  An 8 ohm speaker or similar. You can place the speaker on a shelf, on top of the cabinet, or do a more permanent install inside the cabinet if you prefer.    I'm used a small Bose bookshelf speaker with my Stargate. 

6. Speaker wire. 

7. An inline click wheel switch (optional) - Lets you easily toggle stereo on/off. 

![]({{site.baseurl}}/assets/images/williams/th.jpg)

8. Molex and Speaker parts from Digikey

https://www.digikey.com/en/mylists/list/NV6H9PY4BS

(Note - These cheaper 4mm speaker posts available on ebay will also work)

https://www.ebay.com/itm/384940453644

9. An A50K potentiometer 

https://www.ebay.com/itm/304482856805

10. 8x 1/4" Hex x 1 1/2" Aluminum Standoffs 8-32 Thread Male/Female 

https://www.ebay.com/itm/192562877297

### Stereo ROMs

[ROMs]({{ site.baseurl }}/assets/images/williams/StereoRoms.zip)

### Assembly tips

1. Make sure the stereo board is working BEFORE you install the rom or change any jumpers. The Stargate stereo rom does NOT play any sounds when you press the diagnostics button.  I have not confirmed yet if Joust or Sinistar stereo makes diagnostic sounds.  

2. Jumper the stereo board per this article for a 2532 eporm.  Connect W1, W3, W4, W5, W7, W10, and W15 jumpers.  Other jumpers should be removed.

https://www.jestersattic.com/wms_snd.php

![]({{site.baseurl}}/assets/images/williams/jumpers.jpg)

3.  Note - Even though Stargate uses a 2716 for its main board, 2532 is still needed for the stereo board.

4. Remove the screws from your existing sound board and replace them with the hex standoffs.   Reuse the existing screws to mount the stereo board to the standoffs.

5.  Need a 2532 eprom programmed?   Message me and I may be able to help.

### Thank you

to Synamax for reverse engineering the Sinistar source code and making the Joust and Stargate versions of the stereo rom.  Check out his story here...

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/ZRDdKZ7V54I"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>



