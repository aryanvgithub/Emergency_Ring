# Emergency_Ring:
It will be just like a normal ring with a button, if an emergency situation exists the person wearing the ring can press the button and then the current gps location will be sent to a particular person with an emergency sms sent to the Registered Number warning them about the danger. Also the information about the person and his live location will be hosted on a webpage that can be accessed by the police to save the person from danger.
# Hardware Specifications:
Microcontroller: Arduino Uno R3 (Atmega 328p based 8-bit Microcontroller),
 GPS: Neo 6M GPS,
 RF transmitter and reciever: 433Mhz (With antena slot to increase range).
# Software Specification:
Webpage Design: HTML and CSS,
 Microcontroller programming: C\C++ on Arduino IDE,
 Backend software Development: Python,
 SMS Sending: Twilio Rest API.
# Additional Info:
We have stored the data of registered users in an excel sheet and then accessed it through python.
 All the images and sounds used are locally saved so if you run the code change the paths.
 The I.D. and authentication token of the twilio rest api has been removed from the code as it is confidential for the user.
 The HTML code creating the web page is itself inside the python code and the .html file is created using python only.
