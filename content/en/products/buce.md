---
title: "Buce: 6-Channel All-in-One WiFi LED PWM Controller"
image: /uploads/products/blc06mk1/gallery/pins.jpg
---

Buce (Model BLC06MK1) is an innovative, open-source 6-channel all-in-one WiFi LED PWM controller designed for makers and engineers who love DIY lighting projects, particularly in aquariums and photography.

This versatile controller provides six independent PWM channels, allowing users to customize and control lighting effects wirelessly through our open-source mobile app. With multi-segment dimming capabilities, Buce can simulate natural daylight transitions, such as sunrise and sunset, enhancing the visual experience in various settings.


## Applications

* **Aquarium Lighting**
    Aquarium hobbyists can use Buce to simulate natural lighting environments, promoting the health and growth of aquatic plants or corals.
* **Photography Lighting**
    Photographers can set up dynamic lighting scenes to capture stunning images with precise control over brightness and color, perfect for studio or outdoor shoots.
* **Home Lighting**
    DIY enthusiasts can integrate Buce into their smart home systems to create personalized lighting ambiances for different rooms and occasions, with smooth transitions throughout the day.

{{< tabs >}}

## Dimming

- The firmware and mobile app support advanced programmable segmented dimming functions, including features like sunrise and sunset simulation. Supports linear, logarithmic, and CIE-1931 dimming algorithms.
- Supports scheduling mode, manual mode, and temporary appreciation mode.
- Six independent PWM dimming channels, with software-configurable dimming frequency (default 24kHz), 10-bit 1024-level duty cycle range.
- Supports phase shifting for PWM signal, significantly reducing the peak current of the LED driver when not running at full power.


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
* Communicate using CBOR over CoAP/UDP, and provide Python examples.

{{< /tabs >}}

## Pinout

![](/uploads/products/blc06mk1/gds.png)

---

## Resources

* [Datasheet](https://github.com/oldrev/borneo/tree/master/hw/datasheets)
* Online Documentation: [docs.borneoiot.com](https://docs.borneoiot.com/hardwares/buce)
* GitHub Repo: [github.com/oldrev/borneo](https://github.com/oldrev/borneo)


## Gallery

{{< gallery dir="/uploads/products/blc06mk1/gallery" >}} 