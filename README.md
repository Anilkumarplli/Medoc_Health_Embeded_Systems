# Medoc_Health_Embeded_Systems
Wearable AI Pin Embedded System Engineer Assignment Solution.

# Overview

This repository contains our solution to the Wearable AI Pin Embedded System Engineer Assignment.
The detailed design, calculations, and firmware implementation are provided in the attached PDF document.

# What I Have Done

* Designed a dual-core embedded architecture to support always-on wake-word detection with low power consumption.
* Distributed tasks between a low-power core (continuous listening, buffering, button monitoring) and a high-performance core (Wi-Fi, cloud communication, audio processing).
* Analyzed power consumption to ensure 12+ hours of battery life.
* Performed audio buffer memory calculations and proposed practical solutions to fit within SRAM constraints.
* Designed a hardware-level privacy mute switch that physically cuts microphone power and cannot be overridden by software.

# Implemented a firmware state machine in C with:

* Hold-to-talk behavior
* Battery-level checks
* Safety timeout
* Error handling and recovery logic

# Documentation

* Full explanation and implementation details are available in the PDF uploaded separately.

# Technologies Used
* Embedded C
* State-machine–based firmware design
* Low-power embedded system architecture
