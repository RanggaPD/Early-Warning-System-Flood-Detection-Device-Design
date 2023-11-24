# Early-Warning-System-Flood-Detection-Device-Design
Early Warning System Flood Detection Device Design using NodeMCU ESP8266 and HCSR04 ultrasonic sensor connected to Thingspeak and automatic telegram message as alarm

To create a prototype of this monitoring device, two devices are required: Hardware and Software. Hardware devices consist of NodeMCU (ESP 8266), LED lights, buzzers, HC-SR04 ultrasonic sensors, breadboards, jumper cables, power banks, and USB cables. Software devices, on the other hand, consist of a program that will run the system's functionality so that data can be read and sent to the ThingSpeak website and Telegram bot.

The power supply circuit used to run the prototype is connected to a laptop using a USB cable or a power bank. This power supply circuit is used to supply power to the components, namely the NodeMCU (ESP 8266). The main component circuit is used to monitor water level. This circuit will send sensor reading data to the ThingSpeak database. When the sensor reads the upper limit of the dangerous water level, it will send a chat via Telegram, send data to the ThingSpeak database to be forwarded to the output component to turn on the warning siren.
