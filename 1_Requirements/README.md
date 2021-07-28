

All the activities of this control system are performed on the microcontroller Atmega328. The operation of the heat control system is coded in embedded c and the working is demonstrated using a simuation software called SimulIDE.

## SWOT Analysis

![image](https://github.com/stepin314196/Emb-C/blob/main/1_Requirements/SWOT%20Analysis.png)

## Events and Interrupts
| Folder  | Description  | Staus |
|--- |--- |---|
|ON Button|If previously ON|OFF|
|OFF Button|If previously OFF |ON|
|UP Button|Enter Setting mode |---|
|DOWN Button|Turn off heater |---|


| State  | Period  | Action |
|--- |--- |---|
|Setting Mode|Every one second|Blink the display input and Adjust the setting picture|
|Exit Setting Mode|5 second without Button event |Resume with normal mode|
|Temperature Sensing|Every 100ms|Read the temperature and save it|
|Heater On|Every 1 sec|Blink Led|
