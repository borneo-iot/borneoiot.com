---
title: "Colorata: 10-Channel All-in-One WiFi LED PWM Controller"
image: /uploads/products/blc10mk3/gallery/blc10mk3-cover.jpg
---

Colorata (Model BLC10MK3) is our best 10-channel, all-in-one, WiFi LED PWM embedded controller module, developed for passionate engineers and lighting product manufacturers. Colorata is the "Pro" version of our highly successful 6-channel model, [Buce](./buce). It offers enhanced and superior features in every aspect while still maintaining a highly affordable cost.


## Applications

Colorata integrates all the necessary hardware and software for high-end reef aquarium LED lights in the smallest form factor and at the low cost. It has simple peripheral circuitry, making it super easy to embed into products.

* High-end aquarium lighting.
* Photography lighting.
* And more.

{{< tabs >}}

## Hardware

* ESP32 MCU
* LED PWM channels: 10
* Ten independent PWM dimming channels, with software-configurable dimming frequency (default 24kHz), 10-bit 1024-level duty cycle range.
* Supports phase shifting for PWM signal, significantly reducing the peak current of the LED driver when not running at full power.
* NTC temperature sensing channels: 4
* LED indicator: RGB
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

---

## Software and Firmware

* **Dimming**
  * The firmware and mobile app support advanced programmable segmented dimming functions, including features like sunrise and sunset simulation. 
  * Supports linear, logarithmic, and CIE-1931 dimming algorithms.
  * Supports scheduling mode, manual mode, and temporary appreciation mode.
* **Thermal Management**
  * Automatic emergency shutdown occurs if the NTC temperature exceeds 65°C.

{{< /tabs >}}


## Comparison Table

<style>
table {
    border-collapse: collapse;
    width: 100%;
}

th, td {
    border-bottom: 0.04rem solid rgba(0,0,0,0.15);
    padding: 1pt;
}

th {
    background-color: rgba(0,0,0,0.05);;
}

</style>

|  | **Buce** | **Colorata**    |
|:---------------|:-----|:----- |
| **Dimensions** | 30×22mm | **35×22mm** |
| **MCU** | ESP32-C3 | **ESP32** |
| **LED PWM Channels** | 6 | **10** |
| **NTC Channels** | 1 | **4** |
| **PWM Fan** | YES | **YES** |
| **Two-Wire Fan** | YES | **YES** |
| **Indicator LED** | Single-color LED | **RGB LED** |
| **External Indicator** | NO | **YES** |
| **RTC (Real-Time Clock)**  | ESP32-C3 Built-in | **PCF8563**    |
| **RTC Battery**  | NO | **YES**    |
| **Press Button**  | YES | **YES**    |
| **Extra GPIO Pins**  | NO | **YES**    |
| **Interface** | 2×7 Pin, 0.1"(2.54mm) Pitch, TH Pin-header | **2×15 Pin, 0.05"(1.27mm) Pitch, SMD Pin-header** |
