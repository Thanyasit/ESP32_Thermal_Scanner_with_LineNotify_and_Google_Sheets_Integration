# ESP32_Thermal_Scanner_with_LineNotify_and_Google_Sheets_Integration
## Description

This program uses an ESP32 microcontroller to measure temperature through a K3 Thermal Scanner, and sends notifications via Line Notify if the temperature exceeds a certain threshold. Additionally, it saves the temperature readings to a Google Sheets document using IFTTT.<br><b>2022</b>

## Prerequisites

- ESP32 microcontroller
- K3 Thermal Scanner
- Arduino IDE
- WiFi network
- Line Notify API token
- IFTTT account with a Google Sheets applet
## Installing

1. Clone or download this repository to your local machine.
2. Open the <b>'esp32_thermal_scanner.ino'</b> file in the Arduino IDE.
3. Update the following variables with your own values:
- <b>'ssid:'</b> your WiFi network name
- <b>'LINE_TOKEN:'</b> your Line Notify API token
- <b>'event:'</b> the name of your IFTTT event
- <b>'key:'</b> your IFTTT key
4. Connect your ESP32 and K3 Thermal Scanner to your computer using a USB cable.
5. Upload the code to your ESP32 using the Arduino IDE.
6. Once the upload is complete, disconnect the USB cable and power the ESP32 using a battery or other power source.
7. The ESP32 will automatically connect to your WiFi network and start measuring temperature.

## Usage

The ESP32 will continuously measure temperature through the K3 Thermal Scanner and send notifications via Line Notify if the temperature exceeds 37.3°C. Additionally, it will save the temperature readings to a Google Sheets document using IFTTT.

If the temperature exceeds 150°C, the ESP32 will automatically restart.

## Example

<p align="center">
<img src="https://user-images.githubusercontent.com/77733903/226799242-4194fddf-b0b1-4441-aba0-e5331f416651.jpg" width="500">
</p>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
