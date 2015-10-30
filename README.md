# fleetwood-mega
Eagle files for Version 2 of Fleetwood hardware.

See photo of prototype of faceplate

- This project is not ready for production
- The board is based on Freetronics EtherMegaR3 (https://github.com/freetronics/EtherMega)
- Spec as per EtherMega with following changes
 - **Inclusion of 7 LED tactile switches, a click rotary encoder, and OLED display, for controlling home automation hub by MQTT**
 - Change form factor to better fit a double wall socket back box - dry lining box and metal back box
 - Removal of SD card to save space
 - Removal of USB to serial to save space (use external FTDI or TFTP upload of sketch to bootloader)
 - Built-in support for DIY PoE *or* 802.3af PoE (either one - not yet decided)
 - Ethernet jack moved away from side of board to allow more space for cable / plug insertion in wall box
