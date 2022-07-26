# task2
كتابة خوارزمية تشغل قطعة ESP32

Installing ESP32 Add-on in Arduino IDE:
1. In your Arduino IDE, go to File> Preferences
2. Enter the following into the “Additional Board Manager URLs” field:

https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
Then OK.
3. Open the Boards Manager. Go to Tools > Board > Boards Manager…
4. Search for ESP32 and press install button for the “ESP32 by Espressif Systems“
That's it!

**Testing the Installation**

Plug the ESP32 board to your computer. With your Arduino IDE open, follow these steps:

1. Select your Board in Tools > Board menu (in my case it’s the DOIT ESP32 DEVKIT V1)
2. Select the Port 
3. Open the following example under File > Examples > WiFi (ESP32) > WiFiScan
4. A new sketch opens in your Arduino IDE
5. Press the Upload button in the Arduino IDE. 
6.  “Done uploading.” message.
7. Open the Arduino IDE Serial Monitor at a baud rate of 115200:
8. Press the ESP32 on-board Enable button
