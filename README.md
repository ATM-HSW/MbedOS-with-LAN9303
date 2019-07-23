# LAN9303 shield for NUCLEO-144 and Mbed OS

## Introduction

![BACnet/IP gateway board stack](/images/BACnetBoardStack.png)


## Hardware modification

The onboard Phy must be disabled. For this purpose, several solder bridges (0Ohm resistors) must be removed:
- from top: SB13
- from button: SB160, SB164, SB178, SB181, SB182, SB183

Snippets from the user manual UM1974 show the positions on top and bottom layer.

![board modification](/images/hardwaremodifications.png)

## Mbed OS integration

comming soon
