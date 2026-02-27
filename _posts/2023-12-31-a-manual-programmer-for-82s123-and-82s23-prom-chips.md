## A Manual Programmer for 82s123, 82s23, 74s288, and 74s188 PROM Chips Version 1.5

**Introduction**

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/mj218WpNHEA"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>

The 82s123, 82s23, 74s288 and 74s188 are PROM chips that were commonly used in older arcade games, vintage PCs, and equipment from the 1970s and 80s.  Many modern programmers do not support these chips often making vintage electronics projects difficult to complete.   This manual programmer can be used to read and write these chips.  PROM chips are written by blowing tiny fuses inside the chip and can only be written once.   If you mistakenly pulse the wrong bit on, you'll need to start over with a new chip.  When completing this board, it is advisable to practice pulsing some blank locations on an already written "scratch" chip like I do in this video.  

![]({{site.baseurl}}/assets/images/82s123/Done.jpg)

**The PCB** - You can buy the blank PCB [here](https://bsgelectronics.com/manual-prom-programmer-pcb-for-82s123-and-82s23) or [ebay](https://www.ebay.com/itm/166529806268).   The rest of the parts you can buy via Digikey, Ebay, and others.

![PCB]({{site.baseurl}}/assets/images/82s123/PCB.jpg)

![Yellow]({{site.baseurl}}/assets/images/82s123/Yellow.jpg)

![Blue]({{site.baseurl}}/assets/images/82s123/Blue.jpg)

**Power** - This board requires +5v, +12v, and G which can be tapped from a PC or arcade power supply.    For PC power supply, you can use a standard hard drive power connector. 

![Wire]({{site.baseurl}}/assets/images/82s123/Wire.jpg)

**Parts Required** - The parts for this project can be purchased from Digikey, Ebay.   Electronic hobbyists will likely have some of these parts already available in your parts collection. 

##  Downloads
[BOM list](https://github.com/bsgelectronics/blog/blob/main/assets/images/82s123/PromProg2BOM.xlsx)

[Digikey List](https://www.digikey.com/en/mylists/list/DG3M38DOSF)

**Assembly** - Note orientation of blue push buttons.  Don't accidentally install these backwards!

![Buttons]({{site.baseurl}}/assets/images/82s123/Buttons.jpg)

### Schematic
![schematic1]({{site.baseurl}}/assets/images/82s123/schematic1.png)

![schematic2]({{site.baseurl}}/assets/images/82s123/schematic2.png)

**Thank You** - Thanks to Hans Otten and his site providing info and ideas for making this programmer.  Also, the original 1970s Signetics 82s23 datasheet provided some ideas.

[http://retro.hansotten.nl/6502-sbc/elektuur-junior/junior/junior-expansion-interface-card/program-the-82s23/](http://retro.hansotten.nl/6502-sbc/elektuur-junior/junior/junior-expansion-interface-card/program-the-82s23/)

[https://github.com/bsgelectronics/blog/blob/main/assets/images/82s123/82S23-Signetics.pdf](https://github.com/bsgelectronics/blog/blob/main/assets/images/82s123/82S23-Signetics.pdf)


**Pervious Vesions** - All boards being sold today are version 1.5 which is not known to have any errors.   You will receive a version 1.5 board even if some of the videos and pics still show older version numbers.  A small number of older version boards were shipped in 2024.  If you have an older version and are experiencing problems, please contact me for a replacement or fix instructions. 









