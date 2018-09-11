<img src="https://raw.githubusercontent.com/pratik-vii/Myosa/master/Screenshots/AppIcon.png" width="300">

# MYOSA
MYOSA (Make Your Own Sensors Applications) is a plug-and-play, multipurpose, multi-sensor system for learning and developing sensor based applications. The entire system of MYOSA is like a lego set. All the components of this system are in the form of ‘blocks’ and can simply be plugged into each other. Various blocks include multiple sensors, actuators and an OLED display that shows the sensor readings. This ‘plug and chug’ feature provides the users with ready-to-apply connections of all the necessary components with the motherboard. One doesn’t have to worry about tons of wires and can directly jump to developing creative applications!  The motherboard of MYOSA is an Arduino derived opensource board.  The motherboard also has a Bluetooth module through which the output data gets transferred to the MYOSA mobile app. Thus, MYOSA is a complete package for getting introduced to the world of sensors and creating wonderful real life applications!

## Components of MYOSA:
* The Motherboard
* MYOSA Sensorboards
* MYOSA Actuators
* Onboard Bluetooth
* Plug and Play WiFi
* The Mobile Application
* The Firmware
* Packaging


## The Mobile Application

The MYOSA mobile application has been developed with an aim to bridge the gap between the entire MYOSA system and the user. The user can simply download the mobile app and get connected to his/her own project developed using the MYOSA hardware and firmware. The connection takes place via bluetooth. Once connected, the app provides a great interface for extending the usability of the sensor based project.

<div>
  <img src="https://raw.githubusercontent.com/pratik-vii/Myosa/master/Screenshots/LandingPage.png" width="270">
  <img src="https://raw.githubusercontent.com/pratik-vii/Myosa/master/Screenshots/Readings.jpeg" width="270">
  <img src="https://raw.githubusercontent.com/pratik-vii/Myosa/master/Screenshots/EventCreation.png" width="270">
</div>

## Features of mobile app:

### Access to sensor readings
The mobile app periodically fetches the readings and outputs of the sensors connected to the MYOSA motherboard. The data observed on the OLED display is uploaded to the app via Bluetooth module and updated from time to time. The graphs of the readings of each sensors are also plotted. The user can study the changing trends of the sensor values using these graphs. Thus, the app provides a very handy and easy access to the sensors data.

### Event Creation
The mobile app provides a very interesting feature of ‘event creation’ to visualize and manage the behavior of one’s  MYOSA project in particular situations. This feature allows the user to create an event using all/some of the connected sensors. The range of readings can be set for the selected sensors. If the value of those particular sensors violate the range, then the appropriate actuators will be triggered. For example, if the event is ‘Fire detection and alarm’, then the user can set the thresholds for the air quality sensor (for smoke detection), luminosity sensor and the temperature sensor accordingly. If the values of these sensors exceed the thresholds, then the buzzer (actuator) will be triggered. Thus the user can be made aware whenever a fire outbreak occurs! At a time, 3 simultaneous events can be created. Many more useful events can be thought of and implemented via this feature.

### Availability of local database
The values of all the connected sensors are backed up in an excel sheet which will be stored in the internal storage of the mobile on which the app is downloaded. This data can be stored and used in future if needed. The trend analysis can also be done using the sensor values captured over a specific period of time.

## Developed by
* [Pratik Prajapati](https://github.com/pratik-vii)
* [Ravi Sawlani](https://github.com/james222424)
