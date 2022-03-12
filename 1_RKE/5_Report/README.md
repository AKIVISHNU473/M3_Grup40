# RKE (Remote Keyless Entry)

# 1. INTRODUCTION 

## 1.1 Description 

RKE (remote keyless entry) is an electronic access control system that may be operated from a distance. RKEs, which are commonly used to remotely lock or unlock doors, need the end user to perform an action that causes a physical or software key fob to send a radio signal to a receiver that controls an electronic lock. The action is usually performed by pressing a button on a physical fob. The RKE systems for cars can also be used to control the vehicle's ignition system, security alarm, horn, and lights, in addition to locking and unlocking the doors. RKEs can also be used to control access to specific areas of a building, such as garages. While RKE is not commonly used in buildings other than enterprises, it is used in some home automation and security systems.


## 1.2 Software Requirements

 * Cygwin : Cygwin is a POSIX-Compatible programming and runtime environment that runs natively on Microsoft Windows.
             Under Cygwin, source code designed for Unix-like operating systems may be compiled with minimal modification and executed.
 * STM32CUBEIDE : The STM32 is a family of microcontroller ICs based on the 32-bit RISC ARM Cortex-M33F, Cortex-M7F, Cortex-M4F, Cortex-M3, Cortex-M0+, and Cortex-M0 cores.
 
 
## 1.3 SWOT Analysis

![](https://github.com/AKIVISHNU473/M3_Grup40/blob/main/1_RKE/6_ImagesAndVideos/1SW.jpg)

## 1.4 5W's & 1H

![](https://github.com/AKIVISHNU473/M3_Grup40/blob/main/1_RKE/6_ImagesAndVideos/5W.jpg)


## 1.5 Requirements
## High Level Requirement

|ID  |DESCRIPTION                          |
|:---|:------------------------------------|
|HLR1|System shall be provided with wireless lock system | 
|HLR2|System shall be provided with wireless unlock system | 
|HLR3|System shall be provided with wireless alarm activation and deactivation system |
|HLR4|System shall be provided with light approach |


## Low  Level requirements 
|ID  |DESCRIPTION                                                                                      | 
|:---|:------------------------------------------------------------------------------------------------|
|LLR1|User shall press blue switch on for lock operation|
|LLR2|User shall press blue switch twice for unlock operation|
|LLR3|User shall press blue switch thrice for activation and deactivation of alarm |
|LLR4|User shall press blue switch four times for light approach operation |


## 1.6 Advantages

* It adds extra security for the car.
* We can have better access control(its handey)
* Easy for the usage and it also saves some time compared to the normal one.
    
## 1.7 Disadvantages

* There can be possibility of hackers to manpiulate.
* potential risk comes from the fact that your car’s engine won’t automatically switch off when you are out of range.
* As the technology increases it supports more Vulnerablility.

# 2. ARCHITECTURE

## STRUCTURAL DIAGRAM
### High Level Diagram
![Screenshot (238)](https://user-images.githubusercontent.com/98865009/157942705-bc551387-9b5c-4157-a9a7-5f9828b5ba7b.png)

### Low Level Diagram
![Screenshot (213)](https://user-images.githubusercontent.com/98865009/157795863-a1a36bb1-7ffc-4adb-92e0-691b0b2f5533.png)

## BEHAVIORAL DIAGRAM
### High Level Diagram
![Screenshot (236)](https://user-images.githubusercontent.com/98865009/157918005-8b0e6b78-c855-45fc-8ad5-ede5d197275a.png)

### Low Level Diagram
![Screenshot (217)](https://user-images.githubusercontent.com/98865009/157803936-650de818-f6e3-490b-af48-d713a87c073c.png)

## FLOW CHART

![Screenshot (240)](https://user-images.githubusercontent.com/98865009/157947576-47198e01-d3db-4c8e-9483-9198ef14c435.png)


# 3. TEST PLAN AND OUTPUT

## High Level Test Plan 

|TEST ID  |TEST CASE OBJECTIVE                       |    INPUT DATA                        |EXPECTED OUTPUT            |ACTUAL OUTPUT              |STATUS|
|:--------|:-----------------------------------------|:-------------------------------------|:--------------------------|:--------------------------|:-----|
|HLTP1    |For Car lock Function                     |User shall press the button once |Car locked            |Car locked              |PASS  |
|HLTP2    |For Car unlock Function                   |User shall press the button twice | Car unlocked          |Car unlocked          |PASS  |
|HLTP3     |For alarm activation/deactivation Function|User shall press the button thrice|Alarm activated/deactivated|Alarm activated/deactivated|PASS  |
|HLTP4     |For approach light Function               |User shall press the button four times|Light approach ON      |Light approach ON       |PASS  |


## Low Level Test Plan

|Test ID|	Description                 |Input	                         |Exp output                                                   |Actual Output                        |Status|
|:------|:----------------------------|:-------------------------------|:------------------------------------------------------------|:------------------------------------|:-----|
|LLR1	|Car lock  | 1 user button press |All LEDs will be ON  |All LEDs ON  |	PASS|
|LLR2  |Car unlock                   | 2 user button press  |All LEDs OFF|All LEDs OFF | PASS |
|LLR3	|Alarm activation/deactivation| 3 user button press|All LEDs ON Clockwise direction |All LEDs ON Clockwise direction |PASS|
|LLR4  |Approach light| 4 user button press|	All LEDs ON in Anticlockwise direction |All LEDs ON Anticlockwise direction | PASS |          


