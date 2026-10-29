# disco-time
This is a simple networking monitoring tool, it is configured for the raspberry pi pico 2W and Raspberry pi 3B 

You will require:
- A functioning laptop/PC
- One red LED 
- 330 ohm Resistor 
- 5 Jumper cables (male to male)
- A passive buzzer
- Raspberry Pi Pico 2W
- Raspberry Pi 3B

The local server and tool is hosted on the raspberry pi itself and uses Wi-fi alongside wireshark/nmap to detect incoming inusual traffic, in the event of unusual traffic the red LED will light up and the buzzer will buzz in a steady rythmn

Once the unusual traffic has been ignored or the network individual has acknowleged, the RED LED will be kept on until the issue is handeled however the buzzer will stop ringing as to prevent annoyance.

Circut photos are provided and named accordignly as:

DEVICE_CIRCUTNum
PROGRAM_ProgramNum_Name


This is purely a passion project, credit will be given, alongside that it will forever remain open-sourced.

Made with love
Nullpin
