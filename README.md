# Node RED Installation Instructions on Raspberry PI 

This repository provides resources and/or scripts to help install [Node-RED](https://nodered.org/) on a Raspberry Pi.

## Overview

Node-RED is a flow-based development tool for visual programming, ideally suited for IoT applications. This project aims to simplify the installation process of Node-RED on Raspberry Pi devices.

## Features

- Easy-to-follow installation instructions
- Automation scripts (if provided) for quick setup
- Designed for Raspberry Pi running Linux (Raspberry Pi OS)

## Prerequisites

- A Raspberry Pi device (any model should work)
- Raspberry Pi OS installed and updated
- Internet connection

## Installation
Use the below commands step-by-step on the raspberry pi device either using direct or remote connection: 

1. sudo apt update && sudo apt upgrade -y

2. sudo apt install build-essential git curl

3. bash <(curl -sL https://github.com/node-red/linux-installers/releases/latest/download/update-nodejs-and-nodered-deb)

4. sudo systemctl enable nodered.service

5. start node red with this command: node-red-start

6. Launch nodered by visiting: http://ip-address-of-raspberry-pi:1880. You can find the IP address by running hostname -I on the raspberry Pi terminal.

## Clone this repository 
1. Clone this repository:
   ```bash
   git clone https://github.com/arif6008/Node_red_install_raspberrypi.git
   ```
2. Review the contents of the repository for installation scripts or instructions.
3. Follow the steps provided in the scripts or documentation.

## Usage

- If there is an install script, run it using:
  ```bash
  bash install.sh
  ```
- Otherwise, follow the manual steps provided in the repository files.

## Documentation

- See [Node-RED Documentation](https://nodered.org/docs/) for more details on using Node-RED after installation.

## License

This project is licensed under the MIT License.

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss your ideas.

## Contact

For questions or support, open an issue in this repository.
