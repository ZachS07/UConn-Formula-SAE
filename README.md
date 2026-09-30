# UConn Formula SAE

An overview of my work in the EV section of UConn Formula SAE, a top-5 FSAE team.

![UConn Formula SAE EV Team](FSAE.jpg)

## What I'm Working On

As a new member of the team, my project is to help design and build a custom low-voltage battery pack for our EV.

The pack will be around 24V and 10Ah and will power the lower-voltage electronics on the car, like the BMS, dashboard, sensors, and pumps.

I'm working with two others on the full design process, including figuring out how many battery cells we need, how they should be connected, what protection the pack needs, and how we're going to monitor the individual cells.

This project also includes designing a BMS PCB in Altium around the LTC6811. The BMS will keep track of the cells, balance their voltages, and help protect the battery pack. It will also include a UART-to-CAN for communication with other parts of the car.

![LV Battery Pack CAD](LVBP_Onshape.png)

This CAD model shows a possible layout for the LV battery pack. The pack is modeled to scale around Molicel P50B cells, each measuring approximately **21.55 mm in diameter and 70.15 mm in height**, to help visualize cell spacing and overall pack dimensions.

I'll be updating this repo as the project progresses with my calculations, design decisions, schematics, PCB work, and eventually the finished pack.
