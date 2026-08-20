
<div align="center">
<h1>SpeleoFox</h1><br>
  
A Speleology headlamp - engineered for the caves 

![KiCad](https://img.shields.io/badge/kicad-%2300578F.svg?style=for-the-badge&logo=kicad&logoColor=white) 
![AutoDesk](https://img.shields.io/badge/autodesk-%23000000.svg?style=for-the-badge&logo=autodesk&logoColor=white)
[![License: CERN-OHL-S](https://img.shields.io/badge/License-CERN--OHL--S%20v2-red)](https://ohwr.org/cern_ohl_s_v2)
<br>

<img src="https://github.com/mrk-fox/SpeleoFox/blob/main/img/general%20assembly.png" alt="Flowers" style="width:auto;">
<div align="left">v0.1</div>
</div>


SpeleoFox is a DIY helmet-mounted headlamp, designed for caving activities.

> [!WARNING]
> **Early hardware revision.** SpeleoFox has not been manufactured or tested yet. The board is currently waiting on funding before manufacturing.


## Preliminiaries 
Light in caves is more than just an "aid to see". Its a guarantee of surviviability and situation awareness, which results, when abscent, in fatal situations requiring specialised teams for rescue opertions. Caves are natuarally a hostile environment for humans, where moisture and rough, abrasive condition in movement force equipment to reach its limit. Therefore, already since the earliest XXth century, rugged caving and mining headlamps were basic equipment for cavers and miners. Since then LED's (Light Emitting Diodes) reached consumer market electronics making portable light sorces more efficient than ever before. Even though once basic eqipment of some countires 30% of poulation, caving and mining headlams are bound to a high price beginning from 250€. Therefore, this project aimed to create a simple and cheap, yet withstanding, piece of lighting equipment suitable for caving. 

## Features

- Simple, fail-proof electronics
- Modularity and ease of repare
- One led with two lighting modes to cover a variety of situations underground
- Waterproof case
- 2x 18650 Batteries (With protetion!) on the back side of the helmet

## PCB
The PCB features a AMS1117-2.5 controller for the LED intensity regulator and an AL8860 LED Regulator IC

<img src="https://github.com/mrk-fox/SpeleoFox/blob/main/img/Schematics.png" alt="Flowers" style="width:auto;">
<div align="left">PCB Schematic</div>


<img src="https://github.com/mrk-fox/SpeleoFox/blob/main/img/PCB.png" alt="Flowers" style="width:auto;">
<div align="left">PCB Layers</div>

## CAD

The main maxime while designing the CAD for this project was the goal to protect the electronics on the inside from the harsh conditions in the cave. The thorough documentation can be found in the JOURNAL.md file in this repository.
<img src="https://github.com/mrk-fox/SpeleoFox/blob/main/img/front_case_disassembled.png" alt="Flowers" style="width:auto;">
<div align="left">Front (Emitting) Part disassembled</div>

<img src="https://github.com/mrk-fox/SpeleoFox/blob/main/img/Bat_case_disassembled.png" alt="Flowers" style="width:auto;">
<div align="left">Backside (Battery) Part disassembled</div>

## Assembly

1. First, prepare the PCB by de-panelizing it and soldering all the components according to the BOM, Schematic and PCB Layer (Dont forget to connect the PCBs with a long enoug cable with each other)
2. Print the components in PETG
3. Thermalglue the Radiator to the backside of the LED PCB
4. Place the PCBs into the Printed components
5. Cut a piece of Plexiglass into place and drill holes at the right placec according to the printed part.
6. Use sealant to place the Lids/Plexi onto the 3d printed components after inserting the Batteries
7. Use sealant to seal the cable outlets
8. Screw the components togerther, wait till the sealant dries out and go caving!

## Happy Caving! Please be careful! I thank:
- HACK CLUB
- Kai the Jolly Guy
- Everyone who participated in the 48 hours hackathon!
