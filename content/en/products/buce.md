---
title: "Buce: 6-Channel All-in-One WiFi LED PWM Controller"
image: /uploads/products/blc06mk1/gallery/buce-bottom-white-1.jpg
---

{{< brick_title >}}
# Buce - 6-Channel LED PWM Controller

**Buce is launching a crowdfunding campaign on Crowd Supply! Subscribe to the campaign page to receive updates, shipping information, and early-backer announcements.**


{{< button_cs "Subscribe on Crowd Supply" "https://www.crowdsupply.com/borneo-iot/buce-aquarium-led-controller" >}}


![](/uploads/products/blc06mk1/gallery/buce-bottom-white-1.jpg)

{{< /brick_title >}}


{{< brick_image >}}

![](/uploads/products/blc06mk1/gallery/blc06mk1-1.jpg)

## Introduction

Buce (Model BLC06) is an open-source, 6‑channel WiFi LED PWM controller for makers and engineers.

Buce can be controlled via the [BorneoIoT mobile app](/products/app) (iOS & Android) for real‑time channel control, presets & scenes, scheduling, OTA firmware updates, and Wi‑Fi setup/device discovery.

It is optimized for aquarium lighting but fits many LED projects. Connect a [constant-current LED driver](/products/bacopa) and high-power LEDs — Buce handles the control and scheduling.

{{< /brick_image >}}

{{< brick_features >}}

## Features

---

![](/img/icons/material-symbols/200/rounded/devices.svg)
### All-in-One Controller

Integrates WiFi/Bluetooth, LED PWM output, temperature/current/voltage monitoring, fan drive, buttons, indicator lights, and a built-in 36V voltage converter for comprehensive control.

---

![](/img/icons/material-symbols/200/rounded/performance_max.svg)
### State of The Art Hardware

On a coin-sized footprint, maximizes the potential of the ESP32-C3 microcontroller, providing 6 hardware dimming channels, achieving 4096-level smooth dimming, and supporting up to 19kHz phase-shifted PWM output.

---

![](/img/icons/material-symbols/200/rounded/design_services.svg)
### Feature-Rich

Supports all commercial-grade lighting functions including multi-stage programmable dimming, location-based solar simulation, and soft start for professional applications.

---

![](/img/icons/material-symbols/200/rounded/timer.svg)
### Safety

Equipped with over-temperature and over-power protection, along with PID adaptive cooling fan control to ensure reliable and safe operation.

---

![](/img/icons/material-symbols/200/rounded/auto_fix.svg)
### DIY Friendly

Features a 0.1" pin-header interface for easy DIY projects and customization, requiring minimal peripheral circuits. Directly connect LED driver circuits and main power supply to create intelligent high-power LED lights.

---

![](/img/icons/material-symbols/200/rounded/auto_awesome_mosaic.svg)
### Open-Source

Buce is fully open-source hardware, certified by OSHWA, with open-source Python API, examples, and documentation available for easy integration and customization.

{{< /brick_features >}}

{{< brick_image2 >}}

![](/uploads/products/blc06mk1/block-diagram.svg)



## Quick specs
- Channels: 6 independent PWM
- Dimming levels: 4096
- PWM freq: up to 19 kHz (configurable)
- Input voltage: 5–36 V
- Size: 22 × 30 mm
- Thermal shutdown: >65 °C (configurable)
- Interfaces: `0.1"` pin header, optional INA139, external button

{{< /brick_image2 >}}

{{< brick_wide >}}

## Fully Open Source Hardware

Buce is an [OSHWA certificated](https://certification.oshwa.org/cn000017.html) open-hardware product.

[![](/uploads/products/blc06mk1/oshwa.png)](https://certification.oshwa.org/cn000017.html)

## Applications

* **Aquarium Lighting**
    Aquarium hobbyists can use Buce to simulate natural lighting environments, promoting the health and growth of aquatic plants or corals.
* **Photography Lighting**
    Photographers can set up dynamic lighting scenes to capture stunning images with precise control over brightness and color, perfect for studio or outdoor shoots.
* **Home Lighting**
    DIY enthusiasts can integrate Buce into their smart home systems to create personalized lighting ambiances for different rooms and occasions, with smooth transitions throughout the day.
* **And More**
    Let your creativity shine.

{{< tabs >}}

## Dimming

- Multi-stage programmable dimming with scheduling, manual, and temporary modes.
- Supports linear, logarithmic, gamma, exponential and CIE‑1931 curves.
- 4096 levels, soft start/shutdown, phase shifting to reduce peak driver current.
- Solar simulation using astronomical algorithms.  
- High-frequency PWM (up to 19 kHz) and phase shifting minimize flicker and noise.

### Supported Brightness Correction Curves

![](/uploads/products/lyfi/borneo-led-curves.svg)

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

## Pinout

![](/uploads/products/blc06mk1/gds.png)

## Typical Peripheral Circuit Diagram

![](/uploads/products/blc06mk1/peripherals.svg)


---

## Resources

* Online Documentation & Datasheet: [docs.borneoiot.com](https://docs.borneoiot.com/hardwares/buce)
* GitHub Repo: [github.com/borneo-iot/borneo/borneo](https://github.com/borneo-iot/borneo/borneo)

---

## Gallery

{{< gallery dir="/uploads/products/blc06mk1/gallery" >}}

---

{{< /brick_wide >}}

{{< brick_cta >}}{{< /brick_cta >}}

