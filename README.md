# Magic-Cup-Tilt-Switch-Module

Magic Light Cup Module is a board which has a led and a mercury tilt switch. Using PWM to drive the LEDs on the module you can achieve the effect of light being “magically” transferred from one module to the other when tilting them. In short, it’s 2 components combined, a mercury tilt switch and a led. On tilting the module mercury inside small tube connect the switching point and make switch ON while tilting it to other side move the mercury and it disconnects the circuit and switch get OFF. The module operates on 5V DC supply.

So the magic in the name of this module is because when you tilt the switch, the led will turn on and off. And Of course, it is also possible to connect it to the NodeMCU.

Pin Connection with Arduino:
G: GND
+:  5v DC
S:  Arduino pin 8
L: Arduino pin 9

Pin Connection with Node MCU:
Connect G to a GND port of your NodeMCU
Connect + to a 3.3v port of your NodeMCU
Connect S to a digital port on your NodeMCU (in my example port D3)
Connect L to a digital port on your NodeMCU (in my example port D5)
