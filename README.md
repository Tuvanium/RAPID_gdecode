# RAPID_gdecode
Use RAPID to decode g-code directly in a ABB robot.


1. Create a gcode file in your favorit slicer (Prusa, Cura, ect). <br>
2. Upload the file to the HOME directory of your ABB robot <br>
3. Decode the gcode to robot movement by calling _**ReadGcodeFile "YourFilename.gcode",5000,tool,wobj;**_ <br>
(Decoding will stop at 5000 lines of the file.) <br> <br>


This RAPID module is intended for those that wants to use a ABB robot to do 3D printing.<br> 
As the standard slicers exports gcode a convertion between gcode and RAPID is needed. <br>
This module makes the convertion in the robot, so you can upload the gcode file directly to the HOME directory in your robot without prior convertion.


The code is released under MIT-license. But if you make alot of money from it, you are free to give some to me.
