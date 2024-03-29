# RGB LED Control Web Server

This project is a simple example of controlling the colors of an RGB LED via a web browser using an ESP32 microcontroller.

## Connections
- Red LED Pin: GPIO 23
- Green LED Pin: GPIO 22
- Blue LED Pin: GPIO 21

## Setup
1. Open Arduino IDE.
2. Install the required libraries (WiFi, WebServer).
3. Add your WiFi connection details to the `ssid` and `password` variables.
4. Upload the code to your ESP32 board.

## Usage
1. Connect the ESP32 to a power source and wait for it to connect to the WiFi network.
2. Check the ESP32's IP address from the serial monitor.
3. Open your web browser and visit the ESP32's IP address (e.g., `http://192.168.1.100`).
4. Control the colors of the RGB LED using the color palette.

## Notes
- Use the color palette on the web browser to control the colors.
- Monitor the RGB values via the console output.
