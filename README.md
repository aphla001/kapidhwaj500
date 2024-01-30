# Kapidhwaj 500 - WiFi-Controlled Robot Car

## Overview:

Welcome to Kapidhwaj 500, your budget-friendly WiFi-controlled robot car! This repository contains all the necessary files to get your robot up and running. Follow the instructions below to upload the code to your NodeMCU and make necessary configuration changes.

## Uploading Code to NodeMCU:

### Prerequisites:

- [Arduino IDE](https://www.arduino.cc/en/software) installed on your computer.
- NodeMCU drivers installed on your computer.

### Instructions:

1. Open Arduino IDE.
2. Go to **File > Preferences**.
3. In the Additional Boards Manager URLs field, add the NodeMCU board manager URL: `http://arduino.esp8266.com/stable/package_esp8266com_index.json`.
4. Click **OK** to close the Preferences window.
5. Go to **Tools > Board > Boards Manager**.
6. Search for "esp8266" and install the "esp8266" board by ESP8266 Community.
7. Select your NodeMCU board: **Tools > Board > NodeMCU 1.0 (ESP-12E Module)**.
8. Choose the appropriate COM port: **Tools > Port > [Select Your COM Port]**.

### Uploading Code:

1. Open the provided `Kapidhwaj500.ino` file in Arduino IDE.
2. Ensure the correct board and COM port are selected.
3. Click the right arrow button (**Upload**) to compile and upload the code to your NodeMCU.

## Configuring WiFi Credentials:

In the `Kapidhwaj500.ino` file, you will find the following lines:

```cpp
const char* ssid = "YourSSID";
const char* password = "YourPassword";
```

Replace "YourSSID" with your WiFi network name (SSID) and "YourPassword" with your WiFi password.

## Troubleshooting:

If you encounter any issues during the upload or configuration process, refer to the [troubleshooting section](#troubleshooting) in the `Kapidhwaj500.ino` file.

## Contributing:

We welcome contributions! If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.

## License:

This project is licensed under the [MIT License](LICENSE).
