
# Off-Grid Communication System

## Overview
This project is an **off-grid communication system** designed to provide connectivity in remote areas and during natural disasters such as floods, earthquakes, and GLOFs, where conventional GSM networks may be unavailable. The system functions similarly to a walkie-talkie but is **affordable, rapid to deploy, and scalable** for local communities.  

Planned future upgrades include enabling offline mobile-to-mobile messaging using LoRa modules connected via USB, allowing messages to be sent without internet access.

## Features
- Low-cost communication in remote or disaster-affected areas.
- LoRa-based long-range messaging.
- Can operate independently of traditional network infrastructure.
- Designed for rapid deployment to local communities.
- Future support for offline mobile messaging via USB-connected LoRa modules.

## Technology Stack
- **Microcontroller:** ESP32
- **Communication Protocol:** LoRa
- **Programming:** Arduino, Python, Node.js
- **Messaging Broker:** MQTT

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/gobinda-prasad-paudel/off_grid_communication.git
````

2. Install dependencies for the backend (Node.js):

   ```bash
   npm install
   ```
3. Upload firmware to ESP32 using Arduino IDE.

## Usage

* Power up the ESP32 modules.
* Modules automatically establish a LoRa communication network.
* Messages can be sent via the connected interface to other nodes in the network.
* For advanced usage, integrate with USB-connected mobile devices (future feature).

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request for bug fixes, improvements, or new features.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

Gobinda Prasad Paudel
Email: [gobindapaudelofficial@gmail.com](mailto:gobindapaudelofficial@gmail.com)
Website: [gobindapoudel.com.np](https://gobindapoudel.com.np)
