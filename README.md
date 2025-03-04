# AqualinkD Interface Pi-HAT

![alt text](images/v2.1_main.jpeg)

## What is it?

A Raspberry Pi HAT compatible with Raspberry Pi and similar SBCs
<br>
It is purpose built for use with AqualinkD and allows you to easily connect an SBC to the Aqualink Serial bus
<br>
https://github.com/sfeakes/AqualinkD

## Technical stuff

- Communication with the Pi happens over pins 8/10 for TX/RX
- The board can power itself and the connected Pi from the Aqualink Serial bus power.
- The board has the same footprint as a Raspberry Pi Zero but also works on full size Pi boards (Pi 3, 4, 5 etc.)

## Where can I get one?

I may offer premade boards in the future but for now:
<br>
You can use the files in the KiCAD/fabrication folder to have preassembled boards made at jlcpcb.com
<br>
You'll need to source a 40pin GPIO female header and a 3.50mm 4 position screw terminal and solder them on to complete the board.
<br>
Links to the connectors on AliExpress

- 40pin GPIO female header:
  <br>
  2x20P 2.54mm pitch
  <br>
  https://a.aliexpress.com/_mOcIEMF
  <br>
  ![alt text](images/gpio_small.jpeg)

- 4 position screw terminal:
  <br>
  3.50mm pitch vertical or right angle
  <br>
  https://a.aliexpress.com/_m0hhCc7
  <br>
  ![alt text](images/terminal_small.jpeg)

##

![alt text](images/v2.1_stack_top.jpeg)
![alt text](images/v2.1_stack_side.jpeg)
![alt text](images/v2.1_top.jpeg)
![alt text](images/v2.1_bottom.jpeg)
