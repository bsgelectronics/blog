---
layout: post
title: "6116 RAM Memory Tester"
date: 2024-12-26
---

## How it works

<iframe width="560" height="315" src="https://www.youtube.com/embed/13J_Huuk3XA" title="6116 RAM Memory Tester overview" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## What's Included

![6116 RAM Memory Tester kit contents]({{ site.baseurl }}/assets/images/6116/6116_2.png)

## Assembly Instructions

You will also need an Arduino Mega, soldering supplies, wire cutters, and a PC with a USB port.

1. **Assemble the upper components.** Insert the LEDs, switches, and ZIF sockets. LEDs must be inserted in the correct orientation — the longer leg should go in the hole on the opposite side of the flat mark on the board.

   ![LED long leg vs. short leg orientation]({{ site.baseurl }}/assets/images/6116/longshort.jpg)
   ![Flat mark orientation on the board]({{ site.baseurl }}/assets/images/6116/flat.jpg)

2. **Check your work.** The board should look like this with the components inserted.

   ![Board with upper components inserted]({{ site.baseurl }}/assets/images/6116/IMG_20260127_124517978_HDR.jpg)

3. **Flip the board over and solder in the components.** Ensure that extra solder does not connect any pins. Trim the extra wire length off the LED legs.

4. **Prepare the riser pins.** Cut the pins to fit into the series of holes on the edges of the board. Extra pins can be saved or discarded.

5. **Insert the pin sets** as shown.

   ![Pin sets inserted into the board]({{ site.baseurl }}/assets/images/6116/IMG_20260127_124534781.jpg)

6. **Solder the pins from the top of the board**, then install the completed shield on your Arduino Mega.

7. **Install the Arduino IDE.** Download and install the [Arduino IDE software](https://www.arduino.cc/en/software).

8. **Download the 6116 memory test source code.** Go to the [6116-Memory-Tester repository](https://github.com/cpyne2/6116-Memory-Tester), select **Code > Download ZIP**, then extract the ZIP file and save `6116-sram-tester.ino`.

9. **Connect your Arduino Mega to your computer via USB.**

10. **Configure the Arduino IDE.** Launch the IDE and make sure **Arduino Mega** and your correct COM port are both selected under the **Tools** menu.

11. **Open the sketch.** Select **File > Open**, then select the `6116-sram-tester.ino` file you downloaded in step 8.

12. **Upload the sketch.** Select **Sketch > Upload** to load the code onto your Arduino.

    > **Note:** If you encounter an upload error, retry with the shield disconnected from your Arduino.

## Using the 6116 Tester

1. Insert one 6116 chip to be tested. Do not install two chips at once. The semicircle mark on the chip should point toward the LEDs (pin 1 in the upper left).

2. Plug the Arduino in with a 9V power supply or USB. The test cycle begins automatically.

3. The test takes a few minutes to complete. **Solid green = good**, **solid red = bad**.

4. Press reset to restart a test.

## Schematic

![6116 RAM Memory Tester schematic]({{ site.baseurl }}/assets/images/6116/schematic.png)

## Parts List

- [Download BOM (XLSX)]({{ site.baseurl }}/assets/images/6116/BOM%206116.xlsx)
- [6116-Memory-Tester source code](https://github.com/cpyne2/6116-Memory-Tester)

## Buy the Kit

- [BSG Electronics](https://bsgelectronics.com/6116-ram-tester-arduino-mega)
- [eBay](https://www.ebay.com/itm/166983829839)
