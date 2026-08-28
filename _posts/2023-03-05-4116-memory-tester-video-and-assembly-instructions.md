---
layout: post
title: "4116 Memory Tester Video And Assembly Instructions"
date: 2023-03-05
canonical: https://blog.bsgelectronics.com/4116-memory-tester-video-and-assembly-instructions/
meta-description: "4116 Memory Tester Video and Assembly Instructions"
---

## How it works

<iframe width="560" height="315" src="https://www.youtube.com/embed/WWA9xFqeUac" title="4116 Memory Tester overview" frameborder="0" allowfullscreen></iframe>

## Schematic and BOM Download

- [Download BOM (XLSX)](https://raw.githubusercontent.com/bsgelectronics/blog/main/assets/images/82s123/PromProg2BOM.xlsx)
- [Download Schematic (PDF)](https://raw.githubusercontent.com/bsgelectronics/blog/main/assets/images/4116/4116schema.pdf)

## Assembly Instructions

You will also need a soldering iron, an Arduino Uno, wire cutters, and a PC with a USB port.

1. **Identify the included parts.** These are the parts included in the kit.

   ![Kit parts laid out before assembly](https://blog.bsgelectronics.com/assets/images/4116/parts.jpg)

2. **Assemble the upper components.** Insert components based on the item IDs on the inventory sheet. Make sure LEDs, capacitors, and diodes are inserted with the correct orientation, matching the pictures below.

   ![Capacitor orientation reference](https://blog.bsgelectronics.com/assets/images/4116/caps.jpg)

   ![Diode orientation reference](https://blog.bsgelectronics.com/assets/images/4116/diodes.jpg)

   <!-- NOTE: this third image reused caps.jpg in the original post — confirm whether a different photo (e.g. LED orientation) was intended here -->
   ![4116 component orientation reference](https://blog.bsgelectronics.com/assets/images/4116/caps.jpg)

3. **Flip the board over and solder in the components.** Ensure that extra solder does not connect any pins. Trim the extra wire length off the LED legs.

4. **Clip and insert the riser pins.** Clip to size and insert the riser pins from the bottom, then solder in from the top.

   ![Riser pins soldered from the bottom of the board](https://blog.bsgelectronics.com/assets/images/4116/bottom.jpg)

5. **Install the completed shield on your Arduino Uno.**

6. **Install the Arduino IDE.** Download and install the [Arduino IDE software](https://www.arduino.cc/en/software).

7. **Download the 4116 memory test source code.** Go to the [4116MemTest repository](https://github.com/cpyne/4116MemTest), select **Code > Download ZIP**, then extract the ZIP file and save `4116.ino`.

8. **Connect your Arduino Uno to your computer via USB.**

9. **Configure the Arduino IDE.** Launch the IDE and make sure **Arduino Uno** and your correct COM port are both selected under the **Tools** menu.

10. **Open the sketch.** Select **File > Open**, then select the `4116.ino` file you downloaded in step 7.

11. **Upload the sketch.** Select **Sketch > Upload** to load the code onto your Arduino.

## Using the 4116 Tester

1. Insert the 4116 chip to be tested into the ZIF socket.

   > **Important:** Ensure the chip is inserted with the notch facing up, toward the LEDs. Inserting it backwards can damage the chip.

2. Plug the Arduino in with a 9V power supply or USB. Testing begins automatically when power is connected.

3. Testing runs for about 10 seconds and displays: **solid green = good**, **solid red = bad**.

4. It's possible to insert chips with the tester already plugged in, but make sure pins aren't crossed and the chip has the correct orientation.

5. Press the button to run additional tests.

## Troubleshooting

Verify you have the correct voltages at the locations shown below. Incorrect or missing voltages can be caused by improper assembly — check for solder bridges, resistors in the wrong locations, or chips installed backwards.

![Voltage test points](https://blog.bsgelectronics.com/assets/images/4116/voltage.jpg)

## Schematic

![Full schematic diagram](https://blog.bsgelectronics.com/assets/images/4116/schematic.jpg)
