# Ultra-Sonic-radar-codes
This repository contains the codes used for an Ultra-Sonic radar by using Processing program to draw a real-time radar.

The Processing code file, contains the code you need to the Processing program.
Is important to note that you need to edit at which port your Arduino circuit its located.
In this code, the Arduino was using 'COM9' as his port, but if yours is 'COM5' then you need
to change it to the according port selected on the Arduino program. Also, you cannot have open
the Arduino program 'Serial monitor' because there cannot be two different programs reading the same Serial port. 

This code functions by reading the 'Serial' prints from the Arduino, and those serial prints are
only the angle at which the servomotor is moving and the distance in which an object is from the
Ultra-sonic sensor. With both of those values, the Processing will move on real-time. You can manipulate
the code into your own taste and make all the drawing you wish. You can change letters, colors, and even the size of the radar.

The Arduino code file, contains the code you need to the Arduino circuit.
Is important to note that the pins used for the components, must be the same pins used on the code.
Or, if you are using different pins, then make the changes accordingly on the code to the corresponding pins
connected to your components. If your pins are connected to the declared pins on the code, your circuit will run smoothly.
