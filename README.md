# DASBOB

This is a modification of the DASBOB keyboard. I adapted the routing to work with nice!nanos and ZMK, and routed the outer terminals of the TRRS connector to the RAW and GND pins. This way you can use a stripped TRRS cable to connect the boards to the batteries.

![With Trackpad](https://github.com/nov1n/DASBOB/blob/main/pic/with-trackpad.png)
![Without Trackpad](https://github.com/nov1n/DASBOB/blob/main/pic/without-trackpad.png)


## Firmware
The routing matches that of the rae-dux keyboard. To configure this in ZMK please use this shield: https://github.com/andrewjrae/zmk-config/tree/development/config.

## Batteries and case
To find the wires of the stripped TRRS cable that connect to the RAW and GND pins it's easiest to use a multimeter in continuity mode. Hold one probe on the RAW pin, and the other on each of the wires in turn, until you hear a beep. Repeat for the GND pin. Then connect these wires to the positive and the negative terminals of your battery respectively.

An optional Magic Trackpad accommodates two 90x60x3mm 3000mAh lipo batteries. You can find the design here: (link: https://www.printables.com/model/460594-magic-trackpad-battery-case).
