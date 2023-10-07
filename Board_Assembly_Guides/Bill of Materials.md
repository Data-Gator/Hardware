# Bill Of Materials
## Surface Mount Devices (SMD)
This is a list of devices and quantities which should be purchased for building the Data Gator. PCB Fabrication companies may do the purchasing or use company stock.

| Name | Description | Quantity |Digikey/Mouser Part # | Link | 
| :---: | :---: | :---: | :---: | :---: | 
| Resistor | 0603 100kOhm| 11 || https://www.digikey.com/en/products/detail/walsin-technology-corporation/WR06X104-JTL/13241355 |
| Ceramic Capacitor |10uF| 2 || https://www.digikey.com/en/products/detail/samsung-electro-mechanics/CL32A106MOJNNNE/3888522 |
| Resistor | 0603 2kOhm| 3 || https://www.digikey.com/en/products/detail/yageo/RC0603FR-072KL/727009 | 
| Resistor | 0603 5kOhm| 2 || https://www.digikey.com/en/products/detail/yageo/RT0603BRE075KL/7708365 | 
| Resistor | 0603 4.7kOhm | 2 || https://www.digikey.com/en/products/detail/yageo/RC0603FR-074K7L/727212 | 
| Micro-SD Card Holder | 9 Position, Push-Push, Right Angle | 1 || https://www.digikey.com/en/products/detail/gct/MEM2051-00-195-00-A/10460360?s=N4IgTCBcDaILIFE5gAwFYCMIC6BfIA | 
| u.FL SMT| 50 Ohm | 1 || https://www.digikey.com/en/products/detail/hirose-electric-co-ltd/U-FL-R-SMT-1-40/4285474 | 
| DIP Switch | SPST, 2.54mm, 3 position |1 || https://www.digikey.com/en/products/detail/cui-devices/DS04-254-2-03BK-SMT/11310920 |
| ADS1015 (Analog-to-Digital Converter) | 12 bit, IDGST, 10VSSOP package| 1 || https://www.digikey.com/en/products/detail/texas-instruments/ADS1015IDGST/2174980 | 
| AP2171WG | IC Power Switch, P-Channel, SOT25 package|2|| https://www.digikey.com/en/products/detail/diodes-incorporated/AP2171WG-7/1964664 | 
| TPL5000| Watch Dog Timer, 10VSSOP package|1|| https://www.digikey.com/en/products/detail/texas-instruments/TPL5000DGST/4331549 | 
| Red LED | 1206, 20mA, 1.7V|3|| https://www.mouser.com/ProductDetail/Stanley-Electric/BR1101W-TR?qs=byeeYqUIh0Pp62ktTXSSvA%3D%3D |
| Ceramic Capacitor | 0603, 0.1uF|4|| https://www.mouser.com/ProductDetail/KEMET/C0603C104K5RAC3121?qs=oBCMsStVSxe1EkGyoyETtg%3D%3D |
# Through-Hole Components
These components, as well as the daughter boards, must be soldered or attached to the Data Gator.

| Name | Description | Quantity | Digikey/Mouser Part # | Link | 
| :---: | :---: | :---: | :---: | :---:|
| WDT Switch | SPDT slide switch, 1.4mm | 1 || https://www.digikey.com/en/products/detail/cui-devices/MSS-102568-14A-90-D/13978973?s=N4IgTCBcDaILIGUEFoCMAGMBWAbADjQBYBBZATnWQBEQBdAXyA |
| 6-pin header| 6 pin header, 2.54mm pitch | 1 || https://www.digikey.com/en/products/detail/adam-tech/PH1-06-UA/9830394 | 

# Daughter Boards

| Name | Description | Quantity | Digikey/Mouser Part # | Link | 
| :---: | :---: | :---: | :---: | :---: |
| Firebeetle3 ESP32-E | Espressif ESP-WROOM-32E based micro-controller board with USB interface and GPIO accessible through castellated vias. |1| | https://www.dfrobot.com/product-2195.html |
| Adafruit MAX17048 Fuel Gauge | LiPoly / LiIon Battery Monitor/Fuel Gauge |1| | https://www.adafruit.com/product/5580 | 
| DFRobot Solar Power Manager 5V | Manages solar charging for 5V LiPoly batteries. | 1| | https://www.dfrobot.com/product-1712.html |


# Connectors
Connectors must be soldered by hand since they are through-hole components. These are used to connect analog and I2C sensors to the board. Both sensor options are viable and represent two different price points. Buying 15 sets of connectors in February 2023, JST connectors cost $67 dollars total while Molex connectors cost $125.
### Molex Connectors
The premium option, likely more resistant to  physical damage and support more force if sensor wires get  pulled.

| Item | Quantity | Link | 
| :---: | :---: | :---: |
| 2 Pin Housing Receptacle, 2.5mm | 1 | https://www.digikey.com/en/products/detail/molex/0511030200/2405316
| 3 Pin Housing Receptacle, 2.5mm| 4 | https://www.digikey.com/en/products/detail/molex/0511030300/2405314
| 4 Pin Housing Receptacle, 2.5mm | 4| https://www.digikey.com/en/products/detail/molex/0511030400/2405335
| Socket Contact, 22-28 AWG Crimp | 30 | https://www.digikey.com/en/products/detail/molex/0503518000/2404938
| 2 Pin Connector Header, 2.5mm | 1 | https://www.digikey.com/en/products/detail/molex/0533750210/2405348
| 3 Pin Connector Header, 2.5mm | 4 | https://www.digikey.com/en/products/detail/molex/0533750310/3263194
| 4 Pin Connector Header, 2.5mm | 4 | https://www.digikey.com/en/products/detail/molex/0533750410/2421210

### JST Connectors

Cheaper than Molex connectors and functionally equivalent. The connection made is looser and may be more prone to failure under physical stress such as pulling.

| Item | Quantity | Link | 
| :---: | :---: | :---: | 
| 2 Pin Connector Header, 2.5mm| 1 | https://www.digikey.com/en/products/detail/jst-sales-america-inc/B02B-XASK-1-LF-SN/1634730
| 3 Pin Connector Header, 2.5mm | 4 | https://www.digikey.com/en/products/detail/jst-sales-america-inc/B03B-XASK-1-LF-SN/1634731
| 4 Pin Connector Header, 2.5mm | 4 | https://www.digikey.com/en/products/detail/jst-sales-america-inc/B04B-XASK-1-LF-SN/1634735
| Socket Contact, 22-28 AWG Crimp | 30 | https://www.digikey.com/en/products/detail/jst-sales-america-inc/SXA-001T-P0-6/923775
| 2 Pin Connector Header, 2.5mm | 1 | https://www.digikey.com/en/products/detail/jst-sales-america-inc/XAP-02V-1/923774
| 3 Pin Housing Receptacle, 2.5mm | 4 | https://www.digikey.com/en/products/detail/jst-sales-america-inc/XARP-03V/7423921
| 4 Pin Housing Receptacle, 2.5mm | 4 | https://www.digikey.com/en/products/detail/jst-sales-america-inc/XAP-04V-1/959010