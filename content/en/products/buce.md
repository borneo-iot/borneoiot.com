---
title: "Buce: 6-Channel All-in-One WiFi LED PWM Controller"
image: /uploads/products/blc06mk1/gallery/blc06mk1-cover.jpg
---

{{< brick_title >}}
# Buce: 6-Channel All-in-One WiFi LED PWM Controller

![](/uploads/products/blc06mk1/gallery/blc06mk1-cover.jpg)

{{< /brick_title >}}


{{< brick_image >}}

![](/uploads/products/blc06mk1/gallery/blc06mk1-1.jpg)

## Introduction

Buce (Model BLC06) is an innovative, open-source, 6-channel, all-in-one WiFi LED PWM embedded controller module. It’s designed for makers and engineers passionate about DIY LED projects, especially in aquariums.

This versatile controller provides six independent PWM channels, allowing users to customize and control lighting effects wirelessly through our **[open-source mobile app](app)**. With multi-segment dimming capabilities, Buce can simulate natural daylight transitions, such as sunrise and sunset, enhancing the visual experience in various settings.


{{< /brick_image >}}


{{< brick_wide >}}

## Fully Open Source Hardware

Buce is an [OSHWA certificated](https://certification.oshwa.org/cn000017.html) open-hardware product.

[![](/uploads/products/blc06mk1/oshwa.png)](https://certification.oshwa.org/cn000017.html)

## Buce Is Not a Dev Board

Buce is not a traditional development board! We handle the hard 'dev' stuff, such as writing tens of thousands of lines of code for the firmware and mobile app, so you don’t have to. (Of course, if you’d like to contribute to this open-source project, we’d love to have you on board.)

Just connect Buce to a [constant-current LED power driver](bacopa) and attach some high-power LED chips, and you've got yourself a smart, mobile app-controlled, multi-segment dimming light fixture.

### Applications

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

- The firmware and mobile app support advanced programmable multi-stage dimming.
- Supports linear, logarithmic, gamma, exponential and CIE-1931 dimming algorithms.
- Supports scheduling mode, manual mode, and temporary appreciation mode.
- 6 independent PWM dimming channels.
- High dimming frequency (default 19kHz), ensuring no flickering is visible to the naked eye or detected by recording devices,
  while completely eliminating noise from the circuit.
- Supports phase shifting for PWM signal, significantly reducing the peak current of the LED driver when not running at full power.
- 4096 dimming levels.
- Fully automated solar illumination intensity simulation based on astronomical algorithms.
- Soft start and soft shutdown features to avoid startling aquatic life.

---

## Highly Integrated

* Compact size of only 22×30mm.
* Built-in voltage regulator, allowing direct input of 5~36V voltage.
* Built-in power voltage measurement circuit, with the option to connect an INA139 for current and power measurement.
* Capable of outputting 3.3V voltage to power external devices.
* Supports an external interactive button, which can be used for temporary appreciation mode or to reset network connection information.
* Built-in Thermal Management for High-Power LEDs:
    * Integrated NTC temperature sensing circuit that can directly connect to a 3950 10kΩ NTC.
    * Integrated fan driver circuit, capable of directly connecting to 12V two-wire fans and PWM-controlled fans.
      Two-wire fans can set speed through voltage adjustment.
    * Fan cooling control via PID algorithm (default set to maintain 45°C, configurable via software).
    * Automatic emergency shutdown occurs if the NTC temperature exceeds 65°C.

---

## Other Features

* Automatic SNTP time synchronization.
* 0.1" (2.54mm) pin-header interface, convenient for DIY projects.
* Communicating using CBOR over CoAP/UDP offers both reliability and high performance
* Provides [Open-source Python API and examples](https://docs.borneoiot.com/borneopy).

{{< /tabs >}}

## Pinout

![](/uploads/products/blc06mk1/gds.png)

## Block Diagram

![](/uploads/products/blc06mk1/block-diagram.svg)

## Typical Peripheral Circuit Diagram

![](/uploads/products/blc06mk1/peripherals.svg)

---

## Resources

* Online Documentation & Datasheet: [docs.borneoiot.com](https://docs.borneoiot.com/hardwares/buce)
* GitHub Repo: [github.com/borneo-iot/borneo/borneo](https://github.com/borneo-iot/borneo/borneo)



## Gallery

{{< gallery dir="/uploads/products/blc06mk1/gallery" >}}

{{< /brick_wide >}}
