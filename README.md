ArduinoTelnetServer
===================

Based on:

/*                             *
 *  Arduino Telnet Server      *
 *      7 July 2010            *
 *   Basic Arduino I/O via     *
 *  a command line interface   *
 *      by Steve Lentz         *
 *  stlentz[at]gmail[dot]com   *
 *                             *
 
 Updated 5 March 2012 to reflect change in EthernetServer class name.
 
 Quick Start Instructions:
 1) Set Ethernet address in code below.
 2) Compile and upload sketch.
 3) Connect Arduino to Ethernet.
    Make sure link light is on.
 4) Telnet to Arduino's IP.
 5) On some Telnet clients, hit return to wake up connection.
 6) When connected, type ? <cr> for help.  
 7) Try a simple command such as 'ar'. 
 
Other notes
Tested on Duemilanove with Ethernet Shield.  
Should work on compatible boards.
Tested with Win XP, OS X, and Debian Telnet clients.  
Compiles to about 9 KB, can be made smaller by removing 
  unneeded commands, help message, etc. 
I am an entirely self-taught C programmer; if you
  don't like my code, too bad ;-).  */  
