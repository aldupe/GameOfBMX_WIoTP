# GameOfBMX WIoTP
## Descripción

*Prueba de tecnologia para comenzar a experimentar con la plataforma de IoT de IBM.* 

El objetivo fundamental utilizar el servicios de IoT de [IBM Cloud (Bluemix)](https://bluemix.net) e integrar dispositivos y  desarrollar una aplicación de forma rápida y sencilla con los nodos de [NodeRed](https://nodered.org/).

In this workshop, you will learn how to connect Raspberry Pi as Gateway to IBM Watson IoT Platform (WIoTP), send data from sensors, visualize this data and create a rule in real-time on WIoTP and that trigger alerts and optional actions.
Not all devices/sensors connect directly to the internet as they may use different kinds of
radio technology to transmit data. The Gateway acts as a bridge between the IoT devices
and the Internet beyond. The gateway then store and parse the information and send them
over to cloud servers for processing and analysis.
The Sense HAT is an accessory for the Raspberry Pi that provides an 8×8 LED matrix, a
variety of motion and environmental sensors and a five-button joystick. This combination
makes it a device that can be used both as a sensor that generates events and one that can
provide distinctive feedback to the user.
In this lab, you will send environmental information from your RaspberryPi + SenseHat
emulator to Watson IoT Platform and display it on a dashboard. You will also use the
weather service to check the weather for your area, and use the forecast data to suggest
actions to take.
The real-life scenario we would try to emulate is as follows:
You have installed temperature and humidity sensors in your garden. The raspberry
PI acts as a gateway, collecting data from the sensors and sending it periodically to Watson
IoT platform. It is also connected to your watering station, allowing you to initiate watering
cycles at will.
With WIoTP Dashboard, you can see in real time the lectures from the sensors. You
use it when you’re out on vacation to check now and then that things are OK with your
plants.
You know that when the temperature is over a certain limit and the humidity is
under some level, your plants are in high risk of drying out, so you want to be warned about
this circumstance and automatically trigger an emergency watering. But you are person
concerned with the environment (and you also know that the water charges are high) so
you would like to know if you could skip some watering based on the forecasted
precipitation for the next 24 hours in your location.
