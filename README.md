# Torque

Any and all code related to using Ian Hawkins' Torque for Android.

Torque is an Android app for interacting with a car's onboard computer via an OBD2 dongle (that you have to buy from somewhere like Amazon) plugged into your car's OBDII socket.

You can use it for free, but once you want to do cool(er) stuff you need to buy it, which is worth it.

Torque has a live-logging feature that can output shed-loads of data to an online service that Ian provides, which I recommend you check out. However, he put the option to specify a URL instead of his site, so it seemed a shame not to try it out...

When configured and running, Torque makes rapid-fire HTTP GET requests to the URL and expects a simple "OK!" response in return. Once Torque gives you the key/value pairs in the URL, you're free to do whatever you like with them...
