# BOM - Bill of materials  

> [!NOTE]
> All items marked with * are optional. JST or header connectors can be substituted by soldering the wires directly to the board or ESP.

> [!TIP]
> JST- XH 2.54mm are the recommended connector type for the connectors because they are keyed and you can't connect them the wrong way.
> Simple header pins work fine too, but make sure to orient the plug correctly. 
> JSTs can be bought as kit with wire and crimper. 
> Connectors are preferred over soldering directly to the board for serviceability.

## 3 weapon scoring device

| Number of pieces | Designator | Description | Value | Size | Remarks |
| --- | --- | --- | --- | --- | --- |
| 1* | | PCB |Rev 1.2b|| alternatively you could build the circuit on a breadboard or perfboard|
| 1 | U1 | ESP32 DevKit V1 |  |  |  be sure to get the **30 pin** version (2 x 15). There are many board flavors out there e.g. V4 is 38 pin |
| 2 |  | 64 LED matrix panel | WS2812B-64 led matrix | 65mm x 65mm | |
| 1* |  | MAX7219 Dot matrix Module 4-in-1 LED Display module | | | |
| 2 | C1,C3 | radial electrolytic capacitor | 470µF - 35V | Ø10mm - 5mm pitch |   |
| 2 | C2,C4 | polyester film capacitor | 0,1µF | L7,3 x W2,5mm | |
| 2 | Q1,Q2 | BC337 NPN transistor | 0,8A 45V | TO-92 | | |
| 5 | R1,R2,R3,R4,R5 | metal film resistor | 470Ω 1% | 1/4W | |
| 2 | R6,R7 | metal film resistor | 33Ω 1% | 1/4W | |
| 1 | R8 | metal film resistor | 3,3kΩ 1% | 1/4W | |
| 1 | R9 | metal film resistor | 2,2kΩ 1% | 1/4W | |
| 1 | R10 | metal film resistor | 150Ω 1% | 1/4W | |
| 1* | R11 | metal film resistor | 0Ω bridge | 1/4W | can be substituted by a simple wire bridge |
| 7 |  | female banana jack | | 4mm, panel mount | |
| 1 | R12 | metal film resistor | 10kΩ 1% | 1/4W | |
| 1* | J1 | JST connector | 1 x 7 | 2,54mm pitch | |
| 1* | J2 | JST connector | 1 x 3 | 2,54mm pitch | |
| 1* | J3 | JST connector | 1 x 5 | 2,54mm pitch | |
| 2* | J8,J9 | JST connector | 1 x 2 | 2,54mm pitch | populate as required|
| 2* |  | pin strip, socket (female) | 1 x 15 | 2,54mm pitch | header for the ESP32 board |
| 1* | Q3 | power mosfet| FQP27P06 | TO-220 | reverse voltage protection, strongly recommended if you power externally via J9 |
| 1* | J4 | Right angle 2,54mm socket| | 6-pin | for plug-in connection of a HC-06 BT module |




## Weapons / body wire tester

| Number of pieces | Designator | Description | Value | Size | Remarks |
| --- | --- | --- | --- | --- | --- |
| 1* | | PCB |Rev 1.2b|| alternatively you could build the circuit on a breadboard or perfboard|
| 1 | U1 | ESP32 DevKit V1 |   |   |  be sure to get the **30 pin** version (2 x 15). There are many board flavors out there e.g. V4 is 38 pin |
| 1 |  | 25 LED matrix panel | WS2812B-25 led matrix | 38mm x 38mm | |
| 2 | C1,C3 | radial electrolytic capacitor | 470µF - 35V | Ø10mm - 5mm pitch |   |
| 2 | C2,C4 | polyester film capacitor | 0,1µF | L7,3 x W2,5mm | |
| 5 | R1,R2,R3,R4,R5 | metal film resistor | **47Ω 1%** | 1/4W | These resistors are marked 470Ω* on the silkscreen |
| 2 | R6,R7 | metal film resistor | 33Ω 1% | 1/4W | |
| 7 |  | female banana jack | | 4mm, panel mount | |
| 1* | J1 | JST connector | 1 x 7 | 2,54mm pitch | |
| 1* | J2 | JST connector | 1 x 3 | 2,54mm pitch | |


