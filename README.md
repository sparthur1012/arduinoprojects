HDT11 Source

A C++ project for monitoring temperature and humidity using Arduino Uno and the DHT11 sensor. 
 
  Overview 
  
HDT11 Source is a C++ project designed to measure and monitor temperature and humidity using the DHT11 sensor with an Arduino Uno. 
The goal of this project is to provide a reliable and extensible foundation for environmental monitoring applications, from academic experiments to IoT projects. 
 
  Features 
 
Reads temperature (°C) and humidity (%) values from the DHT11 sensor. 
Displays sensor data in real time via Serial Monitor. 
Easy-to-use and extendable C++ code structure. 
Compatible with Arduino IDE. 
 
  Hardware Requirements 
 
Arduino Uno R3 (or compatible board) 
 
DHT11 temperature & humidity sensor 
Jumper wires 
Breadboard 
Software Requirements 
Arduino IDE 
DHT sensor library for Arduino: 
Install via Arduino IDE → Library Manager → Search for "DHT sensor library" by Adafruit 
 
  Installation & Setup 
 
1.	Clone this repository: 
 
git clone https://github.com/yourusername/Max-Steel.git 
 
2.	Open the project in Arduino IDE. 
3.	Install the required DHT sensor library if not already installed. 
4.	Connect your Arduino Uno with the DHT11 sensor as follows: 
VCC → 5V 
GND → GND 
DATA → Digital Pin (e.g., D2) 
5.	Upload the sketch to your Arduino board. 
Usage 
1.	Open the Serial Monitor (baud rate: 9600). 
2.	Monitor real-time temperature and humidity data. 
  Example output: 
 
Temperature: 25°C   
Humidity: 60% 
 
 
 
  Future Improvements 
 
Support for multiple DHT sensors. 
Integration with LCD Display or OLED module. 
IoT connectivity using ESP8266/ESP32. 
Data logging to SD card or cloud service. 
  
  Contributing 
Contributions are welcome! Feel free to: 
Open issues for bugs or suggestions 
Submit pull requests with improvements 
