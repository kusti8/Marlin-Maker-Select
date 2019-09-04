# Marlin 3D Printer Firmware for Monoprice Maker Select V2 (Wanhao Duplicator i3)
**Please use the 1.1.x branch as that is the only branch I'm modifying in this fork.**
## Changes in this Marlin fork
Branch 1.1.x has been reset to tag 1.1.8 and configuration.h has been modified from a configuration.h found here: https://reprap.org/forum/read.php?415,809741
## Special Instructions
When compiling this firmware the only error I encountered was around u8glib missing. I resolved this in the arduino (1.8.7) IDE by going to "tools -> manage libraries" and installing U8glib by Oliver Version 1.19.1
## Warnings
Please use this at your own risk. I accept no responsibility for the modifications posted here. This configuration compiles and works for my stock Monoprice Maker Select V2 on the original Melzi board but I have likely not tested all scenarios and modifying your firmware will void your warranty and can potentially damage your printer.
## Additional Info
Before installing this firmware I burned a bootloader on my melzi board using an Arduino Uno clone (found here: http://a.co/d/iCYILT7) and the instructions from a Youtube video here: https://youtu.be/ejpSniiJejI until about the 6:45 mark. The rest of the instructions on that video are around updating the Repetier firmware which I couldn't get the latest versions to fit on the small Melzi board so I switched to Marlin and here we are.