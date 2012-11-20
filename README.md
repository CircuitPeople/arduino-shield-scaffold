arduino-shield-scaffold
=======================

Arduino Shield Scaffold (template) for PCB123, and eventually perhaps other PCB CAD systems too.There used to be atemplate in PCB123 for Arduino Shields. Since that's been removed (not sure why) I re-created one starting from Garret's EAGLE template posted on Macetech. To make the template in PCB123 I first exported gerber files from EAGLE. PCB123 can import gerbers, and that was the next step. Upon import the data was al there but the pad were done as polygons, which aren't super user-friendly and lack drill holes, so I took the time to convert them into real oblong pads. 

