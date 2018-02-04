# smartAgri
IoT has made things smarter ,using IoT concepts I had made this mini project on Agriculture .
Smart agriculture 

Title of the Project :      Smart Agriculture 


Idea                        :      To automate and control the watering system in the field of agriculture.


Building Idea         : 

Consider some parameters of the field such as soil moisture level, surrounding temperature and humidity level as these are some parameters determine the need of water to crop.
Other parameters such as the type of soil and its water retaining capacity also effect need of water to crop.
Here in order to give control of the motor to the farmer, he/she may not keep track of the application or check the status of the crop so we can make to send push notifications from the app and one can implement to send text messages to a phone number.(Code for these text messages is not included in code instead Gmail and push notifications are implemented if you are interested to get code for text messages you can comment in below section).
So above mentioned parameters to be determined in order to know whether crop needs water or not.

I'm choosing soil moisture-temperature and humidity sensors in order to monitor them in real time and in order to get those readings choose a microcontroller.To control watering system (motor)  or to automate in the farm we are using IoT concept.



Soil Moisture sensor :

This sensor used to measure the volumetric water content in the soil.Since the direct gravimetric measurement of free soil moisture requires removing, drying, and weighting of a sample, soil moisture sensors measure the volumetric water content indirectly using some other property of the soil such as electrical resistance, dielectric constant or interaction with neutrons, as a proxy for moisture content.

Temperature and Humidity sensor:



Temperature is measured using a thermistor and humidity measurement by capacitive changes.  

I have chosen DHT-11 sensor.It has a single wire digital interface.The sensor is calibrated and doesn't require any extra modules so easy to get relative humidity and temperature.





Microcontroller :

It is a computer present in a single IC which is dedicated to performing a particular task.

I have chosen NodeMCU as my microcontroller which has the ability to connect to the internet and send real-time data to cloud.(one can choose any other microcontroller like Raspberry Pi, CC3200 ... nodemcu chosen as it is low cost compared to others)





NodeMCU uses esp8266 .

Implementation :

First, we are going to use Arduino IDE for programming nodeMCU hence follow the guidelines provided in the following link :



www.instructables.com/id/Quick-Start-to-Nodemcu-ESP8266-on-Arduino-IDE/


Second, we are getting real-time data so to provide that data to farmer we are using the Blynk app.

(One can use any other IoT platform).

Download Blynk app in your mobile and sign up.

http://www.blynk.cc/getting-started/

Next,

Programming your NodeMCU 

finally,

connect all the sensors as per the code and place in the targeted area to monitor

you can see the interface

here is my prototype that pumps water from the motor when button shown in above interface is on

and sensor readings obtained in real time.





