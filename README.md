# two_jumper_controlled_two_oscillators
Code can be loaded directly from Arduino IDE using a standard arduino board with a bootloader or using Atmel Studio and a programmer.

The code is written in AVR-C, not Arduino language.

This board has two outputs and two modes. 
Mode A: Output A and Output B are the same frequency and phase
Mode B: Output A is 700 Hz above Output B (need to double check these numbers).

Arduino PIN 0 and PIN1 switch between mode a and mode b
Arduino Pin9 is Output A (frequency changes based on which key is pressed - pin0 or pin 1)
Arduino pin 11 is Output B (frequency never changes)

Does output phase change when switching back and forth from mode a to b then back to a?

Pressing a key can be a momentary switch or real switch. 

Final note: should add code to make sure both buttons aren't pressed before processing key presses.


