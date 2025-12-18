# ESP32 + WS2812B (NeoPixel) Beginner Guide

A beginner-friendly guide to ESP32 covering basics, NeoPixel (WS2812B) interfacing, circuit diagrams, color control, LED effects, and a NeoPixel clock project.

---

## 📌 What You Will Learn
- ESP32 basics and GPIO overview
- What WS2812B (NeoPixel) LEDs are
- ESP32 ↔ WS2812B wiring and power requirements
- How to set colors using code
- Popular LED effects (blink, fade, rainbow)
- Building a simple NeoPixel clock

---

## 🧠 ESP32 Overview
ESP32 is a powerful microcontroller with:
- Dual-core processor
- Built-in Wi-Fi & Bluetooth
- Multiple GPIO pins
- PWM, ADC, SPI, I2C, UART support

It is widely used for IoT, automation, and embedded projects.

---

## 💡 WS2812B (NeoPixel) Overview
WS2812B is an addressable RGB LED where:
- Each LED can be controlled individually
- Only **one data pin** is required
- LEDs are connected in a chain
- Uses 5V power and a single data line

---

## 🔌 ESP32 ↔ WS2812B Connections

| WS2812B Pin | ESP32 Pin |
|------------|----------|
| VCC        | 5V (or external 5V) |
| GND        | GND |
| DIN        | GPIO 5 (recommended) |

⚠️ **Important Notes**
- Use a **330Ω resistor** in series with DATA line
- Use **1000µF capacitor** across 5V & GND
- For many LEDs, use **external 5V supply**

---

## 📂 Repository Structure
