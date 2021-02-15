# Introduction
The RFM69HCW module integrated with a Atmega328PB microcontroller to run RF programs. This will potentially be used for future students of COMPSYS301 course at The University of Auckland. [Here is a glimpse of the Pacman robot used in the course](https://www.youtube.com/watch?v=HsrKt_Cxeg4). The robot uses RF as well as light sensors to navigate paths. This is the Slave Module that sits on the robot. The video only shows one way communication. This new design ensures two way communication will be possible in the future. 

## Tools
Made on EasyEDA. Exported for Altium and EasyEDA

## Code Libraries for RFM69HCW
[LowPowerLab](https://github.com/LowPowerLab/RFM69)  
[RadioHead](https://www.airspayce.com/mikem/arduino/RadioHead/classRH__RF69.html)

## Power and IO
1) ISP Programming Interface for Atmega328PB.
2) Serial Port (TX/RX) for programming using FTDI cables and using print statements from external devices.
3) SPI Probe Area for debugging using Digital Probes.
4) 5V dedicated Power port. 3.3V Voltage Regulator and Logic Level Translators for system.
5) Reset Switch to reset processor or upload programs using FTDI Cables.

## Example Application
[Garage Home Automation](https://lowpowerlab.com/guide/garagemote/)  
[IoT Home Automation](https://lowpowerlab.com/guide/gateway/)

## Files Included
1) Schematics and PCB docs for Altium and EasyEDA.
2) Gerber Files for manufacturers.
3) PDFs of schematic, bottom and top layer for easy viewing.
