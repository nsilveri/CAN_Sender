# CAN_Sender
Arduino MKR Zero and MKR Can Shield data sensor sender

This is a my part of a university project called Agrosbus.
the aim of the project is to take sensor data from the CAN-bus of an agricultural vehicle and to use it with ROS, 
this project was developed by me and a colleague of mine. 
I dealt with the simulation of a CAN network through the use of some sensors (DHT11 and HC-SR04) connected to the Arduino PINs.
The Arduino.ino Scketch takes data from the sensors and creates one or more virtual CAN nodes that send CAN frames with the CAN Shield on a real CAN network
