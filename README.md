# IoT Home Automation System

A prototype smart home system that controls appliances remotely and switches lights automatically based on room brightness.

## Features
- Remote on/off control of lights and fans from a mobile app
- Real-time temperature and humidity monitoring (DHT11)
- Automatic lighting control using an LDR (light sensor)
- Wi-Fi control via [Blynk / MIT App Inventor]

## Hardware
- NodeMCU ESP8266
- Relay module
- DHT11 sensor
- LDR (light sensor)
- [Bulb / fan / LEDs used for testing]
- Breadboard, jumper wires, 5V USB supply

## Software
- Arduino IDE (C/C++)
- Libraries: ESP8266WiFi, [BlynkSimpleEsp8266], DHT, Adafruit_Sensor

## How It Works
1. The app sends on/off commands over Wi-Fi to the NodeMCU.
2. The NodeMCU switches appliances through the relay.
3. The LDR detects ambient light and switches the light automatically.
4. DHT11 readings are shown live in the app.

## Setup
1. Wire the circuit as shown below.
2. Install the libraries via Sketch → Include Library → Manage Libraries.
3. Add your Wi-Fi name and app token in the code.
4. Upload to the board and control it from the app.

## Results
Appliances were controlled remotely, temperature and humidity were monitored in real time, and lighting switched automatically based on ambient light. 
 
## Circuit Diagram & Simulation
![Screenshot 2025-05-04 164231](https://github.com/user-attachments/assets/b40cf167-7545-4220-86ca-0b32b42c918d)

## Future Improvements
- Voice control
- Energy usage tracking
- Integration with the security system



