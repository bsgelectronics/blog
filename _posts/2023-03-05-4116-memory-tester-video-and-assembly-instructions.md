## 4116 Memory Tester Video and Assembly Instructions

**How it works**

<iframe width="560" height="315"
  src="https://www.youtube.com/embed/WWA9xFqeUac"
  title="YouTube video player"
  frameborder="0"
  allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
  allowfullscreen>
</iframe>

**Schematic and BOM Download**

[BOM 4116](https://github.com/bsgelectronics/blog/blob/main/assets/images/4116/4116%20BOM.xlsx)

[Schematic 4116](https://github.com/bsgelectronics/blog/blob/main/assets/images/4116/4116schema.pdf)

**Assembly Instructions**

1. Parts included - These are the parts that are included in the kit.   You will also need a soldering iron, an Arduino Uno, wire cutters, and a PC with a USB port. 

![Parts](https://github.com/bsgelectronics/blog/blob/main/assets/images/4116/parts.jpg)

2. Assemble upper components.   Insert components based on item IDs on inventory sheet.   Make sure LEDs, capacitors, and diodes are inserted with the correct orientation matching pictures below











3. Flip the board over and solder in the components.   Ensure that extra solder does not connect any pins.   Trim the extra wire length off the led legs. 

4. Clip to size and insert riser pins from the bottom.  Solder in from the top



5.  Install the completed shield on your Arduino Uno

6.  Download and install the Arduino IDE software from arduino.cc

https://www.arduino.cc/en/software

7. Download the 4116 memory test source code.  Select "Code" > "Download Zip".   Extract zip file and save 4116.ino

https://github.com/cpyne/4116MemTest

8. Connect your Arduino Uno to your computer via USB.  

9. Launch the Arduino IDE software.  Make sure "Arduino Uno" and your appropriate COM port are both selected under the Tools menu.   

10. Select File > Open and then select the 4116.ino file that you downloaded in step 7

11.  Select "Sketch" > "Upload" to load the file to your Arduino



Using the 4116 Tester

1. Insert the 4116 chip to be tested into the ZIF socket.   IMPORTANT - Ensure the chip is inserted with the notch facing up towards the LEDs.   Inserting backwards can damage the chip!

2. Plug the Arduino in with a 9v power supply or USB.   Testing will begin when power is connected.  

3. Testing will run for ~10 seconds and will display solid Green = Good, Red = Bad

4. It is possible to insert chips with the tester plugged in, but make sure pins are not crossed and chip has proper orientation.  

5. Press button to run additional tests.   

Troubleshooting

Verify you have the correct voltages in these locations.   Incorrect or missing voltages can be caused by incorrect assembly.  Verify you don't have solder bridges, resistors in the wrong locations, chips installed backwards.





Schematic

