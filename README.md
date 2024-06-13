# Flic-Button-Without-Hub-Pi
Code to control a Flic Button without the needed hub using Raspberry Pi!

First install/use the bluetoothctl command in linux to search for LE bluetooth devices.

Scan the LE bluetooth devices until you find the Flic MAC ADDRESS and write it down.

Adjust code to connect to your specific MAC ADDRESS, and it should work from there!

Adjust the sleep function as needed, default is set to 5 seconds before another press signal can be recgonized.
