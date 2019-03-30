# PCB-RaspiZero-Power-PWM
My first mostly successful try at a printed circuit board. It hosts a PCA9685 16xPWM generator and mosfets for every channel.
Controled via I2C from a Raspberry PI or an Adruino it can be used to dim loads of 7A and more. 
The board's shape, pins and hole palcement equals a Raspberry Pi Zero and therefore allows to mount it directly ontop and still use all pins.  
The Mosfets are N channel mosfets meaning only the Ground is common for all of them and on the PCB. Therefore loads of different voltages can be used simultaneously.

Boards based on Gerber files exported from this project have been produced by https://jlcpcb.com/
Samples have been soldered by myself and tested successfully with a bunch of different loads. Unfortunately it turned out that the diodes on the backside of the PCB are efectively useless because not sensefully placed in the scheme. Therefore inductive loads like motors still require separate flyback diodes!

Photos of a project using this comes soon.
