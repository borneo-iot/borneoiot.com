---
title: "Moonlight Simulation Now Available"
seo:
  title: "Moonlight Simulation Now Live on the Open-Source Borneo-IoT Controller"
image: /uploads/gallery/moon.jpg
date: 2026-02-17 00:00:00
tags:
  - aquarium
  - iot
  - pwm
  - feature
---

Moonlight simulation now live on the open-source Borneo-IoT LED PWM controller.

We are excited to announce that the open-source Borneo-IoT controller now includes a built-in moonlight simulation feature. The microcontroller can use the current time together with a configured latitude and longitude to calculate the moon phase and the precise moonrise and moonset times. Those calculations run directly on the device so the controller can produce a smooth, natural moonlight curve without relying on external services.

The implementation performs astronomical computations on the MCU to determine lunar illumination and the timing of nightly lunar events. With those results the controller drives low-intensity LED channels to recreate realistic moonlight, including gradual moonrise and moonset transitions and subtle brightness changes through the lunar cycle. The simulation is energy efficient and designed to preserve dark intervals that are important for animal health.

For aquarists and reef keepers this feature has practical biological advantages. Many coral species time spawning and other reproductive behaviors to lunar cues, so providing accurate nocturnal illumination that mirrors natural conditions can encourage healthier reproductive cycles. At the same time the gentle nocturnal glow enhances the visual appeal of tanks after lights-out, giving hobbyists a more natural and engaging night view without disturbing the animals.

This capability is available now in the Borneo-IoT codebase and remains fully open source. We welcome feedback, contributions, and real world reports from the community on how moonlight simulation affects aquarium ecosystems and display aesthetics.

