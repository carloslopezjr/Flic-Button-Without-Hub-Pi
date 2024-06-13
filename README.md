# Flic-Button-Without-Hub-Pi
Code to control a Flic Button without the needed hub using Raspberry Pi!

First, install/use the bluetoothctl command in Linux to search for LE Bluetooth devices.

Scan the LE Bluetooth devices until you find the Flic MAC ADDRESS and write it down.

Adjust the code on line 11 to connect to your specific MAC ADDRESS, and it should work from there!

Adjust the sleep function as needed, default is set to 5 seconds before another press signal can be recognized.
