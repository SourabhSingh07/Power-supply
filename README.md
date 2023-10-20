# Power Supply

## Overview
This repository contains the design and documentation for a Universal Power Supply capable of converting 220V AC current to 5V, 9V, and 12V DC outputs. The power supply is built using voltage regulators (7805, 7809, and 7812), a bridge rectifier, and a filter circuit with a 1000µF capacitor. It's a versatile and reliable solution for providing different voltage levels for various electronic projects.

## Features
- **Multiple Voltage Outputs**: This power supply offers three fixed voltage outputs: 5V, 9V, and 12V, making it suitable for a wide range of electronic applications.
- **Stable and Regulated**: The voltage regulators ensure a stable and regulated DC voltage supply, reducing the risk of damage to connected components.
- **Overcurrent and Overheat Protection**: Built-in protection mechanisms prevent overcurrent and overheating issues, enhancing safety.
- **Compact and Efficient Design**: The power supply design is compact, making it suitable for various projects and prototyping needs.
- **Customizable**: The power supply can be customized with additional features, such as voltage display, current limiting, and more.

## Components
- **Voltage Regulators**: 7805 (5V), 7809 (9V), and 7812 (12V).
- **Bridge Rectifier**: Converts AC to DC.
- **Filter Capacitor**: A 1000µF capacitor for smoothing the output.
- **Transformer**: Provides the input AC voltage.
- **Heat Sink**: For dissipating heat from the voltage regulators.

## Schematics
- `schematics/`: Contains circuit diagrams and schematics of the power supply.

## Getting Started
1. **Assemble the Circuit**: Follow the provided circuit diagrams to assemble the power supply circuit.

2. **Testing**: Verify that the circuit is correctly assembled, and there are no loose connections.

3. **Power On**: Connect the power supply to a 220V AC source and ensure that the voltage regulators provide the expected DC output voltage levels (5V, 9V, and 12V).

4. **Usage**: Use the power supply for your electronic projects by connecting your devices to the respective output voltage.

Happy DIY Electronics Projects!
