# car-tracking-system-sim808
Build a Car Tracking System with the SIM808 Module

This project is a simple tracking system that uses the same GSM and GPS module that is built into the SIM808 module. At the end of this tutorial, when you text the GSM module from any phone, you will be able to get a response with the GPS location of the module depending on where it is.

Hardware and Software Requirements

Hardware:
SIM 808 Module 
Arduino UNO OR Arduino MEGA 
Arduino cable
9V supply
GPS antenna and GSM antenna
![image](https://user-images.githubusercontent.com/67792642/120226314-7ad90e80-c236-11eb-804e-1c095818f4bb.png)

Software:
Arduino IDE
SIM808 library

Make Your Connections
Wire up everything as shown in the figures below.

Rx to pin 10
Tx to pin 11
Connect SIM808 with 9V adapter
Give the power to Arduino via USB cable or 9V charger
Connections for the Arduino UNO
![image](https://user-images.githubusercontent.com/67792642/120226417-af4cca80-c236-11eb-9dc6-357dcb660045.png)

Connections for the Arduino Mega
![image](https://user-images.githubusercontent.com/67792642/120226471-ca1f3f00-c236-11eb-8d6a-05de85e40922.png)

The following images show how the connections will look when wired correctly:
![image](https://user-images.githubusercontent.com/67792642/120226530-e58a4a00-c236-11eb-9918-167e9354843f.png)

![image](https://user-images.githubusercontent.com/67792642/120226549-f33fcf80-c236-11eb-8979-742dcf6515f4.png)

![image](https://user-images.githubusercontent.com/67792642/120226579-00f55500-c237-11eb-9cf5-126c45ac02b2.png)

Upload the Source Code
Putting it all Together
After uploading the code via Arduino IDE, just open the serial monitor at 9600 baud rate. Here you will see the following:
![image](https://user-images.githubusercontent.com/67792642/120226681-30a45d00-c237-11eb-8ee7-804c3c209109.png)

So, whenever you send the “Hi” or “Hello” string to the number of that SIM that is already inserted in the GSM Module, Arduino will text you back with the longitude and latitude information of your module location. 

Moreover, I have already added a link to Google maps, so when it texts you back, it also comes with the Google map location as shown in the figure below:
x-special/nautilus-clipboard
copy
file:///home/revinci/Images/Capture%20d%E2%80%99%C3%A9cran%20du%202021-05-31%2017-42-01.png
![Capture d’écran du 2021-05-31 17-42-01](https://user-images.githubusercontent.com/67792642/120226883-9f81b600-c237-11eb-9117-82f4a8b2bcdb.png)
