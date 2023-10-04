# PCB Assembly Guide for Data Gators
Read on for instructions for how to assemble an Data Gator board and example pictures of the finished product.

##### Prerequisites
1. Should have DG PCBs. Instructions for getting boards in [[PCB_Fabrication_Guide|PCB Fabrication Guide]].
2. All surface mount components should be installed.
3. All through-hole components from the [[Bill of Materials]].
4. Have all tools or alternatives listed in the [[PCB_Assembly_Guide#Equipment]]

## Equipment

> [!note] 
> The following equipment is recommended for this project, but no specific brands/varieties are required. Example products are linked for quick reference.

| Item | Description | Example Link |
| :---: | :---: | :---: | 
| Soldering Iron | Need a soldering iron with a moderately small tip. | [soldering iron search on adafruit](https://www.adafruit.com/search?q=soldering+iron) |
| Solder | Any solder wire will do, but thickness around **0.8mm or less** is recommended. | [solder wire options](https://www.amazon.com/s?k=lead+free+solder&crid=3V2S2SCWR1CZC&sprefix=lead+freesolder%2Caps%2C126&ref=nb_sb_noss_2) 
| Solder Wick (optional) | Solder wick is a fallback option when things go wrong. Even if you don't need it now, you likely will later. | [solder wick](https://www.amazon.com/s?k=solder+wick&crid=VG3VQ2B8YPI8&sprefix=solder+wick%2Caps%2C141&ref=nb_sb_noss_1) 
| Solder Pump (optional) | Like solder wick, this is essential for fixing mistakes and clearing solder out of through holes and vias. | [solder pump - kotto](https://www.amazon.com/Solder-Sucker-Desoldering-Removal-Soldering/dp/B08FDY2SGS/ref=sr_1_4?crid=35M8KM142W5KO&keywords=solder+pump+engineer&qid=1696452063&sprefix=solder+pump+enginee%2Caps%2C130&sr=8-4), [solder pump - engineer](https://www.amazon.com/Engineer-SS-02-Solder-Sucker/dp/B002MJMXD4/ref=sr_1_2?crid=35M8KM142W5KO&keywords=solder+pump+engineer&qid=1696452063&sprefix=solder+pump+enginee%2Caps%2C130&sr=8-2)
| Tweezers | Good for holding small components while soldering to save your fingers. | [ifixit tweezers set](https://www.amazon.com/iFixit-Precision-Tweezers-Set-Angled/dp/B079K874CQ/ref=sr_1_7?crid=1QVIWPOS4CD8A&keywords=tweezers+electronics&qid=1696452163&sprefix=tweezers+electonric%2Caps%2C133&sr=8-7)
| Flush Cutters | Good for rework and clean up. | [hakko flush cutters](https://www.amazon.com/Hakko-CHP-170-Micro-Cutter/dp/B00FZPDG1K/ref=sr_1_5?crid=1Z6G64RAP3LXY&keywords=flush+cutters&qid=1696452212&sprefix=flush+cutter%2Caps%2C139&sr=8-5)
| Third Hand and/or Vice (optional) | Something to hold your work is not mandatory - necessity is the mother of invention after all - but this may save you significant head ache. | [helping hands - kotto](https://www.amazon.com/Helping-Soldering-Workshop-Non-slip-Weighted/dp/B07MDKXNPC/ref=sr_1_13?crid=3BENPZOE8VNSP&keywords=third+hand+soldering&qid=1696455855&sprefix=third+hand+soldering%2Caps%2C140&sr=8-13)


## Instructions

1. Solder Firebeetle ESP32 micro-controller (uC) to PCB.

	![pcb with firebeetle](pcb_w_firebeetle.jpg)

> [!note] Tips for Alignment
> It can be difficult to align the micro-controller board with the PCB pads for soldering and keep them aligned. To avoid misalignment, use the pin headers included with the micro-controller to align holes by placing the micro-controller on the PCB, aligning with holes, then placing the pin header through the holes. You can then solder the first and last hole of a side to keep the board in place, remove the pin header, and finish soldering both sides.

2. Solder switch to PCB. 
	![soldered switch](soldered_switch.jpg)

3. Solder Fuel Guage to PCB.

	![soldered switch](soldered_switch.jpg)

4. Solder analog and I2C plugs.

> [!note] 
> **Removing Alignment Pin**
> The plugs may come with an alignment pin on the bottom of the plug as can be seen in the picture below. Since the PCB has no alignment hole, this pin must be removed using a pair of flush cutters before soldering.
> ![three pin](three_pin.jpg)

![pcb populated](images/pcb_populated.jpg)

5. Attach Solar Manager with M3 bolts.
6. Make battery/charging cable using instructions from [[crimping guide]].