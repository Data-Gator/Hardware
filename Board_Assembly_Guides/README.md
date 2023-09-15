# Board Fabrication and Assembly Guide for Data Gators

All the information below is meant to guide _anybody_ through the process and various methods available for making your own Data Gator board. 

#### Table of Contents

| Link | Description |
| :---: | :---: | 
| [Overview](#overview)| Enumerates the basic steps for having a board manufactured and then assembling it. |
| [Terms and Definitions](#terms-and-definitions) | Terms used in these guides to describe the process of producing fully functional Data Gators. |
| [Fabrication](./PCB_Fabrication_Guide.md) | Guide with steps for ordering PCBs from several 3rd party fab houses. |
| [Assembly](./PCB_Assembly_Guide.md) | Guide for the process of assembling surface mount components. |
| [Through-Hole Assembly](./PCB_Through-hole_Guide.md) |  Guide for soldering through-hole components. |
| [Adding Final Boards and Enclosures](./Enclosure_Build_Guide.md) | Links and guide for assembling an enclosure for your Data Gator board. |

#### Overview

1. _**optional** modify [schematics and designs](https://github.com/Data-Gator/Hardware/tree/main/Hardware_Revisions)_
2. [Have PCBs Fabricated](#how-to-acquire-data-gator-pcbs)
3. [Assemble PCBs](#how-to-assemble-the-pcbs)

    * Apply solder paste.
    * Place components.
    * Use hot plate/reflow oven/soldering iron to solder components.
    * Check components for bridges with magnifying glass and rework with soldering iron to remove bridges.

4. Solder through-hole components.
5. Connect separate boards and make cables.

    * Add solar power manager
    * Add battery fuel gauge

6. _**optional** apply antenna mod for external antenna_

#### Terms and Definitions

A few terms are defined below to hopefully make this more readable for those with minimal prior experience. If you have questions and would like to see this guide expanded in some way, please create an issue for the repository and ask away!

| Term | Definition |
| :---: | :---: | 
| Fabrication | Refers to having a printed circuit board (PCB) manufactured without components, simply a layered board with vias and pads for components. Not something you should attempt yourself, this part of the process must be contracted through a third-party fab house. |
| Assembly | Refers to the process of installing components (surface mount and through-hole) on the PCB. Surface mount components often require more knowledge or special equipment to solder while through-hole components can usually be soldered with just a soldering iron and solder! This guide addresses some methods for those without the optimal equipment to get the job done with some simple and not too unusual tools that can be acquired cheaply. | 
| Reflow | Heating up solder to the point that it "flows" to form a solder joint between the component and the board pad. |


