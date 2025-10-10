---
title: 'Our Firmware Now Supports the Seeed XIAO-ESP32C3 Module'
image: /uploads/photos/assets/xiaoc3.jpg
date: 2025-10-08 00:00:00
tags:
  - firmware
  - aquarium
  - iot
  - xiao-esp32c3
---

We're excited to announce that our firmware now supports the renowned Seeed XIAO-ESP32C3 module! This means users eager to test our firmware and mobile app can now do so using this module, without waiting for our dedicated controller to launch.

## Why the XIAO-ESP32C3?

The Seeed XIAO-ESP32C3 is a compact and powerful development board based on the ESP32-C3 chip. It features a USB-OTG interface for easy firmware flashing and debugging. For users looking to quickly get started with our system, this is an ideal choice.

## Supported Features

While the XIAO-ESP32C3 lacks all the external peripherals of our dedicated controller, our firmware profile provides the following core features:

1. **6 Independent LED PWM Channels**: 6 separate LED dimming channels. Your LED driver circuit should include pull-down resistors to avoid large inrush currents at power-up.
2. **Fan PWM Output**: A PWM output for fan control. Since the NTC thermistor support circuit is absent, you can only set the fan PWM duty cycle manually in the app; the PID closed-loop automatic fan-speed control from our dedicated controller is not available.
3. **User Button**: A user button for temporary light-on (short press) and Wi-Fi reset (long press). This reuses the XIAO-ESP32C3's built-in "Boot" button, or you can wire an external button from the module's D9 pin to GND.

## Pinout

Here's the pin assignment for our firmware on the XIAO-ESP32C3:

| Pin | Function             | Notes                                                                 |
|-----|----------------------|-----------------------------------------------------------------------|
| D1  | LED PWM Channel 0    |                                                                       |
| D2  | LED PWM Channel 1    |                                                                       |
| D3  | LED PWM Channel 2    |                                                                       |
| D4  | LED PWM Channel 3    |                                                                       |
| D5  | LED PWM Channel 4    |                                                                       |
| D6  | LED PWM Channel 5    |                                                                       |
| D7  | Fan PWM Output       | Uses standard 25 kHz PWM                                              |
| D9  | User Button          | Shared with XIAO-ESP32C3's "Boot" button                              |

## How To Get It Started

1. Connect the XIAO-ESP32C3 using a USB cable.
2. Flash the firmware using our web-based flasher: [flasher.borneoiot.com](https://flasher.borneoiot.com)
    - Just select the firmware file and follow the on-screen instructions to flash your XIAO-ESP32C3 (no local program required).

After flashing, open our mobile app and use the "Add New Device" function to register it.

## Start Your Aquarium Lighting Project

This support allows you to explore and test our firmware before our dedicated controller launches. Whether for reef tanks, planted aquariums, or custom lighting systems, the XIAO-ESP32C3 helps you get up and running quickly.

We look forward to your feedback and ideas! If you have any questions, feel free to reach out.