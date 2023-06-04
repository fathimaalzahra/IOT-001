## Task 1 - Simon Says
Create a simon says game using ESP32, pushbuttons and LEDs. Blink the leds randomly, asking the user to push the corresponding buttons. If the user has failed, then give a clear indication and restart the game.

What is [simon says game](https://www.mathsisfun.com/games/simon-says.html)?

How to make it using ESP32? Follow this wokwi [simulation](https://wokwi.com/projects/328451800839488084) and modify it for ESP32.

Takeaways : Familiarize with the use of the microcontroller esp32 and create a fun game.





## Task 2 - Basics of MQTT protocol and other communication protocols

Learn the basics of MQTT protocol and its working from the [website](-https://randomnerdtutorials.com/what-is-mqtt-and-how-it-works/)

Learn the different types of communication protocols [here](https://www.opc-router.com/what-is-mqtt/)

Learn about the different networking protocols [here](https://www.techtarget.com/iotagenda/tip/Top-12-most-commonly-used-IoT-protocols-and-standards)

Takeaways : Learn about the different protocols used in IOT. 

## Task 3 - Basics of creating a website

Learn how to create a website both front-end and back-end. Create a webpage with a [button](https://www.w3schools.com/tags/tag_button.asp#:~:text=The%20tag%20defines%20a,with%20the%20element!) that when pressed toggles the color of the webpage.

[need help?](https://www.w3schools.com/cssref/tryit.asp?filename=trycss_js_background-color)

Takeaways : Learn to create a website so that its easier to create a webserver.

## Task 4 - ESP32 Cam 

Set up  a CCTV camera system that streams/records video footages as a measure to heighten the lab security.

[Resource](https://randomnerdtutorials.com/esp32-cam-video-streaming-face-recognition-arduino-ide/)

Takeaways : Learn to use the esp32cam. 


##  Task 5 - Control ESP32 Cam from Node-Red using MQTT protocol

Capture an image from the esp32 cam using Node-Red on the PC. Send the image back to the Node-Red interface.

[Resource](https://www.youtube.com/watch?v=L_rqYK_QUCg)

Takeaways : Learn how to practically use MQTT protocol for publishing and subscribing data.


##  Task 6 - Sending data to ThingSpeak
Using Esp32 post the data of a temperature sensor to the Thingspeak Website using its api and display the graph of temp vs time and after processing retrieve the data back from the website.

Alternatively you can also use matplotlib in python to plot the graph of temp vs time, by downloading the dataset from thingspeak.

[Resource1](https://randomnerdtutorials.com/esp32-http-post-ifttt-thingspeak-arduino/)

[Resource 2](https://nothans.com/thingspeak-tutorials/arduino/send-data-to-thingspeak-with-arduino)

Takeaways : Learn how to publish data to website and get data from it



##   Task 7 - Communication using I2C protocol

Send data from Esp32 to Arduino via I2C protocol and display a message on the lcd screen by typing the message using the webserver hosted on the esp32.

What is [I2C protocol](https://www.tutorialspoint.com/what-is-the-i2c-protocol-in-computer-network#:~:text=I2C%20stands%20for%20the%20inter,device%20has%20a%20specific%20address.)?

[Resource](https://forum.arduino.cc/t/i2c-from-esp32-to-arduino/975652)

Takeaways : Learn the wired communication protocol between two microcontrollers.



## Task 8 - Flashing Morse Code 

Set up an ESP32 to flash morse code using an led making use of the message sent by the webserver hosted on the esp32.

[Resource](https://www.deviceplus.com/arduino/how-to-create-a-morse-code-generator-using-arduino/).

Takeaways : One of the real life application of a webserver for communication.


## Task 9 - Soil Moisture Sensor

Measure the moisture level of the soil in the pot using the capacitive soil moisture sensor and display the moisture level on the serial monitor or on the LCD screen. Give an alert to the user if the soil moisutre level is below a certain level. 

[Resource](https://esp32io.com/tutorials/esp32-soil-moisture-sensor).

Takeaways : Learn to measure soil moisture and control the water level.


## Task 10 - Read and Display Vitals

Measure heart rate and blood oxygen levels using MAX30100 sensor and display the results on an Android Application using MIT App Inventor. Give a notification to the user if the heart rate or the oxygen level is out of the normal range. The app can communicate with the ESP32 using a webserver or using MQTT protocol. 

Resources:

1. [MAX30100 with OLED](https://www.instructables.com/Heart-Rate-and-Blood-Oxygen-Level-With-Arduino-IDE/)
2. [MIT App Inventor using WebServer](https://community.appinventor.mit.edu/t/esp32-sends-data-to-the-app-over-wifi-in-realtime-javascript-ajax/46307)
3. [MQTT using MIT App Inventor and ESP32](https://www.youtube.com/watch?v=WAimZhU5phs)




