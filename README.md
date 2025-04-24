# Bluetooth Car

This project is a software system designed to control a car via Bluetooth communication. It allows users to send commands to the car using a mobile app or other Bluetooth-enabled devices.I kind of wanted to built a car that has every features for controlling.

## Features

- Remote control of the car via Bluetooth.
- This car can also be controlled using voice and has autonomous driving using ultrasonic sensor
- Support for basic car movements (e.g., forward, backward, left, right).
- Easy-to-extend architecture for adding new features.

## Requirements

- A Bluetooth-enabled microcontroller (e.g., Arduino, ESP32).
- A compatible Bluetooth module (e.g., HC-05, HC-06).
- A mobile app or device capable of sending Bluetooth commands.
- Basic programming knowledge to modify and upload the code.

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/bluetooth-car.git
   cd bluetooth-car
   ```

2. Connect the Bluetooth module to your microcontroller as per the module's documentation.

3. Upload the firmware to the microcontroller using the provided source code.

4. Pair your Bluetooth device with the module and use a compatible app to send commands.

## Usage

- Use the mobile app to send commands like `F` (forward), `B` (backward), `L` (left), and `R` (right).
- Ensure the Bluetooth connection is active before sending commands.

## Demo

Below is a demonstration of the Bluetooth Car in action:

<iframe width="727" height="409" src="https://www.youtube.com/embed/VIBWdLLq9kQ" title="Git and GitHub Tutorial in Tamil | The Ultimate Guide to VC, Branching, Merging &amp; Pull Request." frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
