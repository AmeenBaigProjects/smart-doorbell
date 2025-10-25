# smart-doorbell
## What and Why
As of recent, there has been a massive surge of home surveillance devices known as "Smart Doorbells". The main appeal of these devices, is their 2-in-1 functionality of behaving as a regular doorbell while providing video surveillance of the area near your door. What makes these devices "smart" is their IoT capabilities. You can get notified about any doorbell rings or suspicious activities near your door, and access video surviellance footage through your personal devices via online services or applications. 

However, many popular smart doorbell products like the "Ring Doorbell" by Amazon are more feature rich than necessary for the average user, making them more expensive than necessary. For example, the device being able to record surveillance footage 24 hours a day, seven days a week is one such functionality of the Ring Doorbell. Although it may be a useful functionality to have, it drastically decreases the power and storage efficency of the device. Adding a simple motion detection system in the device enables it to only record when motion is detected. This results in a significant decrease in the amount of footage to capture and upload, which means a significant decrease in power and storage consumption.

I wanted to uptake a project where I designed and built such device that maximizes power and storage efficency, by implementing the basic bare-bones functionalities that would make it a Smart Doorbell.

## Functionality
There are two major functionalities that the Smart Doorbell can perform:
### Surveillance Functionality
When a PIR Sensor on the Smart Doorbell detects motion near the door, a buzzer in the Smart Doorbell is sounded and an LED lights up to indicate surveillance is in progress. Simultaneously a camera activates and takes a picture every 5 seconds. When motion is no longer detected, LED turns off and the camera deactivates. The pictures are uploaded to cloud over wi-fi.
### Doorbell Functionality 
When a button to ring the bell is pressed on the Smart Doorbell, a speaker is sounded and a picture taken by the camera along with it's timestamp is sent to your personal device via a telegram bot.

## Bill of Materials
|Part/Component|Usage|Cost|
|--------------|-----|-----|
|Perfboard|Prototyping Board|£0.25|
|18650 Li-ion 3.7v Rechargeable Battery|Power Supply|£3.03|
|TP4056 Li-ion 3.7v Charging Module Overcurrent Protection Board|Charging the Battery|£1.11|
|MT3608 Step-Up Boost Converter|Voltage Boost|£0.34|
|Momentary Reset Short Push Button|Button for Bell|£1.50|

##Schematic
The Schematic ""


