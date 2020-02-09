AIM-
Develop colour sensor with the help of RGB led and ldr.

COMPONENTS REQUIRED
Arduino
RGB LED
Photoresistor
10kΩ resistor
3x 100Ω Resistor
Jumper
Breadboard wires

PROCEDURE-

Step 1:Wire the RGB LED
This will be the emitter part of our circuit emitting different colours which will bounce off of objects, by the law of optics which will be detected by our photosensor.

* Connect pin 2, the longest pin to the GND pin on the Arduino.

* Connect pin 1, the red coloured LED of the RGB LED to pin 5 on the Arduino.

* Connect pin 3, the greed coloured LED of the RGB LED to pin 6 on the Arduino.

* Connect pin 4, the bleu coloured LED of the RGB LED to pin 9 on the Arduino..

Step 2: Wire the Photosensor
The reflected light from the emitter (RGB) LED bouncing back off of any objects will be read by the photosensor which will used calibrated values to find the individual R-G-B colour values of a particular colour.


* Connect one of the pins, call this pin 1, of the photosensor to the GND pin on the Arduino

* Connect pin 2 of the photosensor to the 3.3V pin on the Arduino.

* Connect pin 2 of the photosensor to the A0 pin on the Arduino.

 Last two wirings are all parallel because a voltage divider is made to get the changing voltage reading as the reflected light changes in intensity.
 
 RESULT:
 Hence light sensor is made with the hel of ldr sensor and rgb led with appopriate microcontroller.
