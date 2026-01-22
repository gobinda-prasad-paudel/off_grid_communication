# Off-Grid Communication System

This project implements an **off-grid communication system** designed to enable connectivity in remote areas, especially during natural disasters such as floods, earthquakes, or GLOFs, when conventional GSM networks may be unavailable. The system is inspired by walkie-talkie functionality but uses affordable, rapidly deployable hardware to facilitate communication for local communities.

## Features

- **LoRa-based Communication**: Enables long-range wireless communication between devices.
- **ESP32 Microcontroller**: Serves as the core hardware for sending and receiving messages.
- **Offline Messaging**: Planned capability for offline mobile-to-mobile messaging via LoRa modules connected through USB.
- **Rapid Deployment**: Can be quickly distributed to local users during emergencies.
- **Scalable Design**: Designed to expand coverage and integrate with additional modules in the future.

## Hardware

- ESP32 Microcontroller
- LoRa Transceiver Modules
- USB interface for device connectivity
- Power supply (battery or solar)

## Software

- Python backend for message routing
- Node.js server for management and logging
- MQTT protocol for lightweight messaging
- Arduino IDE for ESP32 firmware

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/gobinda-prasad-paudel/off_grid_communication.git
