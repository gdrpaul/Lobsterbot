# Lobsterbot
1.Arduino Codes for Lobsterbot


There are two arduino scripts. Upload each one on separate arduino (Arduino Uno).

LobsterMotor_JNM is an arduino sketch for controlling the robot.
It recieves sensor input (Break of Infrared Beam) which triggers claws to snap.
The angles can be adjusted.

LobsterData_JNM receives sensor input (Door, Infrared Beam) and transmit information to PC via serial port.
This part is not necessary if you have high-speed DAQ device already.


2.Serial Monitor
If you are using an Arduino Serial Monitor to receive and display data, set the baudrate to 1152000.
If you want to use the default 9600, the baudrate at the LobsterbotData_JNM code should be changed to 9600 as well. 


3.Jittering problem

Depending on the quality of Servos, jittering of claws during resting state may occur occasionally.

Placing a piece of sponge between the claw and the wall can help stable the claws and prevent jittering.
