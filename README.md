# bms
Project BMS (Battery Managment System) based on Texas Instruments Applicattion note [TIDA-00792](https://www.ti.com/tool/TIDA-00792).
THe design was developed during my lessons on **_Introduction to Printed Circuit Board Design_**. 

## Overview 

The BMS is a design thought for a battery supplied product where is needed some management on battery is needed to extend its life. The whole solution it's mainly implemented with parts from the same manufacturer integrated as individual modules. 

You can check more specifics details on the [PCB report](https://github.com/TobiasBp99/bms/blob/master/reportBMS.pdf).

## Features 

- Wide voltage range up to 48V
- CAN BUS to communicate with other potential modules
- Cell voltage measure
- Pack current measure
- Temperature measure
- Cell balancing
- SOH/SOC measure
- 12 to 15 cells easily adaptable

## 3D Model
- ![#f03c15](https://placehold.co/15x15/ffff00/ffff00.png) `Analog Front End`
- ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) `Gauge`
- ![#1589F0](https://placehold.co/15x15/f03c15/f03c15.png) `FET'S`
- ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) `Embedded System `
![placement](https://github.com/TobiasBp99/bms/blob/master/images/MODULES.png)
![top-plane](https://github.com/TobiasBp99/bms/blob/master/images/TL3D.png)
![top-perspective](https://github.com/TobiasBp99/bms/blob/master/images/TL23D.png)

