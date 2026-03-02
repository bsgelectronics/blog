### A Manual Programmer for 82s129, 82s126, 74s287, and 74s387 PROM Chips

## Introduction

The 82s129, 82s126, 74s287, and 74s387 are PROM chips that were commonly used in older arcade games, vintage PCs, and equipment from the 1970s and 80s.    Many modern programmers do not support these chips often making vintage electronics projects difficult to complete.   This manual programmer can be used to read and write these chips.     PROM chips are written by blowing tiny fuses inside the chip and can only be written once.   If you mistakenly pulse the wrong bit on, you'll need to start over with a new chip.    When completing this board, it is advisable to practice pulsing some blank locations on an already written "scratch" chip like I do in this video.    Note: We also have an 82s123 version 

## Video

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/MStExWdTmQo"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>

## Parts List

[BOM]({{ site.baseurl }}/assets/images/82s129/PromProg2BOM.xlsx)

## Pictures

![]({{site.baseurl}}/assets/images/82s129/20250531_155821.jpg)

![]({{site.baseurl}}/assets/images/82s129/20250531_155851.jpg)

![]({{site.baseurl}}/assets/images/82s129/20250531_160222.jpg)

## Operation

How do I use it?  This programmer is manual and requires understanding of both Binary and Hexadecimal numbers.   These chips are made up of 256 addresses each which hold 4 bits of data.   Both the addresses and the bits are just 1s and 0s, but often the data you need to write will be in hex format.

Example - Lets say you wanted to write the value "E" to address "100".   To do this, we need to figure out the binary values for both E (hex) and 100 (decimal).   There are many converters available online if you're unsure how to do this.

https://www.rapidtables.com/convert/number/hex-to-binary.html?x=E

E converts to 1110.   This is the value we want to write to the chip to be shown in the LEDs.   1110 = On-On-On-Off

We need to write this to address 100.   100 is decimal, so lets covert that to binary too.

https://www.rapidtables.com/convert/number/decimal-to-binary.html?x=100

100 converted into binary is 1100100, but that is only 7 digits wide, so we need to add a leading 0.  1100100 = 01100100

01100100 is the address we want to write to.   To get to this address, we need to set the switches to match this pattern.

01100100 = Down-Up-Up-Down-Down-Up-Down-Down.

We are at the correct address so pulse On-On-On-Off to the LEDs here.

Repeat for all 256 addresses.

## Power

This board requires +5v, +12v, and G which can be tapped from a PC or arcade power supply.    For PC power supply, you can use a standard hard drive power connector.  

## Assembly

Note orientation of blue push buttons.  Don't accidentally install these backwards! 

![]({{site.baseurl}}/assets/images/82s129/Buttons.jpg)

## Buy the PCB

Available on this site and ebay


## Digikey List (key parts)

https://www.digikey.com/en/mylists/list/JAWGCR5KV5



## Schematics

![]({{site.baseurl}}/assets/images/82s129/schematic1.png)

![]({{site.baseurl}}/assets/images/82s129/schematic2.png)

## Version History

All boards being sold today are version 1.1 which is not known to have any errors.   You will receive a version 1.1 board even if some of the video and pics still show the 1.0 version number.  If you have a v1.0 board and are experiencing isssues, please contact me for a fix or replacement
