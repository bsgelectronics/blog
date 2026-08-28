---
layout: post
title: "2114 and 9114 Memory Tester Video and Assembly Instructions"
date: 2022-03-11
---

## How it works

## Assembly Instructions

You will also need a soldering iron, an Arduino Uno, wire cutters, and a PC with a USB port.

1. **Identify the included parts.** These are the parts included in the kit.

   ![Kit contents laid out before assembly]({{ site.baseurl }}/assets/images/2114/contents.jpg)

2. **Assemble the upper components.** Insert the LEDs, switches, and the ZIF socket. LEDs must be inserted in the correct orientation — the longer leg should go in the hole on the opposite side of the flat mark on the board.

   ![LED orientation reference]({{ site.baseurl }}/assets/images/2114/led.jpg)

3. **Check your work.** The board should look like this with all components inserted.

   ![Board with upper components inserted]({{ site.baseurl }}/assets/images/2114/Upper.jpg)

4. **Flip the board over and solder in the components.** Ensure that extra solder does not connect any pins. Trim the extra wire length off the LED legs.

   ![Board flipped over for soldering]({{ site.baseurl }}/assets/images/2114/flip.jpg)

5. **Prepare the riser pins.** Cut the pins to fit into the series of holes on the edges of the board. Extra pins can be saved or discarded.

   ![Pins cut to length]({{ site.baseurl }}/assets/images/2114/Pins.jpg)

6. **Insert the pin sets** as shown.

   ![Pin sets inserted into the board]({{ site.baseurl }}/assets/images/2114/Pins2.jpg)

7. **Solder the pins from the top of the board**, then install the completed shield on your Arduino Uno.

   ![Pins soldered from the top of the board]({{ site.baseurl }}/assets/images/2114/Top.jpg)

8. **Install the Arduino IDE.** Download and install the [Arduino IDE software](https://www.arduino.cc/en/software).

9. **Download the 2114 memory test source code.** Go to the [2114MemTest repository](https://github.com/cpyne/2114MemTest), select **Code > Download ZIP**, then extract the ZIP file and save `Test2114.ino`.

10. **Connect your Arduino Uno to your computer via USB.**

11. **Configure the Arduino IDE.** Launch the IDE and make sure **Arduino Uno** and your correct COM port are both selected under the **Tools** menu.

12. **Open the sketch.** Select **File > Open**, then select the `Test2114.ino` file you downloaded in step 9.

13. **Upload the sketch.** Select **Sketch > Upload** to load the code onto your Arduino.

    > **Note:** If you encounter an upload error, retry with the shield disconnected from your Arduino.

## Using the 2114 Tester

1. Plug the Arduino in with a 9V power supply or USB.

2. Insert the 2114 chip to be tested. The semicircle mark should point toward the LEDs (pin 1 in the upper left).

3. Press **Begin Test** to run the test cycle.

4. Press and hold **End Test** to stop.

5. **Solid green = good**, **solid red = bad**.

6. Testing runs in a loop, and the red LED will turn on — and stay on — if an error is encountered. This is useful for longer test runs to help rule out intermittent failures.
