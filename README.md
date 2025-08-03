
## Temperature Monitoring

📌 Introduction:

This project is an IoT-based temperature and humidity monitoring system built using NodeMCU (ESP8266) and DHT11 sensor. The system monitors environmental conditions, turns on an LED alert if the temperature exceeds a certain limit (e.g., 30°C), and sends live data to ThingSpeak via Wi-Fi.

Description:
Temperature Monitoring System with Wi-Fi Upload (NodeMCU + DHT11 + ThingSpeak)


## Circuit overview

This IoT-based temperature monitoring system is built using the NodeMCU ESP8266 board, a DHT11 temperature and humidity sensor, an IR obstacle sensor, and an LED indicator.

Component Required:

NodeMCU ESP8266 WiFi module

DHT11 Temperature and Humidity Sensor

IR Obstacle Detection Sensor

5mm Red LED

Jumper wires

Breadboard (optional)

USB cable for power and programming


## How It Works
DHT11 sensor reads temperature and humidity every 2 seconds.

If temperature exceeds 30°C, the LED turns ON to indicate a warning.

All readings (temperature, humidity, and LED state) are sent to ThingSpeak over Wi-Fi.

The data is viewable in real time on your ThingSpeak channel dashboard.


## Output 
The system continuously reads temperature and humidity from the DHT11 sensor.

If the temperature exceeds 30°C, an LED automatically turns ON as a visual alert.

All readings are sent to ThingSpeak cloud platform using Wi-Fi.

On the ThingSpeak dashboard:

Field1 shows the temperature in °C

Field2 shows the humidity percentage

Field3 shows LED status (1 = ON, 0 = OFF)

Data updates every 10 seconds, allowing for real-time monitoring from anywhere.

![1](https://github.com/user-attachments/assets/6a782a34-adae-4201-a43e-55283e8f73ca)



## Future Scope
Web Dashboard:

Create a custom web page to display the data in real-time using HTML, CSS, and JavaScript (instead of only ThingSpeak).

Mobile App Control:

Use Blynk app or MIT App Inventor to remotely monitor data and control the LED using your smartphone.

Multiple Sensor Integration:

Add other sensors like:

IR sensor for fire or obstacle detection

Gas sensor for LPG or smoke alert

Rain sensor for weather monitoring