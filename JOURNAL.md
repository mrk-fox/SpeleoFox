# Journal SpeleoFox

## Day 1

Today, primarily the following tasks were set and created: 

1. Define the goals of the Project
2. Define the basic architecture to achieve these goals
3. Refine these into a schematic strictly following the manufacturers datasheets
4. Refine the sheet into a ready PCB
5. Plan the Case and the features making it watertight.

For the first point, I decided to make a watertight, speleology grade headlamp mounting on my Edelrid helmet.

As the design is supped to function in caves, i decided to use a simplified approach feturing one CREE LED with an analouge controller instead of a multi LED ATtiny1616 controlled approach. 

At the end, this goal was approached by using a AMS1117-2.5 with a switch routing the current thorugh a 10kOhm volatage divider. The lamp was also deactivated with the AL8860 LED controlling IC. 

The PCB turned out to be a one-piece 3 component panel with a place for a heatsink on the backside to boost the power and supress overheat. 

https://github.com/mrk-fox/SpeleoFox/blob/main/img/PCB.png

The day took 13 hours building in total.



## Day 2

After the PCB was designed, the CAD part was the main focus of finishing the project. A bottom-sealed, screwed Plex lid was the main design idea for the front part, making the glass interchangable and the LEDs light dissipation unhindered. Also, the backside battery containter was designed in a similar way, both modues situated on a 30 mm wide, 3mm thick stainless mount screwed to the helmet. Also, the cable system featured a up to 6mm thick cable for enough isolation to prevent cable damage due to abrasion. The cable gets sealed to the body with my special sealant from Germany. 

Also, 3D printing isn't itself watertight. Therefore, I decided to design the case keeping an epoxidation in mind.

In the end, the final product featured a full, two-component assembly with a brim ring simulating the helmet and a cable as the connection between these two modules.

Total time spendings: 6 hours.



Final journal entry: I spent another 2 hours documenting my work thoroughly.