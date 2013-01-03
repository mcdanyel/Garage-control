Garage-control
==============

Arduino based home automation package for my garage/workshop. 

This build uses Processing, PHP, and Arduino to perform a variety 
of home automation tasks via the internet to my home workshop. My 
current setup uses: 
• Ardunio Uno
• Mutiple relays
• temperature sensors
• motion sensors
• a variety of light fixtures and hard wired outlets 
• PC for intenet connection through Processing app
• iPad for app based control of system

Contents:
• Current working Arduino sketch for an Arduino Uno connected to a PC via USB. 
  The Current build does all the following in a faked multi-thread fashion:
  + Runs a cylon/knightrider like status light
  + Reads current temperatures via temp sensors
  + Watches for motion in order to activate certain lights (relays)
  + Listens for new variables from web app to control lighting, etc (relays)
• Current working processing app for reading web based text file and passing those varibles along to the Ardunio via the USB connection
• Current web app build which works as a command center for the Arduino. The web app contains:
  + Web app designed for iPads that acts like a native app when saved to the desktop
  + PHP file that writes Web app output to a text file.
  + All linked assets for teh web app

This build is presented as is. URLs have been abstracted and will 
have to be updated to your own URLs in order to work properly. I offer
no warranties or garentees that this setup will work for you. It does work 
very well for me. The code is very large and has not been optimized. There 
are better ways of doing everything here but this is my first Arduino project.

Enjoy.
