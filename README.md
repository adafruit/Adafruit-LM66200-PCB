## Adafruit LM66200 Ideal Dual Diodes Breakout PCB

<a href="http://www.adafruit.com/products/5830"><img src="assets/5830-01.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit LM66200 Ideal Dual Diodes Breakout. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5830

### Description

Most projects these days have multiple power supplies: say a battery or DC wall plug or USB for multiple powering options. Juggling these to have seamless hot-swap while avoiding back-powering is always a bit of a challenge: you want to keep things small, cheap, low power and of course reduce as much voltage drop as possible.

The Adafruit LM66200 Dual Ideal Diode breakout is a cute solution to dual supplies: it has back-voltage protection, and two 'ideal' diodes with RdsOn of 40 milliohms, support for 2.5A continuous draw and a separate enable input and status output.

Sure you could DIY the circuitry with multiple transistors, but this is compact and easy to use! Simply connect the two 2~5V power supplies to Vin1 and Vin2, the higher of the two will appear on Vout. Disable the output completely by pulling the On/Enable pin high. Check the Status pin, if desired, to see whether Vin1 or Vin2 is the selected supply.

To make it bread-board friendly, we've placed it on a small PCB with 6 x 0.1" breakout pads. The chip and a 1 Megaohm enable-pulldown is soldered on top. We include a bit of header, some light soldering is required to attach the header - or use free wiring if you want to insert it directly into a circuit.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
