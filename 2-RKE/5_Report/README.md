# Requirements
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


# SWOT Analysis
## Strengths
* low power consumption

* Better Security

* Better accesss control

* Ease and convenience

## Weakness
* The cost of this technology is high

* Thieves can hack the program

# 4W'S & 1H
## WHO
The Bicom system is an electronic access control system that can be operated from user.

## WHAT
The Bicom system which are commonly used to displaying window status, alarm status, car battery info status, Door status.

## WHEN
end user needs to perform an action that causes a physical or software key fob to send a radio signal to a receiver that controls an electronic lock.

## Where
Bicom systems for cars can operate in any where with the requirements.

## How
The action is usually performed by pressing a button on a physical fob.


# Block Diagrams
# Structural 
# High Level 

![Screenshot (227)](https://user-images.githubusercontent.com/98865009/157861800-f1ecc53e-d789-444a-b3c1-79fcbeec1343.png)

# Low Level 

![Screenshot (234)](https://user-images.githubusercontent.com/98865009/157860944-1b321813-7bd7-469b-b93d-f0e0f6178bb6.png)


# Behavior Diagram
 # High Level 
![Screenshot (228)](https://user-images.githubusercontent.com/98865009/157857855-c2791576-0c8e-4ee2-8811-6f04526c9028.png)


# Low Level

![Screenshot (226)](https://user-images.githubusercontent.com/98865009/157856085-8db34286-2ec2-4a34-b0de-4cc6481b7fe3.png)


# TestPlanAndOutput

|NO|Test case|Test case Objective                    |Input data                               |Expected Result                                                    |Actual Result                                              |status |
|:-|:--------|:--------------------------------------|:----------------------------------------|:------------------------------------------------------------------|:----------------------------------------------------------|:------|
|1 |TC-1     |For displaying the window status of car|user needs to press the button one time  |All LED On at the same time, its shows the window status           |All LED ON at the same time, its shows the window status   |PASS   |
|2 |TC-2     |For displaying the alarm status  of car|user needs to press the button Two time  |All led off at the same time, its shows the alarm status           |All led off at the same time, its shows the alarm status   |PASS   |
|3 |TC-3     |For displaying the car battery info    |user needs to press the button three time|All led on in clockwise, it shows the car battery info             |All led on in clockwise, it shows the car battery info     |PASS   |
|4 |TC-4     |For displaying the Door status of car  |user needs to press the button four time |All led on in anti-clockwise , its shows the Door status of car|All led on in anti-clockwise , its shows the Door status of car|PASS   |


