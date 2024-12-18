# ss22-cyber-24
ss22-cyber-24 created by GitHub Classroom
Welcome to our Readme page. We are Cyber24 and the past couple weeks we worked on the creation of our startup. 

1.0 Problem Statement
Ensuring the safety and security of children is a significant concern for parents, particularly in environments where distance monitoring and timely alerts are critical. Conventional solutions like GPS trackers or mobile applications often lack immediate responsiveness or require a network connection, making them less reliable in certain situations.
Our project aims to address this issue by creating a low-cost, Bluetooth-based proximity alarm system. This solution ensures that both parents and children are alerted if the connection between their devices weakens or is lost, indicating an increased distance. By offering a simple and robust alternative, this system provides peace of mind to parents while enhancing IT security for their children.

2.0 Data Collection

3.0 Systems Mapping (Miro)

4.0 Value Proposition Canvas

4.1 Development of our Idea and prototype

4.2 Storyboard

4.3 Prototype

  4.3.1 Website

  4.3.2 Explanation prototype

This prototype is a compact and efficient system designed to enhance child safety by monitoring spacing between a child and a parent. 

Hardware: 

It is built using the following components:

1) ESP32 Microcontroller Boards: Two ESP32 boards serve as the core of the system, enabling Bluetooth communication and processing.
2) Test Boards: Each ESP32 is mounted on a test board, providing a stable platform for connecting the components.
3) KY006 Sound Buzzer Modules: Each board features a buzzer to emit audible alarms in case the devices lose connection.
4) LEDs with Resistors:
	4.1) The parent unit has a green LED, indicating an active connection.
	4.2) The child unit has a red LED, which lights up when the connection is lost.
5) Cables and Connectors: These are used to wire the components to the test board, ensuring seamless operation.
6) Power Supply: Small, portable power banks supply energy to each unit. Activating the device is as simple as pressing the power button on the power bank.


Software:

Development Environment:
Arduino IDE: Used for programming the ESP32 microcontroller.

Software Libraries:

BluetoothSerial: Enables Bluetooth communication between devices.
This project uses the BluetoothSerial library, which is licensed under the Apache License, Version 2.0. See the Apache License, Version 2.0 for more details.
GitHubLibrary for Soundtrack: https://github.com/xitanggg/-Pirates-of-the-Caribbean-Theme-Song/blob/master/Pirates_of_the_Caribbean_-_Theme_Song.ino
License Details: No restrictions on use or distribution; fully free for personal or commercial projects.

How It Works - Initial Setup:

The parent and child units are positioned near each other (approximately one meter apart).
When powered on (by pressing the powerbutton on the Powerbank), wait until the green LED on the parent unit lights up, signaling that the devices are successfully connected. (approximately 5-15 seconds (if not restart))

Use-Case:

The system continuously monitors the proximity between the two devices.
If the child moves beyond the designated range and the connection is lost:
- at the Parents Unit: 	The green LED will turn off, and the buzzer will produces an alert sound.
- at the Child Unit: 	The red LED will light up, and the buzzer will also play the soundtrack.

Power and Portability:

The system is highly portable, thanks to its compact design and the use of power banks. 
There is no need for external wiring or complex installation. 
The Powerbanks need to be charged after ~20 hours of usage.

4.4 bluetooth direction






