# TestPlanAndOutput

## High Level test plan 

|NO|TEST ID  |TEST CASE OBJECTIVE                       |    INPUT DATA                        |EXPECTED OUTPUT            |ACTUAL OUTPUT              |STATUS|
|:-|:--------|:-----------------------------------------|:-------------------------------------|:--------------------------|:--------------------------|:-----|
|1-|TC-1     |For Car lock Function                     |User shall press the button once |Car locked            |Car locked              |PASS  |
|2-|TC-2     |For Car unlock Function                   |User shall press the button twice | Car unlocked          |Car unlocked          |PASS  |
|3-|TC-3     |For alarm activation/deactivation Function|User shall press the button thrice|Alarm activated/deactivated|Alarm activated/deactivated|PASS  |
|4-|TC-4     |For approach light Function               |User shall press the button four times|Light approach ON      |Light approach ON       |PASS  |


## Low Level test plan :

|Test ID|	Description                 |Input	                         |Exp output                                                   |Actual Output                        |Status|
|:------|:----------------------------|:-------------------------------|:------------------------------------------------------------|:------------------------------------|:-----|
|LLR_1	|Car Lock                     |If	Button is pressed one time   |All LEDs will be ON and Print Lock                           |All LEDs will be ON and Print Lock   |	Pass|
|LLR_2  |Car unlock                   |If	Button is pressed two times  |All LEDs OFF and Print Unlock                                |All LEDs OFF and Print Unlock        |	Pass|
|LLR_3	|Alarm activation/deactivation|If Button is pressed three times|All LEDs ON Clockwise and print Alarm activation/deactivation|All LEDs ON Clockwise and print Alarm activation/deactivation	              |Pass|
|LLR_4  |approach light               |If Button is pressed four times|	All LEDs ON in Anticlockwise and Print Approach Light         |All LEDs ON Anticlockwise and Print Approach Light   |Pass                         |
