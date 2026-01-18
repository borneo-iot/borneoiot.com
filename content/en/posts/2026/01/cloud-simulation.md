---
title: "Cloud Simulation: A More Natural Light Experience for Your Coral Tank"
seo:
  title: Cloud Simulation in Our ESP32 based open-source aquarium LED controller
image: /uploads/gallery/clouds.jpg
date: 2026-01-18 00:00:00
tags:
  - aquarium
  - iot
  - pwm
  - feature
---

We've added a new feature to our open-source aquarium LED controller that's typically only found in high-end commercial coral lighting systems: **Cloud Simulation**. 
This feature automatically creates realistic, random cloud shadows throughout the day.

## What is Cloud Simulation?

Imagine standing on a tropical reef on a sunny day. The sun is bright, but as clouds drift across the sky, the light becomes softer for a moment before brightening again. This happens constantly in nature—subtle, random, completely natural.

**Cloud Simulation** brings this natural light variation to your aquarium. Instead of lights that stay exactly the same brightness all day, our new feature adds gentle, realistic cloud shadows that come and go throughout your lighting schedule.

## Why Does This Matter?

While this feature may not be essential for coral health, it adds a delightful visual dynamism to your aquarium. By introducing subtle, random cloud shadows, it creates an ever-changing light show that makes your tank feel more alive and upgraded. Most importantly, it brings an element of fun and surprise to your daily viewing experience, turning routine observations into exciting moments of discovery.

## How Does It Work?

Cloud Simulation happens automatically in the background with random timing where shadow events occur every 5–30 minutes, just like real clouds. Each shadow reduces brightness by 30%–60% to create realistic darkness and believable cloud cover, while fading in and out smoothly over 30 seconds to 5 minutes without sudden changes. The effect is always subtle, designed to be noticeable but gentle, never jarring.

Think of it as nature's dimmer switch—unpredictable, gentle, and always improving your tank's lighting.

## Easy to Control

By default, Cloud Simulation is disabled. You can easily enable it by opening the Borneo IoT App, navigating to the device settings, and tapping to turn it on.

## Real-World Example

Here's what you might see in your tank:

```
14:00 — Bright afternoon sun
14:15 — A cloud drifts by, light softens to 50% for 2 minutes
14:17 — Cloud passes, brightness returns to normal
14:45 — Another shadow, this time dropping to 35% brightness for 40 seconds
...and so on throughout the day
```

Your corals get the best of both worlds: a predictable, healthy light schedule **plus** the natural variation they evolved to thrive in.

## Perfect for Your Corals

Whether you keep SPS, LPS, or soft corals, Cloud Simulation provides a subtle enhancement that mimics natural reef conditions, reduces stress from static lighting, encourages more natural coral behavior, and is completely safe and reversible.

## Try It Today

Cloud Simulation is supported from firmware version 0.4 and above. If you want to experience the difference a more natural light environment can make, simply enable Cloud Drift in your settings and watch your aquarium come to life with realistic, dynamic lighting.

Have fun!