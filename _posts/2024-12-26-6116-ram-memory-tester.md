### 6116 RAM Memory Tester

## How it works

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/13J_Huuk3XA"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>


## What's included

![]({{site.baseurl}}assets/images/6116/6116_2.png)

## Assembly Instructions

1. Other parts you will need - an Arduino Mega, soldering supplies, wire cutters, and a PC with a USB port. 

2. Assemble upper components.   Insert LEDs, Switches, and the zif sockets.   LEDs must be inserted in the correct orientation.    The longer leg should be inserted in the hole on the opposite side of the flat mark on the board. 

![]({{site.baseurl}}/assets/images/6116/longshort.jpg)

![]({{site.baseurl}}/assets/images/6116/flat.jpg)

3.  The board should look like this with the components inserted.

![]({{site.baseurl}}/assets/images/6116/IMG_20260127_124517978_HDR.jpg)

4. Flip the board over and solder in the components.   Ensure that extra solder does not connect any pins.   Trim the extra wire length off the led legs. 

5. Now cut the pins to fit into the series of holes on the edges of the board.   Extra pins can be saved or discarded. 

6. Insert the pin sets as shown.

![]({{site.baseurl}}/assets/images/6116/IMG_20260127_124534781.jpg)

7. Solder pins from the top of the board and install the completed shield on your Arduino Mega

8.  Download and install the Arduino IDE software from arduino.cc

https://www.arduino.cc/en/software

9. Download the 6116 memory test source code.  Select "Code" > "Download Zip".   Extract zip file and save 6116-sram-tester.ino

[https://github.com/cpyne2/6116-Memory-Tester](https://github.com/cpyne2/6116-Memory-Tester)

10. Connect your Arduino Mega to your computer via USB.  

11. Launch the Arduino IDE software.  Make sure "Arduino Mega" and your appropriate COM port are both selected under the Tools menu.   

12. Select File > Open and then select the 6116-sram-tester.ino file that you downloaded previously.

13.  Select "Sketch" > "Upload" to load the file to your Arduino.  *Note - If you encounter an upload error, retry with the shield disconnected from your Arduino. 

##  Using the 6116 Tester

1. Insert one 6116 chip to be tested.  Do not install 2 chips at once.  Note - the semi circle mark on the chip should be pointing towards the leds.   (pin 1 in the upper left)

2. Plug the Arduino in with a 9v power supply or USB.  The test cycle will begin automatically. 

3.  The test will take a few minutes to completed and should end with Green = Good, Red = Bad

4. Press reset to restart a test.

## Schematic

![]({{site.baseurl}}/assets/images/6116/schematic.png)


## Parts List

[BOM]({{ site.baseurl }}/assets/images/6116/BOM 6116.xlsx)

https://github.com/cpyne2/6116-Memory-Tester

https://bsgelectronics.com/6116-ram-tester-arduino-mega

https://www.ebay.com/itm/166983829839


