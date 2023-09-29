# MFD_3
![Image](https://github.com/godor2008/MFD_3/blob/master/MFD/Image/small_buttons.jpg)

This is MFCD board for JF-17 module used in DCS World. It is similar to Thrustmaster Cougar panel, but larger. Designed to be used with 9.7 inch monitor 4:3 1024x768
Designed in Altium Designer 20

Contains output files (Gerber) and elements list for production at https://jlcpcb.com/

Gerber zip archive https://github.com/godor2008/MFD_3/blob/master/MFD/Project%20Outputs%20for%20Mfd3/Project%20Outputs%20for%20Mfd3.zip
BOM https://github.com/godor2008/MFD_3/blob/master/MFD/Project%20Outputs%20for%20Mfd3/Bill%20of%20Materials-Mfd3.xlsx
Pick and Place file https://github.com/godor2008/MFD_3/blob/master/MFD/Project%20Outputs%20for%20Mfd3/Pick%20Place%20for%20Mfd3.csv

You may download these files and use them to order boards with SMT asssembly at https://jlcpcb.com/

Buttons you have to solder yourself.

Button used is 6*6 tactile switch with built-in LED. For example I used this https://www.aliexpress.com/item/32947533283.html
But you may find other similar buttons at alibaba.com or your local shop.
You may also add simple keycaps, for example I used this https://www.aliexpress.com/item/32918071718.html

Firmware is developed by FreeJoy https://github.com/FreeJoy-Team/FreeJoyWiki
Take a look at that project. 

Firmware may be downloaded here https://github.com/godor2008/MFD_3/blob/master/MFD/Firmware/FreeJoy_v1_6_2b3.hex

This is configuration file that contains mappings between physical and logical buttons. Should be uploaded through FreeJoy configurator after programming firmware.
https://github.com/godor2008/MFD_3/blob/master/MFD/Firmware/FreeJoyLeft.conf
