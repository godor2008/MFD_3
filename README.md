# MFD_3
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/MFD/Image/small_buttons.jpg)

This is MFCD board for JF-17 module used in DCS World. It is similar to Thrustmaster Cougar panel, but larger. Designed to be used with 9.7 inch monitor 4:3 1024x768
Designed in Altium Designer 20

Contains output files (Gerber) and elements list for production at https://jlcpcb.com/

[Gerber zip archive](https://github.com/godor2008/MFD_3/blob/small_buttons/MFD/Project%20Outputs%20for%20Mfd3/Project%20Outputs%20for%20Mfd3.zip)
---------------
[BOM](https://github.com/godor2008/MFD_3/blob/small_buttons/MFD/Project%20Outputs%20for%20Mfd3/Bill%20of%20Materials-Mfd3.xlsx)
-------------
[Pick and Place file](https://github.com/godor2008/MFD_3/blob/small_buttons/MFD/Project%20Outputs%20for%20Mfd3/Pick%20Place%20for%20Mfd3.csv)
-----------
You may download these files and use them to order boards with SMT asssembly at https://jlcpcb.com/

Buttons you have to solder yourself.

Button used is 6*6 tactile switch with built-in LED. For example I used this https://www.aliexpress.com/item/32947533283.html
But you may find other similar buttons at alibaba.com or your local shop.
You may also add simple keycaps, for example I used this https://www.aliexpress.com/item/32918071718.html

Firmware is developed by FreeJoy https://github.com/FreeJoy-Team/FreeJoyWiki
Take a look at that project. 

Firmware may be downloaded [here](https://github.com/godor2008/MFD_3/blob/small_buttons/MFD/Firmware/FreeJoy_v1_7_1b3.hex)

This is [configuration](https://github.com/godor2008/MFD_3/blob/small_buttons/MFD/Firmware/new_FreeJoyLeft.cfg) file that contains mappings between physical and logical buttons. Should be uploaded through FreeJoy configurator after programming firmware.

Additionally you'll need to order:
Tiny [HDMI](https://vi.aliexpress.com/item/33057698628.html) 10 cm cable for extension inside case. Order 2 A1 connectors and 10cm cable
![image](https://github.com/godor2008/MFD_3/assets/1040630/173b196d-916a-4216-9e6a-b11b741dd1af)

[XH 2.54 20 cm cables](https://vi.aliexpress.com/item/1005002160765607.html) for usb extension. Order 1 pack of each color

[XH 2.54 4 pin angled connectors set](https://vi.aliexpress.com/item/4000029752260.html) for usb extension. You need only two of them, so order minimal pack you can
![image](https://github.com/godor2008/MFD_3/assets/1040630/b1e457af-7536-40e4-b954-ec63185189ee)

[Usb Connector B Type vertical](https://vi.aliexpress.com/item/32947971157.html)
![image](https://github.com/godor2008/MFD_3/assets/1040630/5e891ae7-79d2-415f-b64a-cc2c8a94e054)





# Some assembly process:

![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/1.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/2.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/3.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/4.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/5.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/6.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/7.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/8.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/9.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/10.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/11.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/12.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/13.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/14.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/15.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/16.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/17.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/18.jpg)
![Image](https://github.com/godor2008/MFD_3/blob/small_buttons/Images/19.jpg)

# HDMI board
Solder **HDMI 47659-1102 Molex** connector and **FFC/FPC 20pin 0.5mm** connector to board. Use board P16. You may use any from the set depending on your prefferable connectors.
![20240318_194333](https://github.com/godor2008/MFD_3/assets/1040630/582cd13c-38ed-4669-8924-e5e7b32522d2)

Then prepare:
2 **M3 nylon locking nuts** and 2 **M3 Threaded Hex Brass Male Female Standoff 7mm**
![20240320_214720](https://github.com/godor2008/MFD_3/assets/1040630/60fbdf5e-7507-4745-a043-6cb139f78a28)

And assemble it:
![20240320_212444](https://github.com/godor2008/MFD_3/assets/1040630/1f68242c-530f-41b7-8fcf-dabf474bb29f)

# USB board
Solder **USB-B vertical** and **XH 2.54 4 pin angled connector**
![20240321_152739](https://github.com/godor2008/MFD_3/assets/1040630/5c45d0c7-f344-4b79-99db-3cd2aa12b416)

Then prepare:
2 **M3 nylon locking nuts**, 2 **M3 Threaded Hex Brass Male Female Standoff 14mm**, 2 **M3 washer**. Washers are needed to perfectly match height of USB connector
![20240321_182308](https://github.com/godor2008/MFD_3/assets/1040630/5d29f562-a5be-439b-88ac-effe5a7af415)

And assemble it:
![20240321_183423](https://github.com/godor2008/MFD_3/assets/1040630/f98754e9-0c6b-4986-bb7f-086a589858ac)



