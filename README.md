# FlashForge Adventure 3 - Klipper + BTT SKR Mini E3 Upgrade

<p align="center">
  <a>
    <img src="https://raw.githubusercontent.com/dJOS1475/FF_AD3_Klipper/main/PCB's/klippventurer.svg" alt="Klippventurer logo" height="185">
  </a>
</p>

Warning: this Upgrade is a Major effort and is recomended for Advanced 3D Printer Users with some electronics skills only. If you would like to keep your OEM mainboard and wiring, please see the Klippventure project by VioSynthax.

# 3D Printed items
are available via Printables:

https://www.printables.com/model/437968-flashforge-adventurer-3-klipper-revo-6-bltouch-btt


# Required Components:
* BigTree Tech SKR Mini E3 v3
* BigTree Tech TFT-35 MZ LCD Screen (with NoTouch E3 Firmware installed)
* PCB's: AD3 HE and AD3 HE BreakOut Boards.
* E3D Revo 6 Hot End
* Good Quality Ribbon cable - ~1.5 meters
* 2x9 Pin IDC Cable Connectors and sockets
* 2x Molex, Micro-Fit 3.0, 43650, 2 Way, 1 Row, Right Angle PCB Headers
* Assorted JST-PH PCB Sockets and Cable Connectors
* 2x PCB Mount Screw Terminal Blocks eg CUI Devices TB004-508-02BE
* 24v to 5v voltage converter eg "1PZ VAC-H15" to power your Raspberry Pi
* Printed Parts


# UPDATES:
* 12th April 2023 - fixed filament macros - please see the Filament_Sensor.cfg file for prerequisites  
* 2nd April 2023 - reduced max speed to 100mm/s - any higher results in layer shifts due to the temps getting too high for the stock stepper motors (at least while printing high tempmaterials like ASA)
* 1st April 2023 - Tweaks to max speed and driver current - the steppers don't seem to like travel speeds over 150mm/s without overheating and causing layer shifts
* 31st March 2023 - Printer now calibrated and Printer.cfg has been updated.
* 30th March 2023 - Everything now works! 

# Videos
FlashForge Adventurer 3 gets a new Brain, Hot-End and Klipper:
https://youtu.be/USZoIhBnA24

Sensorless Homing in Action:
https://youtu.be/0Acrmv7VkdY

and Printing ASA:
https://youtu.be/akCvX6l-e6o


# Klipper Features in use:
* Sensorless Homing
* Adaptive Purge
* Adaptive Mesh Levelling w/ BLTouch
* Auto-Load Filament using Filament Sensor
* Auto Unload Filament when run-out detected
* Unload macro for when you just want to change Filament types/colours etc
* Auto-Extraction Fan at the end of Print (via End G-Code)
* Working LED lighting

# NOTE: 
The factory belt tension on this printer is too loose to exceed 1k acceleration and 100mm/s print speeds. To rectify this you need to retension the X and Y axis belts properly (tight is good, but dont over do it). The Y axis is a PITA as it can only be fixed when the printer is fully disassembled. The Y belt is a continuous loop with no tension adjuster. So you'll need to cut out roughly 5mm from the belt and re-install it as snug as you can get it. I then used some "Selly's Power Grip" to ensure the belts dont jump out of the jaws holding them.

If you still have Y axis layer shifting, I recommend replacing the motor with a better quality unit.

