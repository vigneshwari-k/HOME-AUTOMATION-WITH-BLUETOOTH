# HOME-AUTOMATION-WITH-BLUETOOTH

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: VIGNESHWARI K

**INTERN ID**:CT04DH911

**DOMAIN**: EMBEDDED SYSTEMS

**DURATION**: 4 WEEKS

**MENTOR**: NEELA SANTHOSH

Description:
This project demonstrates a basic home automation system using an Arduino Uno that allows you to control electrical devices remotely through serial communication. The system simulates control of three devices: a light, a bulb, and a fan (DC motor). In the circuit, LEDs represent the light and bulb, while a DC motor represents the fan. Commands are sent from the serial monitor of the Arduino IDE to switch these devices on or off.
Each device is connected to a specific digital output pin on the Arduino. When the Arduino receives a designated character (via USB serial), it performs the corresponding action. Uppercase letters (A, B, C) turn devices ON, and lowercase letters (a, b, c) turn them OFF. For example, sending 'A' turns the light on, while 'a' turns it off. The motor connected to pin 5 simulates a fan, allowing the user to switch it on or off based on commands 'C' or 'c'.
code description:
The setup() function initializes pins as outputs and starts serial communication.
In the loop(), the Arduino waits for a command from the serial monitor.
When a command is received, the switch statement checks which device to control.
Each command turns a device ON or OFF and prints feedback in the serial monitor.
Applications:
Home Automation:
This system can be scaled up to control real-world appliances using relays, making it suitable for basic home automation.
Smart Control of Devices:
Integrate with Bluetooth or Wi-Fi (like ESP8266) to control devices via smartphone apps or over the internet.
Fan and Light Control in Rooms:
The motor simulates a fan and can be part of a ventilation or cooling control system, activated as needed.
Accessible Environments:
Allows elderly or disabled users to operate appliances easily via a simple command interface.
Prototyping Automation Ideas:
Acts as a foundation for more complex systems involving voice commands, sensors, or cloud-based monitoring.

#output



