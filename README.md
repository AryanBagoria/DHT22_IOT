# Arduino IoT Cloud Temperature & LED Control

This project connects an Arduino to the Arduino IoT Cloud to monitor temperature using a **DHT22 sensor** and control an onboard LED.

## Features

* **Temperature Monitoring:** Reads and sends temperature data (in °C) from a DHT22 sensor to the Arduino IoT Cloud.
* **LED Control:** Allows remote control of the built-in LED via the Arduino IoT Cloud dashboard.

## Setup

1.  **Hardware:**
    * Arduino board
    * DHT22 temperature sensor connected to **Digital Pin 7**.
2.  **Software:**
    * Configure your **`arduino_secrets.h`** and **`thingProperties.h`** files with your IoT Cloud credentials and variable definitions (already handled by Arduino IoT Cloud).
    * Ensure you have the **DHT sensor library** installed in your Arduino IDE.

## Usage

Once uploaded, the Arduino will continuously read temperature data and send it to your configured Arduino IoT Cloud dashboard. You can also toggle the LED from the dashboard.
