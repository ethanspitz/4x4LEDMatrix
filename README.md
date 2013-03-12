4x4LEDMatrix
============

4x4 LED Matrix uses ATTINY85 with three 74-595s each with their own serial in from the ATTINY85. One used for ground connections on the matrix, two used for anode connections for controlling color. BS270 N-Channel Mosfets used for draining current on each row.

###Plans on adding:
* Power Connection
* Voltage Regulator
* Connection for daisy chaining multiple boards???
* Switch for disabling light output
* Code

###Bugs to be fixed:
* Overlaping pads on every LED
* VCC/GND on 74595s
