# Atmel_M90E32AS_ESP32_Library
ESP32 Compatible Library for Poly-Phase High-Performance Wide-Span Energy Metering IC

[![Platfrom](https://skillicons.dev/icons?i=arduino)](https://skillicons.dev)
<img align="left" alt="medium" src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white" />


# Overview
The EnergyMeteringIC library enables precise monitoring of electrical parameters in a three-phase power system. It utilizes SPI communication to configure the M90E32AS IC, set line frequency and gains, and retrieve data such as voltage, current, power, power factor, frequency, and temperature. The library includes functions like readWriteRegister() and read32BitRegister() for efficient register access, with error detection for SPI failures (e.g., disconnected wires) to enhance reliability. Initial versions include Atmel_M90E32AS_ESP32.h and Atmel_M90E32AS_ESP32.cpp, released as of June 21, 2025.

# Features

    Supports ESP32 architecture.
    Configures Atmel's M90E32AS for three-phase energy monitoring.
    Retrieves voltage, current, power, power factor, frequency, and temperature.
    Implements SPI-based communication with error handling.
    Modular design for easy integration into Arduino projects.

# Installation
Via Arduino Library Manager

    Open the Arduino IDE.
    Go to Sketch > Include Library > Manage Libraries....
    Search for Atmel_M90E32AS_ESP32.
    Click Install Button.

# Manual Installation

    Download the latest release from the Releases page.
    Extract the .zip file.
    Move the Atmel_M90E32AS_ESP32 folder to your Arduino libraries directory (e.g., ~/Documents/Arduino/libraries/).
    Restart the Arduino IDE.
