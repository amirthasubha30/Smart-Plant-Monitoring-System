Overview
This project enables monitoring of temperature and humidity levels of a plant environment using the DHT11 sensor. It utilizes the Blynk platform to provide real-time data visualization and alerts for temperature variations.

Hardware Requirements
NodeMCU ESP8266 board
DHT11 temperature and humidity sensor
Jumper wires
Software Requirements
Arduino IDE
Blynk app (for data visualization and alerts)
Installation Instructions
Connect the DHT11 sensor to the digital pin 2 of the NodeMCU ESP8266 board.
Install the Blynk app on your smartphone and create a new project.
Generate an authentication token in the Blynk app.
Replace the placeholders in the code with your WiFi credentials and Blynk authentication token.
Upload the provided code to the NodeMCU ESP8266 board using the Arduino IDE.
Run the Blynk app and connect it to the created project using the authentication token.
Usage
Ensure all connections are properly set up.
Power on the NodeMCU ESP8266 board.
Open the Blynk app and monitor the temperature and humidity readings in real-time.
Receive alerts if the temperature exceeds 30 degrees Celsius.
Code Explanation
The code initializes the DHT11 sensor and connects to the Blynk server.
It reads temperature and humidity values from the sensor and sends them to the Blynk app for visualization.
If the temperature exceeds 30 degrees Celsius, an alert is sent to the Blynk app.
Real-time temperature and humidity readings are displayed on the Blynk app.
