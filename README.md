# Lobsterbot
Arduino Codes for Lobsterbot


There are two arduino scripts. Upload each one on separate arduino (Arduino Uno).

LobsterMotor_JNM is an arduino sketch for controlling the robot.
It recieves sensor input (Break of Infrared Beam) which triggers claws to snap.
The angles can be adjusted.

LobsterData_JNM receives sensor input (Door, Infrared Beam) and transmit information to PC via serial port.
This part is not necessary if you have high-speed DAQ device already.
