# Zine Project
## Stage 0:
Downloading application such as KiCAD for designing ,simulation and PCB development for the whole project
## Stage 1 – Circuit Design

### Power Stage – H-Bridge Design(Idea From Other's Project)

Purpose:

The H-Bridge is a power control circuit that lets current flow through a motor in both directions, so the motor can rotate clockwise or anticlockwise.
It also helps control speed and torque when used with PWM (Pulse Width Modulation) signals.


Started learning by watching how other deployed and operated the whole schematics and designing
From youtube :- https://www.youtube.com/watch?  v=4kDMF0SQ0Zg&list=PLJ0HErIq5D2zQIZq9s4L3cUzeMuB7d4Ho&index=2.   

Thus finally implemented it on my own.
![Schematics](https://github.com/Aakash4096/AnalogMotorTorqueControl/raw/main/assets/H_bridge_schematics.png)
![Template_PCB](https://github.com/Aakash4096/AnalogMotorTorqueControl/raw/main/assets/template_pcb.png)


#### moving back to our own project -
Searched and gone through specifications for my project 
Components used for this project  


-Q_PMOS as p-MOSFET


-Q_NMOS_GDS as n-MOSFET


-Resistors


-SS34 as 40V 3A Schottky Diode, SMA


-IR2104 as Half-Bridge Driver, 600V, 210/360mA, PDIP-8/SOIC-8

Taking references from project developed in site:
https://www.pcbway.com/blog/technology/A_Standalone_Full_Bridge_DC_Motor_Driver_2c7c2086.html

Added PWM1 and PWM2 inputs from HALF-BRIDGE driver.

Thus my project looks as this :-

![Power_stage](https://github.com/Aakash4096/AnalogMotorTorqueControl/raw/main/assets/Power_stage_schematics.png)





