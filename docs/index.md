# Embedded Course Hardware

## Overview

This documentation collects the boards, tools, sensors, actuators, and basic electronic components used in the embedded development course.

The course mainly uses **ESP32-S3** and **STM32F411CEU6** boards. Most examples assume **3.3V logic**, so always check voltage levels, current limits, polarity, and wiring before connecting a component.

---

## Table of Contents

### Development Boards and Debugging Tools

| Component | Description |
|-----------|-------------|
| [ESP32-S3 N16R8](components/esp32s3-n16r8.md) | ESP32-S3 development board used for WiFi, GPIO, ADC, PWM, I2C, SPI, and UART practice. |
| [STM32F411 Black Pill](components/black-pill.md) | STM32F411CEU6 development board used for ARM Cortex-M programming and debugging. |
| [ST-Link V2](components/st-link-v2.md) | Debugger and programmer for STM32 boards. |
| [WeAct Mini Debugger](components/weact-st-link.md) | Compact ST-Link compatible debugger and programmer. |
| [USB-TTL Serial Adapter](components/usb-ttl-serial-adapter.md) | UART adapter for serial communication and debugging. |
| [Logic Analyzer](components/logic-analyzer.md) | Tool for inspecting digital signals such as UART, I2C, SPI, and PWM. |
| [Digital Multimeter](components/multimeter.md) | Measurement tool for voltage, resistance, continuity, current, and basic debugging. |

---

### Passive Components and Analog Sensors

| Component | Description |
|-----------|-------------|
| [LEDs](components/leds.md) | Basic output components for status indication, GPIO practice, and PWM brightness control. |
| [Resistors](components/resistors.md) | Passive components used for current limiting, pull-ups, pull-downs, and voltage dividers. |
| [Capacitors](components/capacitors.md) | Passive components used for filtering, decoupling, timing, and power stability. |
| [Diodes](components/diodes.md) | Protection components used for polarity, flyback, and one-way current flow. |
| [Transistors](components/transistors.md) | Switching components used to control larger currents from MCU GPIO pins. |
| [Potentiometers](components/potentiometers.md) | Adjustable voltage dividers for ADC input and user controls. |
| [Photoresistor](components/photoresistor.md) | Light-dependent resistor used for analog light sensing. |
| [Thermistors](components/thermistors.md) | Temperature-dependent resistors used for analog temperature measurement. |
| [Tactile Switches](components/tactile-switches.md) | Digital input buttons used for GPIO, interrupts, and debouncing practice. |

---

### Modules, Actuators, and Digital Sensors

| Component | Description |
|-----------|-------------|
| [Relay Module](components/relay-module.md) | Isolated switching module for controlling separate loads. |
| [DC Motor](components/dc-motor.md) | Brushed motor actuator used for driver circuits and PWM speed control. |
| [Servo Motor SG90](components/servo-motor.md) | Position control actuator driven by timer/PWM-style pulses. |
| [Rotary Encoder](components/rotary-encoder.md) | Incremental digital input component for menus and value selection. |
| [BME280](components/bme280.md) | Digital temperature, humidity, and pressure sensor using I2C or SPI. |
| [DS18B20](components/ds18b20.md) | Digital temperature sensor using the 1-Wire bus. |
| [DS1307 RTC](components/ds1307.md) | Real-time clock module with battery backup and I2C communication. |
| [SSD1306 OLED Display](components/ssd1306.md) | Small monochrome OLED display for text, sensor values, menus, and debugging. |
| [Passive Buzzer](components/buzzer.md) | Sound output component driven with PWM or square-wave signals. |

---

## How to Use These Pages

Each component page includes practical information for lab work:

- What the component does
- How it connects to ESP32-S3 or STM32F411 boards
- Important electrical limits
- Common wiring mistakes
- Basic calculations where useful
- Typical course examples

Before powering a circuit, verify:

- Supply voltage
- GPIO logic level
- Polarity
- Current consumption
- Common ground
- Pull-up or pull-down requirements
