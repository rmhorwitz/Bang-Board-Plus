# Bang-Board-Plus
Bang Board Plus is a USB virtual pinball interface that provides a game joystick controller, a HID keyboard, and a handful of outputs.  The game joystick input is replaced with the X and Y output of an accelerometer, while the joystick Z channel emmulates the output of a ball plunger.  The board has 12 high-current output channels for controlling solenoids, motors and lamps.  This is a value point system, providing a limited amout of features at a low cost. 
Coding was initially done in micropython, but this had severe performance restrictions. MJR has offered a port of his Pinscape for Pico that I am in process of evaluating.
The schematic and PCB design is captured in KiCAD 8.0.  This package stands at Revision 2.
This package is released as-is. At the time of initial release this design has not been built yet. 
PDFs of the PCB and schematics are provided for review and comment. 
