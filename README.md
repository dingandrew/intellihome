Intellihome: A framework for Smart Home Connectivity

IEEE Spring 2019 Quarterly Projects

Contributors: 

Andrew Ding, Katherine Olesak, Justin Han

Problem:

Existing smart home products such as Nest Thermostat, Phillips Hue Light Bulbs, 
Smart Fridges, Amazon Alexa, and Google Home are very expensive and also require 
some degree of technical literacy to operate,  making them unappealing for many 
consumers. While these different products can be interfaced with one another, 
there is a lack of a single cohesive application that can easily manage multiple 
different IoT devices. Current solutions such as connecting a Philips Hue to 
Amazon Alexa is time consuming, different for every manufacturer, and difficult 
for the layperson. There does not exist a single product line that contains 
multiple smart home devices that are managed through a single application. 

Solution:

The goal of our project is to create a framework that allows wireless connectivity 
and smart capabilities to be easily added and interfaced with common home devices.  
Our framework will embrace a modular design philosophy, this means that the 
hardware and software can easily be adapted to meet any requirements. 

Internet connectivity is achieved through the ESP8266 wifi module which is 
connected to relays or other peripherals, which is programmed to communicate 
to the main Raspberry Pi. Our software stack will allow the user to control 
multiple devices, monitor usage, and collect data. The website will also allow 
the user to program certain actions for the devices to perform and use machine 
learning on the data collected when applicable. 

Because we are creating a framework our hardware has to be able to interface 
with existing devices. One example of this is the Smart Plug which is connected 
to the network and uses a relay to turn power to the outlet on or off. The Smart 
Plug will also be able to monitor electricity usage to the website allowing the 
user to see which appliances are the most inefficient. This concept could also 
be embedded inside a home power grid so that every light, outlet, switch could 
be connected to the IoT. In theory any device ranging from sensors for measuring 
temperature to home security could be added to our network using our framework. 
The framework would be able to handle multiple devices all with a different 
functionality and purpose. Seamlessly allowing a user to control every aspect 
of their home. We will also add backwards integration to existing smart home 
systems such as Amazon Alexa.


Implementation:

https://intellihome-de355.firebaseapp.com



