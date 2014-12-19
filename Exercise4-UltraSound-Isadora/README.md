Prerequisites:

Isadora http://troikatronix.com/download/isadora-pre-releases/
Arduino software: http://arduino.cc/en/Main/Software
HC-SR04 library: https://code.google.com/p/arduino-new-ping/ (download and unzip folder into /Users/THIS_USER/Documents/Arduino/libraries

Arduino hardware (I used Uno r3)
Ultrasound distance sensor HC-SRO4


Exercise 4


1. Set up the sensor in Arduino as described here: http://www.instructables.com/id/Ultrasonic-Range-detector-using-Arduino-and-the-SR/

2. Open HC-SR04.ino/HC-SR04.ino patch in Arduino software
3. Upload patch to Arduino
4. Close Serial terminal in Arduino it is open
5. Open UltraSound_HC-SRO4_Arduino.izz in Isadora
6. Enable Serial Ports, and check the settings of the port 1, especially the speed — it should correspond to the speed set in the arduino patch