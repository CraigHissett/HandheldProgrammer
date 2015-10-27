# HandheldProgrammer
Pi/Arduino hybrid portable Programming device

The Pi will have various programming environments such as Python, Ardino, html editors etc.
It will be connected to the Arduino Pro Micro via i2c.
The Arduino Pro Micro will monitor the i2c line and forward any keyboard commands to it's USB port using the keyboard library
Enclosed in a gameboy-style case, a python script will run on startup to capture button presses from the Arduino nano

Programming of the Arduino will be possible from the Pi as both the Pi USB ports and the Arduino USB port 
will be on the outside to be connected to eachother
