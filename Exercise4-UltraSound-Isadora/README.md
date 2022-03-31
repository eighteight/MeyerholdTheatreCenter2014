Exercise 4: Arduino + HC-SR04 ultrasonic distance meter + video player controlled by a distance to an object

Prerequisites:

Isadora http://troikatronix.com/download/isadora-pre-releases/

Arduino software: http://arduino.cc/en/Main/Software

HC-SR04 library: https://bitbucket.org/teckel12/arduino-new-ping/wiki/Home (download and unzip folder into /Users/THIS_USER/Documents/Arduino/libraries

Arduino hardware (I used Uno r3)

Ultrasound distance sensor HC-SRO4





1. Set up the sensor in Arduino as described here: http://www.instructables.com/id/Ultrasonic-Range-detector-using-Arduino-and-the-SR/

2. Open HC-SR04.ino/HC-SR04.ino patch in Arduino software
3. Upload patch to Arduino
4. Close Serial terminal in Arduino if it is open
5. Open UltraSound_HC-SRO4_Arduino.izz in Isadora (it will ask for a video file — provide it)
6. Enable Serial Ports, and check the settings of the port 1, especially the speed — it should correspond to the speed set in the arduino patch
7. At this point Arduino should be sending the distance measurements to Isadora, which will drive the position of the video file


![Preview](https://raw.github.com/eighteight/MeyerholdTheatreCenter2014/master/Exercise4-UltraSound-Isadora/IMG_3100.JPG)
