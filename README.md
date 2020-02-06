# Consumer Electronics (2018)
## Smart Alarm System: IoT & MQTT

Main module (Raspberry Pi 3B) communicating via WiFi using MQTT protocol with sensor modules based on SparkFun boards (ESP8266 Thing).
If an intruder is detected a notification is sent to the IFTTT application and a video from the camera to the email. A link to visualize the video streaming is included in the email (VPN connection to the internal network is required).

- **Main module:** LCD Display, keypad matrix, RFID sensor, video camera, leds and speaker. (Python v3.x)

- **Sensors:** PIR, magnetic door and distance. (C and Arduino)



Project developed collaboratively with [Sergio Pérez][1]

[1]: https://github.com/spmorillo
