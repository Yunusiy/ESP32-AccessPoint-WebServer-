## ESP32 Web Server with Access Point

This repository contains code for an ESP32-based web server that serves a simple web page allowing users to control an LED connected to the ESP32's GPIO pin. The ESP32 acts as an Access Point, allowing clients to connect directly to it and control the LED through a web interface.

### Features:
- **Access Point Mode:** The ESP32 creates its own Wi-Fi network, allowing clients to connect directly to it without the need for an existing network infrastructure.
- **Web Interface:** Clients can control the state of an LED via a simple web page served by the ESP32.
- **On/Off Control:** Users can toggle the state of the LED on and off with the click of a button on the web interface.

### Requirements:
- [Arduino IDE](https://www.arduino.cc/en/software) or PlatformIO with ESP32 support.
- ESP32 development board.
- LED and a current-limiting resistor (if needed) connected to GPIO pin 2 of the ESP32.

### Getting Started:
1. Clone this repository to your local machine.
2. Open the code in Arduino IDE or PlatformIO.
3. Replace the placeholder SSID and password in the code with your desired Wi-Fi credentials.
4. Upload the code to your ESP32 development board.
5. Power up the ESP32 board and connect to the Wi-Fi network named "ESP32-Access-Point" with the configured password.
6. Open a web browser and navigate to the IP address shown in the Serial Monitor to access the web interface.
7. Toggle the LED state using the ON/OFF buttons on the web page.
