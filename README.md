# home-automation-system

## project overview 
This project is a prototype of the family automation system designed to provide centralized control for household appliances gratitude to IoT integration. The system allows users to monitor and control lights, fans and other remote electronic devices through mobile applications or web interface. It aims to improve energy efficiency, comfort and access, especially for the elderly and people with disabilities.
Architecture includes sensors and transmitters connected to microcontrollers, communicating with cloud services to access and control data in real time.

## components and apps used 
 Hardware Components
NodeMCU (ESP8266 Wi-Fi module)

Relay modules

DHT11 temperature and humidity sensor

Light sensors (LDR)

230V AC appliances (bulbs, fans, etc.)

Breadboard and jumper wires

Power supply (5V / USB)

📱 Software & Apps
Arduino IDE (for firmware development)

Blynk App / MIT App Inventor (for mobile app interface)

Firebase (optional for real-time database logging)

Thingspeak (for data visualization and analytics)

MQTT broker (like Mosquitto)
##  Libraries Used for Compilation
In the Arduino IDE, the following libraries are essential:

ESP8266WiFi.h – for Wi-Fi connectivity

BlynkSimpleEsp8266.h – for Blynk app integration

DHT.h – to interface with DHT11 sensor

Wire.h – I2C communication

Adafruit_Sensor.h – sensor handling

PubSubClient.h – MQTT protocol (optional)

FirebaseESP8266.h – for Firebase integration (optional)

To install these:

Open Arduino IDE

Go to Sketch → Include Library → Manage Libraries

Search and install the required libraries

## project outcome 
The remote control of the devices received through the mobile interface


 Moisture monitoring in real time



 Automatic lighting control is based on the level of lighting around
houses in real houses in real houses of real houses in real houses for real houses in real houses in real houses

## Conclusion
The prototype of the domestic system shows that the success of the IoT can be used to create a smart habitat. With simple components and open source platforms, we have achieved remote monitoring and control features. This system is modulated and can be expanded to include additional devices, security systems and AI automation for future development. 
 
## Circuit Diagram & Simulation
![Screenshot 2025-05-04 164231](https://github.com/user-attachments/assets/b40cf167-7545-4220-86ca-0b32b42c918d)



