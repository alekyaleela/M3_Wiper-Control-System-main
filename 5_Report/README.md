
# WIPER CONTROL SYSTEM
## INTRODUCTION
over the past two decades, the automotive industry has aggressively researched ways to exploit modern computing and electronic advances in the development of safety, reliability, and entertainment technologies for vehicles. With drivers exposed to an ever increasing number of distractions, automatic rain-sensing wiper systems become an even more appealing feature, as they work to minimize the time the driver must take his/her hands off the wheel. Most traditional systems offer intermittent as well as variable speed operation. The traditional wiper system however requires driver constant attention in adjusting the wiper speed.

Traditional windshield wiper speed constantly varies according to time and vehicle’s speed. Because the manual adjustment of the wiper distracts driver's attention, which may be a direct cause accidents. This is review paper for automatic wiper in various method and also explain the basic skeleton for adjust speed of wiper automatically cording to the amount of water on the windshield and in addition with also in advance removal of moisture inside the car while raining.

Wiper is an essential component that used to wipe the raindrops or any water from the windscreen. Wipers are designed and made to clear the water from a windscreen. Most of cars have two wipers on the windscreen, one on the rear window and the other on each headlight. The wiper parts visible from outside the car are the rubber blade, the wiper arm holding the blade, a spring linkage, and parts of the wiper pivots. The wiper itself has about six parts called pressure points or claws that are small arms under the wiper


## OBJECTIVE

The aim of the project is to design a  wiper control system which automatically controls the wiper according to the rain fall of water.In large cities and industries where supply and distribution tanks are at a largedistance from water control station, it is very difficult situation to monitor the water.

   The main objective of this project is through ARM microcontroller to design a wiper control system. The project mainly insists on controlling the motion of wiper 
   based on frequency and time period (in seconds).

![wiper](https://user-images.githubusercontent.com/101463471/167909762-f1cebc39-2b23-4052-9f8e-4462c994e1bb.jpg)

# REQUIREMENTS

## SOFTWARE REQUIRMENTS:
- STM32CUBEIDE
- CYGWIN
- QEMU

## COMPONENTS USED IN PROJECT:

- STM32F407G-DISC1

STM32F407 series of microcontrollers are high-performance MCUs designed for medical, industrial and consumer applications. It is based on ARM Cortex-M4 and offers up to 168MHz. The STM32F407VGT6 is the onboard chip which comes in a 100-pin LQFP package.

The STM32F407G-DISC1 is a Discovery Kit allows users to easily develop applications with the STM32F407 high performance microcontrollers with ARM cortex-M4 32-bit core. It includes everything required either for beginners or for experienced users to get quickly started. Based on the STM32F407VGT6, it includes an ST-LINK/V2 or ST-LINK/V2-A embedded debug tool, two ST MEMS digital accelerometers, a digital microphone, one audio DAC with integrated class D speaker driver, LEDs and push buttons and an USB OTG micro-AB connector.
   
   
![stm32f4_discovery-550x550h](https://user-images.githubusercontent.com/101463471/168055114-fb6720ea-d64a-4d8a-bcfe-251745618ffc.jpg)

## 4'WS and 1H:

#### Who
All automobiles have wiper system and  The drive moves the two wiper arms at a certain angle across the windshield, providing a clear view for the driver and passenger while travelling.
 
#### What
The main purpose of the wiper system is to clean the windscreen sufficiently to provide suitable visibility at all times. In this project three LEDs are used to control the system.


#### When
Wipers are a small part of  any automobiles like cars,trains,truck and so on but they have a big impact on  driving and overall safety. They remove rain, snow, dirt, pollen, frost and other debris quickly. In this project when ignition system is turn on or off where the three LEDs turn on or off depending upon the frequency.
    
#### Where
Wipers system are used in automobiles.

#### How
This system has been  done by LED and Timer. 

## SWOT ANALYSIS:

### Strengths:
a) Growth in production of vehicles

b) Higher demand for luxury features

c) Automatic wiper control system

d) Less power consumption

e) Operating level is easy 
	
### Weakness:
a) May not be working at inclement weather

b) May not detect objects

c) It may also malfunction if components fail

d) Sometimes not working properly

e) High cost


### Opportunities:

a) The wiper serves to clean the windshield of the any automobile  at the front and rear. Wiper works by removing oil, dust, rainwater, and dirt that get stuck to the windshield.

b) Wipers detect moisture on the windshield and activate the wipers to help increase driver visibility.

