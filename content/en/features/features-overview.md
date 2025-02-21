---
title: Feature Overview
weight: 2
---


## Full stack open-source

- Schematic and PCB Layout design for the WiFi LED controller module (core board) using Horizon EDA
- Schematic and PCB Layout design for a 6-channel 57W lamp reference design
- Firmware based on the ESP-IDF framework
- The mobile app developed using Flutter

## Highly customizable modular design

- The core board of the LED controller module is only 2cm x 3.5cm, making it easy to integrate
- If using the core board is inconvenient, you can refer to the schematic to integrate the microcontroller and peripheral circuits into a custom PCB

## Component-based firmware architecture

- Independent board definitions, supporting different families of Espressif microcontrollers without code modifications, compatible with ESP32/ESP32-C3/ESP32-C5 and more;
- The firmware architecture uses a driver and initialization management framework similar to Zephyr RTOS, separating the underlying layer from application functionality
- Universal CoAP + CBOR underlying protocol, allowing the mobile app to support various devices such as lamps, dosing pumps, and thermometers;

## Feature-rich

- A standalone 6-channel PWM LED controller operable via a mobile app, requiring almost zero peripheral components
- Autonomous multi-stage sunrise/sunset graphical dimming and soft start for the module, with an easy setup mode
- Automatic time synchronization based on the SNTP protocol
- PID-based automatic cooling fan control and other protection features
- Python client library and demo scripts for module communication
- Optional peripheral INA139 current monitoring

## Budget-friendly

- The MCU uses the popular low-cost ESP32-C3 (6-channel edition) or ESP32 (10-channel edition), with no any custom or uncommon components
- Built-in voltage regulation circuit can directly drive the cheapest two-wire cooling fans, and also supports PWM speed-controlled fans
- The module uses pin headers by default, making it convenient for DIY enthusiasts

And much more, such as a dosing pump and pH monitor currently under development based on this firmware and app architecture. 

For more details, please checkout the online docs:

{{< button "Online Docs" "https://docs.borneoiot.com" >}}


