---
title: "Colorata: 10-Channel All-in-One WiFi LED PWM Controller"
image: /uploads/products/blc10mk3/blc10mk3-white-2.jpg
---

{{< brick_title >}}
# BLC10 LED PWM Controller

**Our flagship 10-channel WiFi LED PWM controller.**

![](/uploads/products/blc10mk3/blc10mk3-white-2.jpg)

{{< /brick_title >}}

{{< brick_wide >}}

Colorata (Model BLC10MK3) is our flagship 10-channel, all-in-one, WiFi LED PWM embedded controller module, developed for passionate engineers and lighting product manufacturers. Colorata is the "Pro" version of our highly successful 6-channel model, [Buce](./buce). It offers enhanced and superior features in every aspect while still maintaining a highly affordable cost.


## Applications

Colorata integrates all the necessary hardware and software for high-end reef aquarium LED lights in the smallest form factor and at the low cost. It has simple peripheral circuitry, making it super easy to embed into products.

* High-end aquarium lighting.
* Photography lighting.
* And more.

{{< tabs >}}

## Hardware

* ESP32 MCU
* LED PWM channels: 10
* Ten independent PWM dimming channels, with software-configurable dimming frequency (up to 19 kHz), 12-bit 4096-level duty cycle range.
* Supports phase shifting for PWM signal, significantly reducing the peak current of the LED driver when not running at full power.
* NTC temperature sensing channels: 4
* LED indicator: Addressable RGB
* Compact size of only 22×30mm.
* Built-in voltage regulator, allowing direct input of 5~36V voltage.
* Built-in power voltage measurement circuit, with the option to connect an INA138/INA139 for current and power measurement.
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

|  | **BLC06E** | **BLC10**    |
|:---------------|:-----|:----- |
| **Dimensions** | 25 × 20 mm | 35 × 22 mm |
| **MCU** | ESP32-C3 | ESP32 |
| **LED PWM Channels** | 6 | 10 |
| **NTC Channels** | 1 | 4 |
| **PWM Fan** | ✔ | ✔ |
| **Two-Wire Fan** | ✔ | ✔ |
| **Indicator LED** | Addressable RGB LED | Addressable RGB LED |
| **External Indicator** | ✔ | ✔ |
| **RTC (Real-Time Clock)**  | ESP32-C3 Built-in | PCF8563 |
| **RTC Battery**  | × | ✔ |
| **Press Button**  | ✔ | ✔     |
| **Extra GPIO Pins**  | × |  ✔ |
| **Voltage Measurement**  | ✔ |  ✔ |
| **LED Current Measurement**  | ✔ |  ✔ |
| **Extra GPIO Pins**  | × |  ✔ |
| **Interface** | 2×10 Pin, 0.8 mm Pitch, SMD B2B header | 2×15 Pin, 0.05"(1.27 mm) Pitch, SMD Pin-header |

{{< /brick_wide >}}

---

{{< brick_contact >}}{{< /brick_contact >}}