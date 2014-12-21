Exercise 13

Use rotary encoder, arduino and Isadora to dynamically projection-map a rotating object

Inspiration: https://www.youtube.com/watch?v=lX6JcybgDFo

Prerequisites:

Isadora http://troikatronix.com/download/isadora-pre-releases/

Arduino software: http://arduino.cc/en/Main/Software



Arduino hardware (I used Uno r3)

Rotary encoder (I used COM-10596) https://www.sparkfun.com/products/10596


1. Three pins of the encoder only are used. They are called A, B, C
2. Connect A and B to analog inputs of Arduino A0 and A1.
3. Connect C to GND input of Arduino on analogue side
4. Launch RotaryEncoder/RotaryEncoder.ino in Arduino software
5. Rotate encoder and observe value change in Serial monitor in Arduino software.
6. Close Serial monitor above.
5. Launch RotaryEncoder_Arduino.izz in Isadora.
6. Set serial speed to 115200
7. Rotate the encoder and observe the rotation of the movie



Other useful links:

Encoder lib: https://github.com/medecau/QuadEncoder

Arduino patch is a modified version of http://www.circuitsathome.com/mcu/programming/reading-rotary-encoder-on-arduino

How the encoder works, and how to fix the “bounce”: https://www.youtube.com/watch?v=HQuLZHsGZdI
