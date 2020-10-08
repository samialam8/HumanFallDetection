# Human Fall Detection
Human Fall Detection Using Arduino Board

## Software Used:
1. Install Arduino IDE (https://www.arduino.cc/en/Main/Software)
2. Libraries(adxl345, Bluetooth Module)

## Why Fall Detection is needed and its objectives.

Fall risk factors include[1]:

-> Working at elevated heights,

-> Overdrinking of alcohol,

-> Working in unsafe environment,etc.

The objective of this project is to design and create fall detection system for people of all ages. The system will be wearable and capable of wireless communication with mobile phones. In the event of fall, the device will warn the users and others wirelessly with the help of mobile phones.
This system is different from all existing commercial devices for several reasons. In this design, middleman call center service is not needed thus extra monthly fee is saved. Additional setup costs and hardware is minimized by use of users existing mobile phones. This is done because most likely next generation are relatively comfortable with technology and had their own cell phone. This device is designed in such a way that if there is fall and if it not severe then one can cancel the alarm by pressing manual cancellation button. This device also offers a wide range of alert methods for hearing impaired, seeing impaired. In the event of fall the device can give warning in the form of siren and flashing LED. So, this design of fall detection system should improve on previous system and designs.


## Component used to build this project is listed below:

-> Arduino UNO Board (ATMEGA328P)

-> Accelerometer (Adxl345)

-> Bluetooth Module (HC-05)

-> Force sensing resistor (FSR)

-> Light Emitting Diode (LED)

-> Resistors(10kohm)

-> Buzzer

## Circuit diagram of fall detection system

![](Circuit%20diagram.png)
 
Figure 8: Circuit diagram of fall detection system


## How it works?

For fall detection, the most simple and common methodology is by using accelerometer and applying thresholds [11,12]. When there will be any motion that exceeds some threshold value of acceleration then it will be considered as a fall. For the advancement of fall detection technique, the dot products or cross products of the axial accelerometer is observed and calculated to obtain the cross-product magnitude and angle change [13]. Force sensing resistor is used to measure the foot pressure of the person. This is important because most often when a person falls, they fall vertically standing to horizontally lying on the ground which results in no pressure on the person foot.
This project all together involves defining algorithms for maximum sensitivity and specificity. This project is done with the help of new idea with hybrid algorithms. This device uses accelerometer and FSR. In this project, sensor placement is done on the wrist and foot of the person.
