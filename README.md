# capstone
The goal of the project was to make a vibrating pet collar, i used object identifcation on a raspberry pi 3 to locate the object, then with a user drawn danger area.
(The danger area is drawn by first, pressing the space bar tp take a capture of the feed, then with a mouse right click, hold down and draw across the area where object is to not be at)

The raspberry pi is connected to an arduino serially (i.e with a usb cable connecting the arduino to the raspberry pi). Then once the set criteria of 20 counts is met, a signal is sent serially to the arduino which then sends a signal to the collar using the nRF24L01 module both on the sender and receiver, once the code is received, the vibrating motor powers up.


raspberrypi_identify.txt is a python code for the identification on the raspberry pi. I followed the youtube video to get the identifcation running and the example codes. https://youtu.be/iOTWZI4RHA8
Then updated the code to run for the project needed.

The other 2 codes are arduino c/c++ files.

 
