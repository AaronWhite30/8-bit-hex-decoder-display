8 bit hex decoder display

Based on the atmega328 is designed to continuously display in hex, the voltage levels on each of its input pins. 
To reduce the load the decoders may have on the parent circuit,
The inputs are buffered with 100K resistor arrays and the LM324 quad opamps wired in a unity gain configuration.
It uses the 74HC595 serial to parallel shift registers to process the the data from the uP and uppdate the 7 segment displays.
