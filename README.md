# CR10V2-BLtouch-Installation
Installation Instructions for the CR10 V2

## Overview & Bill of Materials

The CR10V2 is a great printer to upgrade because it is so easy. To complete it, you will need the following: 

1) BL Touch unit https://3dprintingcanada.com/products/genuine-antclabs-bltouch-sensor?_pos=2&_sid=605b91a36&_ss=r
2) XD-1000 extension cable https://3dprintingcanada.com/collections/antclabs/products/genuine-antclabs-bltouch-extension-cables-sm-xd-1000
3) One 3D printed BL touch mount: https://www.thingiverse.com/thing:3947349

## Firmware Flashing Guide

Uploading the firmware for the CR10V2 is straightforward. 

1) First, please download X-loader from the link below and save all the files in the repository to one folder: 
https://github.com/3d-printing-canada/Xloader

2) Plug your CR10V2 into your computer's USB port. Open Xloader. Select the following options:
a) Device: Mega(ATMEGA2560)
b) Com port: Your printers port (it will show up in the list as something like Com2, Com7, etc)
c) Baud Rate: 115200

Download the hex file from this repository. Load that into xLoader and flash the firmware. Viola! 

The source code for the hex file is stored in the folder. 

