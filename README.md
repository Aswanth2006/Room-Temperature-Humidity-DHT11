# Room-Temperature-Humidity-DHT11
Arduino project to measure room temperature &amp; humidity using DHT11 sensor
# Room Temperature & Humidity Monitor (DHT11 + Arduino)

📌 This project measures **temperature and humidity** of a room using a **DHT11 sensor** and Arduino.  
The data is displayed on the Serial Monitor.

## 🔧 Components
- Arduino UNO
- DHT11 Sensor
- Jumper wires
- Breadboard

## ⚡ Circuit
- VCC → 5V
- GND → GND
- Data → Pin 2

## 🖥 Arduino Code
The code is inside `DHT11_Project.ino`.  
It uses the `DHT` library to read data from the sensor.

## 📊 Example Output
Humidity: 55.00 % | Temperature: 28.50 °C | 83.30 °F

## 🚀 Future Improvements
- Display data on LCD (16x2) or OLED
- Upload data to IoT platform (ThingSpeak, Blynk, etc.)
