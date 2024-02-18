:Author: riccardos07
:Email:
:Date: 02/12/2023
:Revision: version# 1
:License: Public Domain

= Project: {Temp and humidity with set point trigger to send notification}

Describe your project

== Step 1: Installation
Please describe the steps to install this project.

For example:

1. download the c++ file
2. go to iot arduino cloud
3. create thing and dashboard
4. add a device(uno r4 wifi board in this case or if modified then configure on the cloud)
5. gather dht 11 and also lcd 16x2 display with 4 pin configuration
6. connect the board to wifi
7. create the variables for the dashboard
8. add the variable to the dashboard
9. make an led for the alarm, two guages for temp and humidity, create setpoint slide and make sure it is read write
10. configure wifi and check connection with board
11. get the IFTTT app for FREE on your phone, get an adress linked to your email and number for notification automation
12. plug it into the code
13. get the iot remote app on your phone
14. set it up with your email and account for it to work properly and so you can view the data from remote
15. print case stl and or get it printed, the stl i have is not a gcode so you need to slice it first with a slicer like cura or any other will do

== Step 2: Assemble the circuit

Assemble the circuit following the diagram layout.png attached to the files part

== Step 3: codes and setup

Upload the code contained in this sketch on to your board

=== Folder structure

....
 sketch123                => Arduino sketch folder
  ├── Stay_cool_Feb_24.ino     => main Arduino file
  ├── case stl(x2 as there is top and bottom)     => stl for case printing
  ├── wiring sketch doen on tinkercad     => for wiring
  └── ReadMe.adoc     => this file
....

=== Contributing
To contribute to this project please contact: riccardo.spada2007@gmail.com

=== BOM
Add the bill of the materials you need for this project.
around 40 usd

|===
| ID | Part name | Quantity
| display | lcd display | 1       
| sensor | DHT 11 | 1        
| board | Arduino uno r4 wifi | 1  
| wires | jumper cable | 9 (2xmale-male, 7xmale-female)
| connections | breadboard | 1  
|===


=== Help
This document is written in the _AsciiDoc_ format, a markup language to describe documents. 
If you need help you can search the http://www.methods.co.nz/asciidoc[AsciiDoc homepage]
or consult the http://powerman.name/doc/asciidoc[AsciiDoc cheatsheet]
