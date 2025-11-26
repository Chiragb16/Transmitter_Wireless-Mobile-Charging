Wireless Power Transmitter
Overview:
A compact wireless power transmitter circuit using a 555 timer, NPN transistor, IRF540N MOSFET, and a resonant LC tank. Supplies wireless energy for simple charging and demonstration purposes.

How It Works:

12V input gets regulated to 5V with the L7805.

The 555 timer creates a square wave signal.

Signal is amplified and switches the MOSFET, driving the coil (L1).

The coil and capacitor (LC tank) transmit power wirelessly.

Setup:

Connect power, components, and coil as per the schematic.

Supply 12V DC to the input.

Place receiver coil nearby for wireless energy transfer.

Main Parts:

L7805 regulator (TO-220)

NE555 or compatible timer

BC547(Or Some other) NPN transistor

IRF540N MOSFET

180uH coil & 0.1uF capacitor

