# MOXA-Comms
Testing communications with the MOXA NPORT W2250A wireless serial device server. Main Goal is to get TCP Server mode working for each serial port. 

##VI's

###Serial only.vi

Communications with Group3 via MOXA when setup for Real COM (successful)

###TCP-serial.vi

Using TCP sub-VI's to communicate with Group3 (unsuccessful)

###TCP-VISA.vi

Using VISA sub-VI's for TCP communications to work with Group3 via Moxa (successful). In this case Group3/MOXA was set up for TCP Server.

###TCP-VISA_omega.vi

VI used to work out kinks in communicating with Omega (successful)

###Ionizer_Monitor_test.vi

Prototype of future Ionizer stage monitoring program to test functionality of MOXA box

##Screen Shots

###TCP-VISA_screencap.JPG

Picture of "workaround" for Omega's wonkiness

###Omega-settings.JPG

Terminal server settings for Omega CNi854-EI. 