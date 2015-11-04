# fleetwood-mega
Eagle files for Version 2 of Fleetwood hardware.

Hi reader! The PCB in this project is not ready for production. Parts have not been finalised, traces not yet routed. It's a work in progress.

Latest YouTube project update here: https://www.youtube.com/watch?v=HE-3FGcSKfI
YouTube channel generally full of my MQTT ramblings here: https://www.youtube.com/user/hazymat

Do take a look at the photo of Fleetwood's first prototype installed in the home, included in the repo.

- This project is not ready for production
- The board is based on Freetronics EtherMegaR3 (https://github.com/freetronics/EtherMega)
- Spec as per EtherMega with following changes
 - **Inclusion of 7 LED tactile switches, a click rotary encoder, and OLED display, for controlling home automation hub by MQTT**
 - Change form factor to better fit a double wall socket back box - dry lining box and metal back box
 - Removal of SD card to save space
 - Removal of USB to serial to save space (use external FTDI or TFTP upload of sketch to bootloader)
 - Built-in support for either DIY PoE or 802.3af PoE - as per original EtherMega
 - Ethernet jack moved away from side of board to allow more space for cable / plug insertion in wall box

# LICENCE
This work is licensed under the
Creative Commons Attribution-Share Alike License.  
To view a copy of this license, visit

  http://creativecommons.org/licenses/by-sa/3.0/  
  http://creativecommons.org/licenses/by-sa/3.0/legalcode

or send a letter to

  Creative Commons  
  171 Second Street, Suite 300  
  San Francisco  
  California, 94105  
  USA

The "license" folder within this repository also contains copies of the
licences referenced above.

# CREDITS
The EtherMega was designed by Marc Alexander (marc@freetronics.com) and
Jonathan Oxer (jon@freetronics.com) based on previous work by the Arduino
team (www.arduino.cc/playground/Main/People) which includes:

 * Massimo Banzi
 * David Cuartielles
 * Tom Igoe
 * Gianluca Martino
 * David A. Mellis
