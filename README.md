# G920-shifter-stand-alone - 13/05/2020
Logitech G920 shifter to work as it's own USB device

One of the problems that seems to keep showing up with peoples G920 shifter, is that it shifts into the wrong gears. This will help to set up the shifter to change the calibration.

Before doing this, be sure to strip down the shifter to spray some cleaning fluid into the potentiometers. This helps a lot, but might not be the final solution.

This isn't my project as such. I have modified some small parts of it and wanted to dumb it down even further for those who, like me, need things dumbing down a bit. In the code I added an extra input for people who want to use a gear splitter in Euro Truck Simulator.

I am not a coder. It took me way too many hours to figure out how the code works and how to add my own piece of it!

Credits go to amstudio
https://www.youtube.com/watch?v=dLpWEu8kCec 
this is a great video of it all in action and how to set everything up. 

amstudio - github https://github.com/AM-STUDIO/LOGITECH_USB_ADAPTER

Thank them, not me, I just added some code and decided to explain the code better.

You will need this library installed into your Arduino software - https://github.com/MHeironimus/ArduinoJoystickLibrary

# This only works with the Arduino Leonardo and the Arduino Pro Mini

![gearstickdiagram](https://user-images.githubusercontent.com/65309612/81860694-01a14780-955f-11ea-93c1-67e7dec296e0.JPG)
Picture credit to amstudio

Wire up your gear stick DB9 connector to your Arduino like so. You can just push peices of wire into the conector and the Arduino. I did this to confirm it all works. Then ordered some male CB9 connectors that I can mount to the outside of a case of some kind.

Open the Arduino sketch to see the comments inside that explain how to change your calibration and enable the input to wire in anything you like. My main reason is to use it for a gear splitting function in Euro Truck Sim. Other uses I can think of might be to add a button somewhere on the shifter. It could be useful for arming nitrous in BeamNG Drive. I have it set up in Assetto Corsa to shift into 7th gear for cars that need it. Use your imagination.
