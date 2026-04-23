---
title: "Buce: 6-Channel All-in-One WiFi LED PWM Controller"
image: /uploads/products/blc06mk1/gallery/buce-bottom-white-1.jpg
---

{{< brick_title >}}
# Buce - 6-Channel LED PWM Controller

Easy-to-use embedded 6-channel smart LED PWM controller.


![](/uploads/products/blc06mk1/gallery/buce-bottom-white-1.jpg)

{{< /brick_title >}}

{{< brick_image >}}

![](/uploads/products/blc06/features.jpg)

## Introduction

The Buce module integrates every high-end feature standard in professional reef and planted tank lighting, offering a level of control and precision that rivals any flagship LED fixture on the market.

It features six independent PWM dimming channels, allowing users to customize and control lighting effects wirelessly through our easy-to-use [Borneo Aqua Pro](/app).

Applications: aquatic lighting, photography lighting, home lighting and more.

{{< button "Get It on PCBWay Store" "https://www.pcbway.com/project/gifts_detail/6_Channel_Wi_Fi_PWM_LED_Dimmer_for_Aquariums_adb134c9.html" >}}

{{< /brick_image >}}

{{< brick_image2 >}}

![](/uploads/products/blc06mk1/block-diagram.svg)

## Quick Specs

- Micro-controller: ESP32-C3
- Channels: 6 independent PWM
- Driver Compatibility: Supports a wide range of Constant Current (CC) and Constant Voltage (CV) LED drivers.
- Dimming Levels: 4096
- PWM Frequency: up to 19.5 kHz (configurable)
- Input Voltage: 5–36 V
- Thermal Shutdown: >65 °C (configurable)
- Interfaces: 0.1"(2.54 mm) pin header
- Supported Peripherals: INA138/INA139 current sensor / push button / NTC / fan
- Dimensions: 22 × 30 mm

{{< /brick_image2 >}}

{{< brick_wide >}}

## Fully Open Source Hardware

Buce is an [OSHWA certificated](https://certification.oshwa.org/cn000017.html) open-hardware product.

[![](/uploads/products/blc06mk1/oshwa.png)](https://certification.oshwa.org/cn000017.html)

{{< tabs >}}

## Dimming

- Multi-stage programmable dimming with scheduling, manual, and temporary modes.
- Supports linear, logarithmic, gamma, exponential and CIE‑1931 curves.
- 4096 levels, soft start/shutdown, phase shifting to reduce peak driver current.
- Solar simulation using astronomical algorithms.  
- High-frequency PWM (up to 19 kHz) and phase shifting minimize flicker and noise.

---

## Integration and Thermal Management
- Built-in voltage regulator and power measurement; optional INA139 for current/power.  
- 3.3 V output for peripherals.  
- Fan driver (2‑wire and PWM fans) + PID control (default target 45 °C).  
- NTC input for temperature; emergency shutdown >65 °C.


---

## Other Features

* Automatic SNTP time synchronization.
* 0.1" (2.54mm) pin-header interface, convenient for DIY projects.
* Communicating using CBOR over CoAP/UDP offers both reliability and high performance
* Provides [Open-source Python API and examples](https://docs.borneoiot.com/borneopy).

{{< /tabs >}}

## Feature Comparison: Buce vs. Competitors

| Feature | Borneo Buce (BLC06) | TC420 / TC421 | Storm / Storm X | Bluefish Mini |
| :--- | :--- | :--- | :--- | :--- |
| **Device Category** | Logic Controller (Open-Source) | Power Driver (Finished Product) | Logic Controller (Legacy DIY) | Logic Controller (Cloud-Based) |
| **Output Type** | 3.3V Logic PWM | MOSFET Power Stage (CV) | 5V Logic PWM | PWM / 0-10V Analog |
| **Driver Requirement**| External Driver Required | No (Direct Drive LED Strips) | External Driver Required | External Driver Required |
| **Dimming Curves** | Linear, Log, CIE1931, Gamma | Linear Only | Linear Only | Linear / Custom |
| **Scheduling** | Multi-stage | Time-point based | 12-24hr Cycle | Multi-stage |
| **Sun Simulation**| Geo-location Based | Manual Timer Only | Manual Sunrise/Set | Geo-location Based |
| **Moonlight** | Geo-location Based | No | Yes (Basic) | Auto Moon Phase Sync |
| **Cloud Simulation**| Supported | No | Yes | Supported |
| **Lightning / Storm** | No | No | Yes | Yes |
| **Acclimation Mode**| Supported | No | No | Supported |
| **Channels** | 6 Channels | 5 Channels | 6 (Storm) / 16 (Storm X) | 6 Channels |
| **Dimming Resolution**| 12-bit (4096 Levels) | 8-bit (256 Levels/100 Steps) | 8-bit / 12-bit (Storm X) | 12-bit (4096 Levels) |
| **PWM Frequency** | Up to 19.5 kHz | ~1 kHz (Low Frequency) | ~1 kHz | Unknown |
| **User Interface** | Mobile App (Local WiFi + Cloud) | USB / Mobile App (TC421) | On-board LCD + Knob | Mobile App (Cloud Only) |
| **Temporary Mode** | App + Hardware Button | No | No | Yes (App) |
| **Telemetry & Safety**| PID Fan, Volt/Amp/Power Monitor | None | Fan Control (Manual) | None |
| **Open Source** | Full (HW, FW, & App) | Proprietary (Closed) | Proprietary (Closed) | Proprietary (Closed) |
| **Form Factor** | Coin-sized Module (22×30mm) | Large Metal Housing | Medium PCB with LCD | Small Plastic Case |
| **Price** | 💲💲 | 💲💲 | 💲💲💲 | 💲💲💲💲 |

## Pinout

![](/uploads/products/blc06mk1/gds.png)

## Usage Example

![](/uploads/products/blc06/bo-blc06.png)

## Dimensions

![Dimensions](/uploads/products/blc06/dimensions.svg)

---

## Resources

* Online Documentation & Datasheet: [docs.borneoiot.com](https://docs.borneoiot.com/hardwares/buce)
* GitHub Repo: [github.com/borneo-iot/borneo/borneo](https://github.com/borneo-iot/borneo/borneo)
* PCBWay Store: [Get it now on PCBWay store](https://www.pcbway.com/project/gifts_detail/6_Channel_Wi_Fi_PWM_LED_Dimmer_for_Aquariums_adb134c9.html)

---

## Gallery

{{< gallery dir="/uploads/products/blc06mk1/gallery" >}}

{{< /brick_wide >}}

{{< brick_cta >}}{{< /brick_cta >}}