c) Improve safety by decressing driver distraction.

### Threats:
a) Time interval may vary thereby it cause some problem on  wiper system.

b) Due to so much ice or snow on  windshield may cause the  wipers to get jammed and cause circuit overloading.

c) Accident may occur due to fault in wiper system.


## HIGH LEVEL REQUIREMENTS:

|RID       |DESCRIPTION	       |STATUS |
|----------|-------------------|-------|
|HLR1      |EMBEDDED C LANGUAGE   	   |IMPLEMENTED|
|HLR2      |OS WINDOWS         |IMPLEMENTED|
|HLR3      |	     STM32CUBEIDE   |IMPLEMENTED|
|HLR4      |  CYGWIN |IMPLEMENTED|
|HLR5      |QEMU	       |IMPLEMENTED|
|HLR6      |HARDDISK	       |IMPLEMENTED|
|HLR7      |RAM 4GB            |IMPLEMENTED|

## LOW LEVEL REQUIREMENTS:

|RID         |DESCRIPTION	 |STATUS|
|------------|------------------|-------|
| LLR1 | RED LED ON | IMPLEMENTED   |  
| LLR2 | BLUE LED FREQUENCY 1Hz |IMPLEMENTED |
| LLR3 | GREEN LED FREQUENCY 4Hz| IMPLEMENTED|
| LLR4 | ORANGE LED FREQUENCY 8Hz | IMPLEMENTED |
| LLR5 | RED LED OFF    |  IMPLEMENTED|

## BLOCK DIAGRAM
![Block_Diagram](https://user-images.githubusercontent.com/101463471/168140083-7d395fdd-9aba-4c25-a874-b89045f6eace.PNG)
## FLOW CHART
![Flow_Chart](https://user-images.githubusercontent.com/101463471/168140090-364962c4-b952-44e1-8eaa-5d75ad9e93c8.PNG)
## MECHANICAL DIAGRAM
![Mechanical_Diagram](https://user-images.githubusercontent.com/101463471/168140191-af343067-c2df-4eb6-85ad-64756f7aff62.PNG)
## SCHEMATIC DIAGRAM
![Schematic_Diagram](https://user-images.githubusercontent.com/101463471/168140099-3dc2aab5-0df3-4a95-b7d7-01cb5fcb0696.PNG)
## STATE DIAGRAM
![State_Diagram](https://user-images.githubusercontent.com/101463471/168140316-458d241d-fdc1-444b-b096-a0f445935398.PNG)

## TESTCASES
### HIGH LEVEL TEST PLAN:

|TEST ID      |DESCRIPTION	       |INPUT |  EXPECTED OUTPUT|
|----------|-------------------|-------|-----|
|HL01      |BUTTON PRESSED  |PRESSED 2 SECOND| EXECUTED |
|HL02      |BUTTON PRESSED  |PRESSED 1 SECOND|EXECUTED |
|HL03      |BUTTON PRESSED  |PRESSED 0.25 SECOND|EXECUTED |
|HL04      |BUTTON PRESSED	|PRESSED 0.125SECOND|EXECUTED |
|HL05      |BUTTON PRESSED	|PRESSED 2 SECOND|EXECUTED |


### LOW LEVEL TEST PLAN:

|TEST ID       |DESCRIPTION	    |INPUT| EXPECTED OUTPUT|
|------------|------------------|-------|------------|
|LL01      |BUTTON PRESSED |PRESSED 2 SECOND|  RED LED ON |
|LL02      |BUTTON PRESSED |PRESSED 1 SECOND| BLUE LED ON|
|LL03      |BUTTON PRESSED |PRESSED 0.25 SECOND|GREEN LED ON|
|LL04      |BUTTON PRESSED |PRESSED 0.125 SECOND|ORANGE LED ON|
|LL05      |BUTTON PRESSED |PRESSED 2 SECOND|RED LED OFF|

## OUTPUT IMAGES


## M3_WIPER-CONTROL-SYSTEM
|  FOLDER  | DESCRIPTION|
|----------|-----------|
|0_Abstract|Contains explanation of project|
|1_Requirements|Contains 4'WS & 1H , SWOT analysis and details of high level and low level requirements|
|2_Design|Contains Block diagram,Schematic diagram,Mechanical diagram, State diagram and Flow chart|
|3_Implementation|Contains Source code and  Simulation|
|4_Testcases|Contains testplan and procedures|
|5_Report|Contains overall details of project|
|6_Output   |Contains output images|

