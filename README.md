# FlashForge Adventure 3 - Klipper + BTT SKR Mini E3 Upgrade

<p align="center">
  <a>
    <img src="[[https://raw.githubusercontent.com/VioSynthax/Adventurer-Voxel-Klipper/2.0-preview/images/klippventurer.svg](https://raw.githubusercontent.com/dJOS1475/FF_AD3_Klipper/main/PCB's/klippventurer.svg)](https://raw.githubusercontent.com/dJOS1475/FF_AD3_Klipper/main/PCB's/klippventurer.svg)" alt="Klippventurer logo" height="185">
  </a>
</p>

Warning: this Upgrade is a Major effort and is recomended for Advanced 3D Printer Users with some electronics skills only

3D Printed items will be shared via my Printables account soonish (just in final testing)

https://www.printables.com/social/171511-djos_1475/models


Required Components:
* BigTree Tech SKR Mini E3 v3
* BigTree Tech TFT-35 MZ LCD Screen (with NoTouch E3 Firmware installed)
* PCB's: AD3 HE and AD3 HE BreakOut Boards.
* E3D Revo 6 Hot End
* Good Quality Ribbon cable - ~1.5 meters
* 2x9 Pin IDC Cable Connectors and sockets
* 2x Molex, Micro-Fit 3.0, 43650, 2 Way, 1 Row, Right Angle PCB Headers
* Assorted JST-PH PCB Sockets and Cable Connectors
* 2x PCB Mount Screw Terminal Blocks eg CUI Devices TB004-508-02BE
* Printed Parts (Unreleased)


UPDATES:
31st March 2023 - Printer now calibrated and Printer.cfg has been updated.
30th March 2023 - Everything now works! 


Sensorless Homing in Action:
https://youtu.be/0Acrmv7VkdY

and Printing ASA:
https://youtu.be/akCvX6l-e6o


Klipper Features in use:
* Sensorless Homing
* Adaptive Purge
* Adaptive Mesh Levelling w/ BLTouch
* Auto-Load Filament using Filament Sensor
* Auto Unload Filament when run-out detected
* Unload macro for when you just want to change Filament types/colours etc
* Auto-Extraction Fan at the end of Print (via End G-Code)
* Working LED lighting

NOTE: The Stepper Motors on this machine are kinda junk, and above 1k acceleration, are prone to layer shifts. I recomend replacing them if higher accelerations are desired.
