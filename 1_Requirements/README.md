A pharmaceutical manufacturer needs to keep space temperatures in a warehouse between 68°F and 78°F to maximize shelf life of their products. The pharmaceutical logistics and supply chain process involve the movement of drugs and medications from one facility to another. When these products are exposed to incorrect temperatures, the effects of decomposition can occur and diminish the effects intended from the products.When a drug is stored in temperatures that are too high or too low, the drug's chemical stability will likely be impacted. That means that the drug may degrade and form impurities. While these impurities may not be visually noticeable, this degradation can cause real problems when the drug is administered.

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
