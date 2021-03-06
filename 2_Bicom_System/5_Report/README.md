 # BICOM SYSTEM
 
 ##  Description 

This is the extension of the Remote Keyless Entry,as it is operated in single directional This Bicom system is operated in bi directional way. This project gives the information of the qualities of the car like Window status and Alarm status,car battery info.


##  Requirements
## High Level Requirements
|ID  |DESCRIPTION	STATUS                                   |
|:---|:----------------------------------------------------|
|HLR1|The application shall display Window status          |
|HLR2|The application shall display alarm status           |
|HLR3|The application shall display car battery info status|
|HLR4|The application shall display Door status            |




## Low Level Requirements
|ID  |DESCRIPTION	STATUS                                                               |
|:---|:--------------------------------------------------------------------------------|
|LLR1|For displaying window status, user need to press the button one time             |
|LLR2|For displaying alarm status , user need to press the button two time             |
|LLR3|For displaying car battery info status, user need to press the button three time |
|LLR4|For displaying Door status, user need to press the button four time              |


## 5W's & 1H

![](https://github.com/KeerthuMG/M3_Group40/blob/main/2_BiCom%20System/6_ImagesAndVideos/2SW.jpg)

##  Swot Analysis 

![](https://github.com/AKIVISHNU473/M3_Grup40/blob/main/2_Bicom_System/6_ImagesAndVideos/1SW.jpg)


##  Block Diagrams
### Structural 
### High Level 

![Screenshot (246)](https://user-images.githubusercontent.com/98865009/157951654-8e7dedac-1734-466e-9af7-e25e7614b78b.png)


### Low Level 

![Screenshot (242)](https://user-images.githubusercontent.com/98865009/157950289-56e7b46a-5f55-46c5-a165-f5be80e097d8.png)


### Behavior Diagram
 ### High Level 
![Screenshot (236)](https://user-images.githubusercontent.com/98865009/157950525-17d65404-9238-405a-b876-3b34ece6fc92.png)

### Low Level
![Screenshot (244)](https://user-images.githubusercontent.com/98865009/157950550-c0e27592-aa27-4f1d-a556-f1eb4985875d.png)

### Flow chat 

![Screenshot (221)](https://user-images.githubusercontent.com/98865009/157950928-c073c3b8-ca67-451b-9cae-05cab37b4321.png)



## TestPlanAndOutput

### High Level test plan 

|TEST ID  |TEST CASE OBJECTIVE                       |    INPUT DATA                        |EXPECTED OUTPUT            |ACTUAL OUTPUT              |STATUS|
|:--------|:-----------------------------------------|:-------------------------------------|:--------------------------|:--------------------------|:-----|
|HLTP1     |Window Status         |User press button once | Shall print Window Status        | Shall print Window Sttus              |PASS  |
|HLTP2     |Car Alarm Status      |User press button twice|Shall print Alarm Status | Shall print Alarm Status | PASS |
|HLTP3     |Car Battery Info      |User press button thrice|Shall print Battery Status | Shall print Battery Status | PASS |
|HLTP4     |Door Satus           |User press button four times|Shall print Door Stauts | Shall print Door Status | PASS |

### Low Level test plan 

| TEST ID | TEST CASE OBJECTIVE | INPUT DATA | EXPECTED OUTPUT | ACTUAL OUTPUT | STATUS |
|---------|---------------------|------------|-----------------|---------------|--------|
|LLTP1|Window Status | User press button once | Shall ON all the LED's| Shall ON all the LED's | PASS |
|LLTP2|Car Alarm Status | User press button twice | Shall OFF all the LED's | Shall OFF all the LED's | PASS |
|LLTP3|Car Battery Info | User press button thrice | Shall ON all the LED's once clockwise | Shall ON all the LED's once clockwise | PASS |
|LLTP4|Door Status | User press button four times | Shall OFF all the LED's once anticlockwise | Shall OFF all the LED's once anticloclwise | PASS |

# ADVANTAGES:
* We can have much more information about our car .
* It adds extra security for the car.
* We can have better access control
* Easy for the usage and it also saves some time compared to the normal one.
    
# DISADVANTAGES:
* There can be possibility of hackers to manpiulate.
* potential risk comes from the fact that your car???s engine won???t automatically switch off when you are out of range.
* As the technology increases it supports more Vulnerablility.

