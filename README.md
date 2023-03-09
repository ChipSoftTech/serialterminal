A browser based serial terminal. No plugins. Vanilla javascript. 

I work with microcontollers alot and needed a light weight serial connected. In the latest verison of chrome a new serial API was exposed allowing javascript web applications to directly connect to serial devices from a web page.

The index.html file contains a bare bones serial terminal with fewer than 150 lines of code between the HTML, CSS and javascript. 

Instructions for use:
1) Load index.html in your browser (or upload to a web server)
2) Set baud speed from drop down.
3) click connect.
4) select serial device
5) Talk to your serial device from the built in serial console.


Full source here:
[Source](index.html)

Known to work in chrome, chromium and edge browsers.
Will not work in firefox or brave. 

Modified by Brian Carter from Chippewa Software Technology
Originally created by mmiscool as a simple example. 
ZanzyTHEbar has made some significant improvements and added a settings page exposing more of the connection settings along with doing an xterm.js implementation under the advanced button. 
